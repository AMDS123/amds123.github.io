---
layout: post
title: "A Surprising Linear Relationship Predicts Test Performance in Deep Networks"
date: 2018-07-25 15:20:02
categories: arXiv_AI
tags: arXiv_AI Classification Relation
author: Qianli Liao, Brando Miranda, Andrzej Banburski, Jack Hidary, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
Given two networks with the same training loss on a dataset, when would they have drastically different test losses and errors? Better understanding of this question of generalization may improve practical applications of deep networks. In this paper we show that with cross-entropy loss it is surprisingly simple to induce significantly different generalization performances for two networks that have the same architecture, the same meta parameters and the same training error: one can either pretrain the networks with different levels of "corrupted" data or simply initialize the networks with weights of different Gaussian standard deviations. A corollary of recent theoretical results on overfitting shows that these effects are due to an intrinsic problem of measuring test performance with a cross-entropy/exponential-type loss, which can be decomposed into two components both minimized by SGD -- one of which is not related to expected classification performance. However, if we factor out this component of the loss, a linear relationship emerges between training and test losses. Under this transformation, classical generalization bounds are surprisingly tight: the empirical/training loss is very close to the expected/test loss. Furthermore, the empirical relation between classification error and normalized cross-entropy loss seem to be approximately monotonic

##### Abstract (translated by Google)
鉴于两个网络在数据集上具有相同的训练损失，他们什么时候会有完全不同的测试损失和错误？更好地理解这个泛化问题可以改善深度网络的实际应用。在本文中，我们表明，对于具有相同架构，相同元参数和相同训练误差的两个网络，对于交叉熵损失，引起显着不同的泛化性能是非常简单的：可以预先训练具有不同级别的网络。 “损坏的”数据或简单地用不同高斯标准偏差的权重初始化网络。最近关于过拟合的理论结果的推论表明，这些效应是由于交叉熵/指数型损失测量测试性能的固有问题，可以将其分解为两个组件，这两个组件都被SGD最小化 - 其中一个是与预期的分类性能无关。但是，如果我们将损失的这一部分分解出来，那么训练和测试损失之间就会出现线性关系。在这种转变下，经典的泛化界限出乎意料地紧张：经验/训练损失非常接近预期/测试损失。此外，分类误差与归一化交叉熵损失之间的经验关系似乎近似单调

##### URL
[http://arxiv.org/abs/1807.09659](http://arxiv.org/abs/1807.09659)

##### PDF
[http://arxiv.org/pdf/1807.09659](http://arxiv.org/pdf/1807.09659)

