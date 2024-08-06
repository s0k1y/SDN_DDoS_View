# 有监督模型 -目标变量可用

## 单模型
### 分类 -连续目标变量 sum:7
#### LVQ sum:1
#### 朴素贝叶斯(NB) sum:1
##### gaussian naive bayes (GNB) sum: -1
#### 最近邻(Nearest Neighbor) sum:3
##### KNN(k近邻) -sum:4
###### KNN-DPTCM
##### Nearest Centroid (NC) 
#### CRF (Conditional Random Fields)
#### 最大熵模型

### 回归 -分类目标变量
基本是线性模型
####  线性回归
##### Generalized Linear Model (GLM)
####  逻辑回归
####  Lasso
####  Ridge
#### 判别分析(Discrimant Analysis)
##### LDA(线性判别分析)
##### QDA(二次判别分析)
#### 最大熵模型 (Maximum Entropy Model)
### 决策树(DT) sum:8
####  ID3
####  C5.0
##### C4.5 sum:1
##### J48 sum:2
####  CART
####  贝叶斯网络 sum:1

### 神经网络(NN) /Deep Learning -sum:10
Neural Nerwork
####  感知器
##### MLP 多层感知器 -sum:2
####  概率图模型

#### ANN -sum:2
#### DNN -sum:3
###### + SAE(Stacked Autoencoders)  sum:1
###### + DBNs(Deep Belief Networks) sum:1
#### FNN
Feedforward Neural Network
#### RNN -sum:4
循环神经网络
##### LSTM(long short-term memory) -sum:3
##### GRU
###### Cu-DNNGRU sum:1
 D. Javeed, T. Gao, M. T. Khan, and I. Ahmad, ‘‘A hybrid deep learningdriven SDN enabled mechanism for secure communication in Internet of
Things (IoT),’’ Sensors, vol. 21, no. 14, p. 4884, Jul. 2021.
##### CuBLSTM sum:1
 D. Javeed, T. Gao, M. T. Khan, and I. Ahmad, ‘‘A hybrid deep learningdriven SDN enabled mechanism for secure communication in Internet of
Things (IoT),’’ Sensors, vol. 21, no. 14, p. 4884, Jul. 2021.
#### GANs -sum:1
生成对抗网络（Generative Adversarial Networks, GANs
###  支持向量机(SVM) -sum:10
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
####  随机森林 sum:7
####  Bagging Tree (BT)

# 半监督模型 -目标变量部分可用
Semi-Supervised Learning
## 分类
####  EM算法
## 聚类

# 无监督模型 -目标变量不可用 

## 聚类 sum:2
(CLUSTERING)
### Density-Based Clustering
基于密度
#### DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
基于密度的空间聚类算法，能够发现任意形状的簇。
#### DenStream
算法，用于识别密度变化并检测异常行为。
### Distance-Based Clustering
#### K-means
一种流行的聚类算法，通过最小化簇内平方误差来分组数据点。-sum:2
### Hierarchy Clustering
#### BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies)
一种层次聚类算法，特别适合大规模数据集。
#### Agglomerative Clustering (Hierarchical Clustering)
自底向上层次聚类算法，逐步合并最相似的簇。
### Other Clustering Methods
#### Self-Organizing Map (SOM) -sum:1
##### Dynamic Self-Organizing Map (DSOM) -sum:1
#### K-Medoids
#### Fuzzy C-Means
#### Gaussian Mixture Models (GMM)
##### MCMC 
(Markov Chain Monte Carlo) for Parameter Estimation Bayesian Networks
#### Hidden Markov Models (HMM)
#### Spectral Clustering
#### EM Algorithm 
(通常用于 Gaussian Mixture Models 和 Hidden Markov Models)

## 降维 
(Dimensionality Reduction)

### PCA 
(Principal Component Analysis): 主成分分析，用于降维和特征提取。
### SVD 
(Singular Value Decomposition)
奇异值分解，用于降维。
### DBNs sum:1
Deep Belief Networks
### SAE sum:1
Stacked Autoencoders

### 降维与可视化

#### t-SNE
(t-distributed Stochastic Neighbor Embedding): 一种用于可视化高维数据的非线性降维技术，尽管通常用于可视化，但也可用于聚类。









# 强化学习 sum:2
## Decision Making
#### Q-Learning sum:1
#### R-Learning
#### TD-Learning
#### Deep Deterministic Policy Gradient(DDPG)
##### Multi-Agent Deep Deterministic Policy Gradient (MADDPG) sum:1
## 分类目标变量-分类
## 目标变量不可用-控制
# 分布式机器学习技术 sum:1
## 分裂学习
## 联邦学习

