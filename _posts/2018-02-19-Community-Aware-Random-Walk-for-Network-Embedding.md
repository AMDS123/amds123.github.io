---
layout: post
title: "Community Aware Random Walk for Network Embedding"
date: 2018-02-19 15:57:36
categories: arXiv_AI
tags: arXiv_AI Embedding Classification Prediction Gradient_Descent
author: Mohammad Mehdi Keikha, Maseud Rahgozar, Masoud Asadpour
mathjax: true
---

* content
{:toc}

##### Abstract
Social network analysis provides meaningful information about behavior of network members that can be used for diverse applications such as classification, link prediction. However, network analysis is computationally expensive because of feature learning for different applications. In recent years, many researches have focused on feature learning methods in social networks. Network embedding represents the network in a lower dimensional representation space with the same properties which presents a compressed representation of the network. In this paper, we introduce a novel algorithm named "CARE" for network embedding that can be used for different types of networks including weighted, directed and complex. Current methods try to preserve local neighborhood information of nodes, whereas the proposed method utilizes local neighborhood and community information of network nodes to cover both local and global structure of social networks. CARE builds customized paths, which are consisted of local and global structure of network nodes, as a basis for network embedding and uses the Skip-gram model to learn representation vector of nodes. Subsequently, stochastic gradient descent is applied to optimize our objective function and learn the final representation of nodes. Our method can be scalable when new nodes are appended to network without information loss. Parallelize generation of customized random walks is also used for speeding up CARE. We evaluate the performance of CARE on multi label classification and link prediction tasks. Experimental results on various networks indicate that the proposed method outperforms others in both Micro and Macro-f1 measures for different size of training data.

##### Abstract (translated by Google)
社交网络分析提供了有关网络成员行为的有意义的信息，可用于各种应用，如分类，链接预测。然而，由于针对不同应用的特征学习，网络分析在计算上是昂贵的。近年来，许多研究集中在社交网络中的特征学习方法。网络嵌入表示具有相同属性的低维表示空间中的网络，其呈现网络的压缩表示。在本文中，我们引入了一种名为“CARE”的网络嵌入算法，可用于不同类型的网络，包括加权，定向和复杂网络。目前的方法试图保留节点的邻居信息，而所提出的方法利用网络节点的局部邻域和社区信息来覆盖社交网络的局部和全局结构。 CARE构建由网络节点的局部和全局结构组成的定制路径作为网络嵌入的基础，并使用Skip-gram模型学习节点的表示向量。随后，应用随机梯度下降来优化我们的目标函数并学习节点的最终表示。当新节点附加到网络而没有信息丢失时，我们的方法可以扩展。并行生成定制的随机散步也用于加速CARE。我们评估CARE在多标签分类和链接预测任务上的表现。在各种网络上的实验结果表明，所提出的方法在不同大小的训练数据的微观和宏观测量方面都优于其他方法。

##### URL
[http://arxiv.org/abs/1710.05199](http://arxiv.org/abs/1710.05199)

##### PDF
[http://arxiv.org/pdf/1710.05199](http://arxiv.org/pdf/1710.05199)

