---
layout: post
title: "Averaging Weights Leads to Wider Optima and Better Generalization"
date: 2018-08-08 08:49:15
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
深度神经网络通常通过使用SGD变体优化损失函数以及衰减学习速率来训练，直到收敛。我们表明，沿着SGD轨迹的多个点的简单平均，具有周期性或恒定的学习率，导致比传统训练更好的泛化。我们还表明，这个随机权重平均（SWA）过程找到比SGD更广泛的最优值，并且用单个模型近似最近的快速几何集合（FGE）方法。使用SWA，我们在CIFAR-10，CIFAR-100和ImageNet上的一系列最先进的残留网络，PyramidNets，DenseNets和Shake-Shake网络上，与传统的SGD培训相比，在测试精度方面取得了显着的提高。简而言之，SWA非常容易实现，改进了泛化，并且几乎没有计算开销。

##### URL
[http://arxiv.org/abs/1803.05407](http://arxiv.org/abs/1803.05407)

##### PDF
[http://arxiv.org/pdf/1803.05407](http://arxiv.org/pdf/1803.05407)

