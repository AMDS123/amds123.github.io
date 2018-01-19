---
layout: post
title: "Sparsely Connected Convolutional Networks"
date: 2018-01-18 01:02:58
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Ligeng Zhu, Ruizhi Deng, Zhiwei Deng, Greg Mori, Ping Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Residual learning with skip connections permits training ultra-deep neural networks and obtains superb performance. Building in this direction, DenseNets proposed a dense connection structure where each layer is directly connected to all of its predecessors. The densely connected structure leads to better information flow and feature reuse. However, the overly dense skip connections also bring about the problems of potential risk of overfitting, parameter redundancy and large memory consumption. In this work, we analyze the feature aggregation patterns of ResNets and DenseNets under a uniform aggregation view framework. We show that both structures densely gather features from previous layers in the network but combine them in their respective ways: summation (ResNets) or concatenation (DenseNets). We compare the strengths and drawbacks of these two aggregation methods and analyze their potential effects on the networks' performance. Based on our analysis, we propose a new structure named SparseNets which achieves better performance with fewer parameters than DenseNets and ResNets.

##### Abstract (translated by Google)
残余学习跳过连接允许训练超深度神经网络，并获得一流的表现。在这个方向上建设，DenseNets提出了一个密集的连接结构，其中每一层直接连接到所有的前辈。密集连接的结构导致更好的信息流和功能重用。然而，过度密集的跳过连接也带来了过度拟合，参数冗余和大内存消耗的潜在风险问题。在这项工作中，我们分析统一聚合视图框架下的ResNets和DenseNets的特征聚合模式。我们显示两个结构密集地收集来自网络中以前层的特征，但是以它们各自的方式组合它们：求和（ResNets）或串联（DenseNets）。我们比较这两种聚合方法的优缺点，并分析它们对网络性能的潜在影响。基于我们的分析，我们提出了一个名为SparseNets的新结构，其参数比DenseNets和ResNets更少。

##### URL
[http://arxiv.org/abs/1801.05895](http://arxiv.org/abs/1801.05895)

##### PDF
[http://arxiv.org/pdf/1801.05895](http://arxiv.org/pdf/1801.05895)

