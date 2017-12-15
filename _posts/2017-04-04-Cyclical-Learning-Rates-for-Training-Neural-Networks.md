---
layout: post
title: "Cyclical Learning Rates for Training Neural Networks"
date: 2017-04-04 11:34:46
categories: arXiv_CV
tags: arXiv_CV Classification
author: Leslie N. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
It is known that the learning rate is the most important hyper-parameter to tune for training deep neural networks. This paper describes a new method for setting the learning rate, named cyclical learning rates, which practically eliminates the need to experimentally find the best values and schedule for the global learning rates. Instead of monotonically decreasing the learning rate, this method lets the learning rate cyclically vary between reasonable boundary values. Training with cyclical learning rates instead of fixed values achieves improved classification accuracy without a need to tune and often in fewer iterations. This paper also describes a simple way to estimate "reasonable bounds" -- linearly increasing the learning rate of the network for a few epochs. In addition, cyclical learning rates are demonstrated on the CIFAR-10 and CIFAR-100 datasets with ResNets, Stochastic Depth networks, and DenseNets, and the ImageNet dataset with the AlexNet and GoogLeNet architectures. These are practical tools for everyone who trains neural networks.

##### Abstract (translated by Google)
众所周知，学习率是调整深度神经网络最重要的超参数。本文介绍了一种设置学习率的新方法，即循环学习率，它实际上消除了通过实验找到全球学习率的最佳值和时间表的需求。这种方法不是单调地减少学习速率，而是让学习速率在合理的边界值之间循环变化。使用周期性学习率而不是固定值进行训练可以实现更高的分类准确性，而无需调整，而且往往需要更少的迭代次数。本文还描述了一个简单的方法来估计“合理范围” - 线性增加网络的学习率在几个时代。此外，循环学习率在CIFAR-10和CIFAR-100数据集上用ResNet，随机深度网络和DenseNets以及带有AlexNet和GoogLeNet架构的ImageNet数据集进行演示。这些都是训练神经网络的每个人的实用工具。

##### URL
[https://arxiv.org/abs/1506.01186](https://arxiv.org/abs/1506.01186)

##### PDF
[https://arxiv.org/pdf/1506.01186](https://arxiv.org/pdf/1506.01186)

