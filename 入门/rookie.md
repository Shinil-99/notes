# Title:Data Mining - Practical Machine Learning Tools and Techniques

目的是为了入门，能看懂Prof. Shin Matsushima 最新的一篇论文

从目录来看，分为数据挖掘初步与高级机器学习方案两部分。作为初步，先看数据挖掘的基础概念部分。有些名词的专业性较高，为了未来的进一步学习，深入学习应该使用英文版的图书和文献。github中有《统计学习方法》与《机器学习》的代码示例，可以进行克隆学习。

### 数据挖掘基础
data mining = Knowledge Discovery in Database (KDD)  
need: tools for 从海量数据中发现有价值的信息  
数据仓库：多个异构数据源在单个站点以统一的模式组织的存储，以支持管理决策  
proceed：清理、集成、选择、变换、挖掘、评估、表示
elements：统计、机器学习、数据库的应用

本书的前半部分基本上与《统计学习方法》的内容相同，后半部分为机器学习相关的简单介绍。

# Title:Deep Learning Essentials

目的入门了解。  
前言中提到深度学习时图像识别、物体识别和自然语言处理问题解决方案的好的提供者。目前来看NLP相关的应用可能与未来学习相关。除了前两章的基础介绍，第八章及之后的所有内容均可阅读了解。

深度学习采用的方法是模仿神经元层中的活动。“深”在于有多个<u>非线性特征变换形态</u>。  
浅层算法更多地关注特征工程和特征选择，而深度学习算法强调定义和最有用的计算拓扑图(计算架构)以及正确有效的参数或超参数优化方法，以便使学到的数据表示具有良好的泛化能力。  
深度学习有一定程度的硬件需求。Python与C++是主流深度学习使用和维护语言。  

大量具有标签的训练数据的获取代价有时候很高，如何直接通过不带标签的数据进行学习是一个难点。对于传统深度学习进行改进的强化学习，在不同的网络结构中各自的特点和应用也不同。

处理数据、选择优化函数、数据模型压缩以及如何利用现有的预训练模型，都是进一步提高学习能力的突破口。目前深度学习的流行方向在于生成对抗网络，这一点在许多领域的动态数据学习中都有所应用。

# Title: The Elements of Statistical Learning: Data Ming, Inference and Prediction

Briefly get started to Statistical Learning 

### Chap1 Introduction

1. supervised & unsupervised learning problem
2. Examples used statistical learning tools
3. Chap1-4&7 are mandatory for concepts definitions. In this book they use R as programming language.

### Chap2 Overview of Supervised Learning

1. input, output, and their meanings in supervised learning
2. input = predictor (statistical context) = independent variable = feature (recognition context)
    output = response = dependent variable
3. regression = predict quantitative outputs
   classification = predict qualitative outputs

4. Linear Model  
    $$\hat{Y} = \hat{\beta_0} + \sum_{j=1}^p X_j \hat{\beta_j}$$   
    $$RSS(\beta) = \sum_{i=1}^N (y_i - x_i^T \beta)^2$$
5. Nearest-Neighbor Method
   $$\hat(Y)(x) = \frac{1}{k} \sum_{x_i \in N_k(x)} y_i$$

*之后的内容尽可能略去数学的部分，着重在名词解释和通用知识*