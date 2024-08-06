# 有监督模型 -目标变量可用 

## 单模型
### 分类 -连续目标变量 sum:7
#### LVQ sum:1
#### 朴素贝叶斯(NB) sum:2
#### 最近邻(Nearest Neighbor) sum:3
##### KNN(k近邻) -sum:4
###### KNN-DPTCM
#### CRF (Conditional Random Fields)
#### 最大熵模型

### 回归 -分类目标变量
基本是线性模型
####  线性回归
####  逻辑回归
####  Lasso
####  Ridge
#### 判别分析(Discrimant Analysis)
##### LDA(线性判别分析)
##### QDA(二次判别分析)
#### 最大熵模型 (Maximum Entropy Model)

### 决策树(DT) sum:7
####  ID3
####  C5.0
##### C4.5 sum:1
##### J48 sum:2
####  CART
####  贝叶斯网络 sum:1

### 神经网络(NN) -sum:4
Neural Nerwork
####  感知器
##### MLP 多层感知器 -sum:2
####  概率图模型

#### ANN -sum:2
#### DNN -sum:1
###  支持向量机(SVM) -sum:7
#### SMO sum:1

Support Vector Machine
####  线性可分
####  线性支持
####  线性不可分
## 集成学习(ensemble)
### Boosting sum:5
####  CBDT
####  AdaBoost sum:1
####  XGBoost sum:3
####  LightGBM
####  CatBoost
####  Gradient Boost sum:1
### Bagging sum:4
####  随机森林 sum:4
# 无监督模型 -目标变量不可用 

## 聚类 sum:2
(CLUSTERING)
#### SOM sum:1
##### DSOM sum:1
####  kmeans -sum:1
#### K-Medoids
####  Fuzzy C-Means
####  Hierachical
####  Gaussion Mixture(混合高斯模型)
##### MCMC 用于参数估计
#####  贝叶斯网络
####  Hidden Markov Model(HMM)
####  层次聚类
####  谱聚类
####  EM算法


## 降维
####  PCA
####  SVD
####  概率图模型
# 半监督模型 -目标变量部分可用
Semi-Supervised Learning
## 分类
####  EM算法
## 聚类
# 强化学习
## Decision Making
#### Q-Learning
#### R-Learning
#### TD-Learning
## 分类目标变量-分类
## 目标变量不可用-控制
# 分布式机器学习技术 sum:1
## 分裂学习
## 联邦学习