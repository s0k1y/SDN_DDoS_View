# 攻击溯源
## IP路径追踪
对IP伪造式的DDoS效果 有待进一步确认
## 交换机逐级回溯
确认主机后下发流规则遏制
## AS级回溯方法
## 接口级回溯方法
## 攻击路径预测
### 三层攻击图(TAG)预测攻击路径。

# 访问控制
## 身份验证
### 检测到主机异常则三次握手确定合法性,非法则加入访问控制列表作为攻击者
### 交换机身份验证
#### 区块链
### 源地址验证 防IP欺骗
验证失败则下发流规则阻止相关流量   --VAVE应用  来源:Exploring Security Dynamics in SDN Controller Architectures Threat Landscape and Implications  
### 基于角色
### 基于证书
### 基于用户 
### 基于令牌的身份验证系统
### 多因素认证
### 公钥密码
#### 公钥基础设施(PKI)+ECC+AES
### 安全协议
## 流验证
#### 基于用户的流验证机制
保护网络免受未认证用户DDoS  --FlowNAC机制   来源:
Exploring Security Dynamics in SDN Controller Architectures Threat Landscape and Implications  

# 流量调度
分散攻击流量
## 拓扑结构设计
## 负载均衡
### 分布式缓解
#### 以分布式控制器网络弹性容错机制 集群抵御
##### Gossip分布式通信协议

### 路由/重定向
#### 路由表平衡算法
#### 选择性重路由
#### 临界流重路由
##### Bellman-Ford 算法最短路径路由
#### 重定向至蜜罐/可消耗服务器
### 基于策略的流量调度

Belyaev et al 来源:
Exploring Security Dynamics in SDN Controller Architectures Threat Landscape and Implications  
#### 利用域名间隔/网络地址转换来分配流量
# 流量限制
## 主机处理
### 黑名单封禁
## 阻塞端口 
### 短时阻断
#### 禁用一段时间 过期恢复
## 限速 
### 按目标分类
#### 交换机到控制器 
##### PPS
packets per second (pps) 
### 按作用对象分类
#### 所有交换机
#### 指定交换机
### 按速率调整分类
#### 固定速率
#### 动态速率
## 限制生成
### 如Openflow中交换机限制异步消息packet_in的生成

# 流量过滤(清洗)
## 控制器可对交换机消息进行过滤
## 防火墙

# 交换机内存管理
## 流规则存储空间管理
### 数据结构
#### 背包
#### 令牌桶
#### cuckoo-filter
#### scalable bloom filter
#### 概率数据结构
##### bloom-filter(BF)

## 流规则替换(驱逐)
用新条目替换旧的流表条目
###  删除
#### FIFO
#### 最近最少使用(LRU)
#### 流条目学习排序
25.12 认同
#### k-相似贪婪树

### 超时
超时值(改进配置参数)
具有较大的超时值意味着旧的规则会持续存在于流表中，从而阻止新流规则的创建。然而，具有较低的超时值会导致较大的开销，因为交换机需要不断地为先前已知的流重新请求规则。流规则超时值对交换机性能和DDoS成功率有显著影响
来源:Denial-of-service attacks in OpenFlow SDN networks
#### 固定超时
##### 流状态超时
##### 硬超时
##### 空闲超时
#### 动态超时
##### 随机化超时值
##### 基于时间侧信道推断超时值
Y. Shen, C. Wu, D. Kong, and Q. Cheng, ‘‘Flow table saturation attack
against dynamic timeout mechanisms in SDN,’’ Appl. Sci., vol. 13, no. 12,
p. 7210, Jun. 2023.

## 流规则压缩(聚合)
适用于不需要对单个流进行高度控制的网络，否则不适合。
### 使用通配符来减少规则数量
#### 访问控制规则
#### 转发规则
## 流规则拆分与分发
### 复杂规则拆分成多条简单规则分布在多交换机
## 交换机缓存Table-miss并主动分析与生成流规则
针对数据平面饱和DoS 检测到攻击后，将Table-miss重定向到数据平面缓存，主动流规则分析器直接在数据平面上生成和安装新的流规则，并动态更新它们

