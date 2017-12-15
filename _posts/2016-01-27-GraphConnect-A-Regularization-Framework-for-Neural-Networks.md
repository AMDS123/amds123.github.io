---
layout: post
title: "GraphConnect: A Regularization Framework for Neural Networks"
date: 2016-01-27 03:21:15
categories: arXiv_CV
tags: arXiv_CV Regularization Relation
author: Jiaji Huang, Qiang Qiu, Robert Calderbank, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have proved very successful in domains where large training sets are available, but when the number of training samples is small, their performance suffers from overfitting. Prior methods of reducing overfitting such as weight decay, Dropout and DropConnect are data-independent. This paper proposes a new method, GraphConnect, that is data-dependent, and is motivated by the observation that data of interest lie close to a manifold. The new method encourages the relationships between the learned decisions to resemble a graph representing the manifold structure. Essentially GraphConnect is designed to learn attributes that are present in data samples in contrast to weight decay, Dropout and DropConnect which are simply designed to make it more difficult to fit to random error or noise. Empirical Rademacher complexity is used to connect the generalization error of the neural network to spectral properties of the graph learned from the input data. This framework is used to show that GraphConnect is superior to weight decay. Experimental results on several benchmark datasets validate the theoretical analysis, and show that when the number of training samples is small, GraphConnect is able to significantly improve performance over weight decay.

##### Abstract (translated by Google)
深度神经网络在大型训练集可用的领域已经证明是非常成功的，但是当训练样本数量很小时，其性能会受到过度拟合的影响。现有的减少过度配合的方法，如重量衰减，Dropout和DropConnect都是与数据无关的。本文提出了一种新的方法GraphConnect，它是依赖于数据的，并且是通过观察数据感兴趣的数据靠近一个流形的。新方法鼓励学习决策之间的关系类似于一个表示流形结构的图形。本质上，GraphConnect旨在学习数据样本中存在的属性，而不是重量衰减，Dropout和DropConnect，这些属性被设计为使其更难以适应随机误差或噪声。经验性的Rademacher复杂性被用来将神经网络的泛化误差与从输入数据中学习的图谱的光谱特性联系起来。这个框架用来显示GraphConnect优于重量衰减。在几个基准数据集上的实验结果验证了理论分析，并且显示当训练样本的数量很小时，GraphConnect能够显着提高性能而不是重量衰减。

##### URL
[https://arxiv.org/abs/1512.06757](https://arxiv.org/abs/1512.06757)

##### PDF
[https://arxiv.org/e-print/1512.06757](https://arxiv.org/e-print/1512.06757)

