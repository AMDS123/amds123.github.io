---
layout: post
title: "Averaging Weights Leads to Wider Optima and Better Generalization"
date: 2018-03-14 17:09:27
categories: arXiv_AI
tags: arXiv_AI
author: Pavel Izmailov, Dmitrii Podoprikhin, Timur Garipov, Dmitry Vetrov, Andrew Gordon Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are typically trained by optimizing a loss function with an SGD variant, in conjunction with a decaying learning rate, until convergence. We show that simple averaging of multiple points along the trajectory of SGD, with a cyclical or constant learning rate, leads to better generalization than conventional training. We also show that this Stochastic Weight Averaging (SWA) procedure finds much broader optima than SGD, and approximates the recent Fast Geometric Ensembling (FGE) approach with a single model. Using SWA we achieve notable improvement in test accuracy over conventional SGD training on a range of state-of-the-art residual networks, PyramidNets, DenseNets, and Shake-Shake networks on CIFAR-10, CIFAR-100, and ImageNet. In short, SWA is extremely easy to implement, improves generalization, and has almost no computational overhead.

##### Abstract (translated by Google)
深度神经网络通常通过使用SGD变量优化损失函数以及衰减学习率来训练，直到收敛。我们表明，沿着SGD的轨迹的多个点的简单平均，具有周期性或恒定的学习率，导致比传统训练更好的泛化。我们还表明，这种随机加权平均（SWA）程序发现比SGD更广泛的最优化，并且近似于最近的使用单个模型的快速几何集成（FGE）方法。使用SWA，我们在CIFAR-10，CIFAR-100和ImageNet上与传统的SGD培训相比，在一系列最先进的残留网络，PyramidNets，DenseNets和Shake-Shake网络上实现了测试精度的显着提高。简而言之，SWA非常容易实现，改进了泛化，几乎没有计算开销。

##### URL
[https://arxiv.org/abs/1803.05407](https://arxiv.org/abs/1803.05407)

##### PDF
[https://arxiv.org/pdf/1803.05407](https://arxiv.org/pdf/1803.05407)

