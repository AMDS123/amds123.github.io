---
layout: post
title: "DiracNets: Training Very Deep Neural Networks Without Skip-Connections"
date: 2018-01-26 14:08:57
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Inference Classification
author: Sergey Zagoruyko, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks with skip-connections, such as ResNet, show excellent performance in various image classification benchmarks. It is though observed that the initial motivation behind them - training deeper networks - does not actually hold true, and the benefits come from increased capacity, rather than from depth. Motivated by this, and inspired from ResNet, we propose a simple Dirac weight parameterization, which allows us to train very deep plain networks without explicit skip-connections, and achieve nearly the same performance. This parameterization has a minor computational cost at training time and no cost at all at inference, as both Dirac parameterization and batch normalization can be folded into convolutional filters, so that network becomes a simple chain of convolution-ReLU pairs. We are able to match ResNet-1001 accuracy on CIFAR-10 with 28-layer wider plain DiracNet, and closely match ResNets on ImageNet. Our parameterization also mostly eliminates the need of careful initialization in residual and non-residual networks. The code and models for our experiments are available at https://github.com/szagoruyko/diracnets

##### Abstract (translated by Google)
具有跳过连接的深度神经网络（如ResNet）在各种图像分类基准中表现出优异的性能。据观察，他们背后的最初动机 - 培养更深层次的网络 - 实际上并不是真实的，好处来自能力的提高，而不是深度。受此启发，受ResNet的启发，我们提出了一个简单的Dirac权重参数化方案，它使我们能够在没有明确的跳过连接的情况下训练非常深的普通网络，并获得接近相同的性能。由于Dirac参数化和批量归一化都可以折叠成卷积滤波器，所以这种参数化在训练时间上具有较小的计算成本，并且根本没有任何成本，因此网络变成了简单的卷积链（ReLU对）。我们可以将CIFAR-10上的ResNet-1001精度与28层宽平原DiracNet相匹配，并且与ImageNet上的ResNets紧密匹配。我们的参数化也大多消除了在残留和非残留网络中仔细初始化的需要。 https://github.com/szagoruyko/diracnets上提供了我们实验的代码和模型

##### URL
[http://arxiv.org/abs/1706.00388](http://arxiv.org/abs/1706.00388)

##### PDF
[http://arxiv.org/pdf/1706.00388](http://arxiv.org/pdf/1706.00388)

