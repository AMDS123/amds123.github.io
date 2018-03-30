---
layout: post
title: "Normalization of Neural Networks using Analytic Variance Propagation"
date: 2018-03-28 12:37:27
categories: arXiv_CV
tags: arXiv_CV
author: Alexander Shekhovtsov, Boris Flach
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of estimating statistics of hidden units in a neural network using a method of analytic moment propagation. These statistics are useful for approximate whitening of the inputs in front of saturating non-linearities such as a sigmoid function. This is important for initialization of training and for reducing the accumulated scale and bias dependencies (compensating covariate shift), which presumably eases the learning. In batch normalization, which is currently a very widely applied technique, sample estimates of statistics of hidden units over a batch are used. The proposed estimation uses an analytic propagation of mean and variance of the training set through the network. The result depends on the network structure and its current weights but not on the specific batch input. The estimates are suitable for initialization and normalization, efficient to compute and independent of the batch size. The experimental verification well supports these claims. However, the method does not share the generalization properties of BN, to which our experiments give some additional insight.

##### Abstract (translated by Google)
我们解决了使用分析矩传播方法估计神经网络中隐藏单元统计量的问题。这些统计数据对于饱和非线性（如S形函数）前输入的近似白化很有用。这对于训练的初始化和减少积累的尺度和偏差依赖性（补偿协变量偏移）是重要的，这可能简化了学习。在批量标准化中，这是当前应用非常广泛的一种技术，使用了对一批中隐藏单位统计的样本估计。所提出的估计使用通过网络的训练集的均值和方差的分析传播。结果取决于网络结构及其当前权重，但不取决于具体的批量输入。这些估计值适用于初始化和标准化，计算效率高且与批量大小无关。实验证实很好地支持了这些说法。然而，该方法不能共享BN的泛化属性，我们的实验给出了一些额外的见解。

##### URL
[https://arxiv.org/abs/1803.10560](https://arxiv.org/abs/1803.10560)

##### PDF
[https://arxiv.org/pdf/1803.10560](https://arxiv.org/pdf/1803.10560)

