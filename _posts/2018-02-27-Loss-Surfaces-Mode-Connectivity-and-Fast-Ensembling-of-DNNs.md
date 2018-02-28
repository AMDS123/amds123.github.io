---
layout: post
title: "Loss Surfaces, Mode Connectivity, and Fast Ensembling of DNNs"
date: 2018-02-27 17:13:28
categories: arXiv_AI
tags: arXiv_AI Face
author: Timur Garipov, Pavel Izmailov, Dmitrii Podoprikhin, Dmitry P. Vetrov, Andrew Gordon Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
The loss functions of deep neural networks are complex and their geometric properties are not well understood. We show that the optima of these complex loss functions are in fact connected by a simple polygonal chain with only one bend, over which training and test accuracy are nearly constant. We introduce a training procedure to discover these high-accuracy pathways between modes. Inspired by this new geometric insight, we propose a new ensembling method entitled Fast Geometric Ensembling (FGE). Using FGE we can train high-performing ensembles in the time required to train a single model. We achieve improved performance compared to the recent state-of-the-art Snapshot Ensembles, on CIFAR-10 and CIFAR-100, using state-of-the-art deep residual networks. On ImageNet we improve the top-1 error-rate of a pre-trained ResNet by 0.56% by running FGE for just 5 epochs.

##### Abstract (translated by Google)
深度神经网络的损失函数是复杂的，它们的几何特性不是很好理解。我们证明，这些复杂损失函数的最优值实际上是通过一个简单的多边形链连接的，只有一个弯曲，训练和测试精度几乎是恒定的。我们引入一个训练程序来发现模式之间的这些高精度路径。受这种新的几何见解的启发，我们提出了一种称为快速几何集成（FGE）的新组合方法。使用FGE，我们可以在训练单个模型所需的时间内训练高性能的合奏队。与最近最先进的Snapshot Ensembles相比，CIFAR-10和CIFAR-100采用最先进的深度残留网络，我们实现了性能提升。在ImageNet上，我们通过运行FGE 5个纪元，将预先训练的ResNet的前1个错误率提高了0.56％。

##### URL
[http://arxiv.org/abs/1802.10026](http://arxiv.org/abs/1802.10026)

##### PDF
[http://arxiv.org/pdf/1802.10026](http://arxiv.org/pdf/1802.10026)

