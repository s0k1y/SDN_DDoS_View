the SIDS is less efficient in detecting zero-day vulnerabilities
because its functionality is reactive. In other words, the attack must be known so that it is included in the signature


偏密码
给流量打标签加密后 进行对比

我们不做
做不来


主要研究加密算法



该方法通过分析IP流的不同维度来创建模式。分析源IP地址、目的IP地址和端口号的位、包及其流量/秒的熵值，计算IP流量维数。它使用
数字签名技术，为每个维度生成签名。将其与实时IP流的签名进行比较，如果不一致，再与已知的攻击签名进行比较来识别攻击。这种技术的限制是它不能适用于零日攻击。