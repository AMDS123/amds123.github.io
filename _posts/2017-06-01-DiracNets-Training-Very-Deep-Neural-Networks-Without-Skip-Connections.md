---
layout: post
title: "DiracNets: Training Very Deep Neural Networks Without Skip-Connections"
date: 2017-06-01 17:02:11
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification
author: Sergey Zagoruyko, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks with skip-connections, such as ResNet, show excellent performance in various image classification benchmarks. It is though observed that the initial motivation behind them - training deeper networks - does not actually hold true, and the benefits come from increased capacity, rather than from depth. Motivated by this, and inspired from ResNet, we propose a simple Dirac weight parameterization, which allows us to train very deep plain networks without skip-connections, and achieve nearly the same performance. This parameterization has a minor computational cost at training time and no cost at all at inference. We're able to achieve 95.5% accuracy on CIFAR-10 with 34-layer deep plain network, surpassing 1001-layer deep ResNet, and approaching Wide ResNet. Our parameterization also mostly eliminates the need of careful initialization in residual and non-residual networks. The code and models for our experiments are available at this https URL

##### Abstract (translated by Google)
具有跳过连接的深度神经网络（如ResNet）在各种图像分类基准中表现出优异的性能。据观察，他们背后的初始动机 - 培养更深层次的网络 - 实际上并不是真的，而好处来自能力的提高，而不是深度。受此启发，受到ResNet的启发，我们提出了一个简单的Dirac权重参数化方案，它使我们能够训练非常深的普通网络而无需跳过连接，并且性能几乎相同。这种参数化在训练时间上具有较小的计算成本，在推理中完全没有成本。 CIFAR-10拥有34层深平面网络，超过1001层深度ResNet，接近Wide ResNet，能达到95.5％的精度。我们的参数化也大多消除了在残留和非残留网络中仔细初始化的需要。我们实验的代码和模型可以在https网址上找到

##### URL
[https://arxiv.org/abs/1706.00388](https://arxiv.org/abs/1706.00388)

##### PDF
[https://arxiv.org/pdf/1706.00388](https://arxiv.org/pdf/1706.00388)

