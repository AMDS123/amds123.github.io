---
layout: post
title: "Reservoir computing for spatiotemporal signal classification without trained output weights"
date: 2016-07-19 13:28:17
categories: arXiv_CV
tags: arXiv_CV RNN Classification
author: Ashley Prater
mathjax: true
---

* content
{:toc}

##### Abstract
Reservoir computing is a recently introduced machine learning paradigm that has been shown to be well-suited for the processing of spatiotemporal data. Rather than training the network node connections and weights via backpropagation in traditional recurrent neural networks, reservoirs instead have fixed connections and weights among the `hidden layer' nodes, and traditionally only the weights to the output layer of neurons are trained using linear regression. We claim that for signal classification tasks one may forgo the weight training step entirely and instead use a simple supervised clustering method based upon principal components of norms of reservoir states. The proposed method is mathematically analyzed and explored through numerical experiments on real-world data. The examples demonstrate that the proposed may outperform the traditional trained output weight approach in terms of classification accuracy and sensitivity to reservoir parameters.

##### Abstract (translated by Google)
水库计算是最近引入的机器学习范例，已被证明非常适合处理时空数据。传统的递归神经网络不是通过反向传播来训练网络节点连接和权值，而是在“隐藏层”节点之间具有固定的连接和权重，而传统上只有神经元输出层的权重是使用线性回归来训练的。我们声称，对于信号分类任务，可以完全放弃权重训练步骤，而是使用基于储集层状态规范的主成分的简单监督聚类方法。所提出的方法是通过对现实世界数据的数值实验进行数学分析和探索的。实例表明，所提出的方法在分类精度和对储层参数敏感性方面可能优于传统的训练输出权重方法。

##### URL
[https://arxiv.org/abs/1604.03073](https://arxiv.org/abs/1604.03073)

##### PDF
[https://arxiv.org/pdf/1604.03073](https://arxiv.org/pdf/1604.03073)

