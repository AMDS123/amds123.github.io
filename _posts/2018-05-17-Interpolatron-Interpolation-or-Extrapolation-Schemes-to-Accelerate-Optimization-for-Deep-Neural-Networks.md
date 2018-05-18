---
layout: post
title: "Interpolatron: Interpolation or Extrapolation Schemes to Accelerate Optimization for Deep Neural Networks"
date: 2018-05-17 13:29:33
categories: arXiv_AI
tags: arXiv_AI Optimization Gradient_Descent
author: Guangzeng Xie, Yitan Wang, Shuchang Zhou, Zhihua Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we explore acceleration techniques for large scale nonconvex optimization problems with special focuses on deep neural networks. The extrapolation scheme is a classical approach for accelerating stochastic gradient descent for convex optimization, but it does not work well for nonconvex optimization typically. Alternatively, we propose an interpolation scheme to accelerate nonconvex optimization and call the method Interpolatron. We explain motivation behind Interpolatron and conduct a thorough empirical analysis. Empirical results on DNNs of great depths (e.g., 98-layer ResNet and 200-layer ResNet) on CIFAR-10 and ImageNet show that Interpolatron can converge much faster than the state-of-the-art methods such as the SGD with momentum and Adam. Furthermore, Anderson's acceleration, in which mixing coefficients are computed by least-squares estimation, can also be used to improve the performance. Both Interpolatron and Anderson's acceleration are easy to implement and tune. We also show that Interpolatron has linear convergence rate under certain regularity assumptions.

##### Abstract (translated by Google)
在本文中，我们探讨了大型非凸优化问题的加速技术，特别关注深度神经网络。外推方案是用于加速凸优化的随机梯度下降的经典方法，但它通常不适用于非凸优化。或者，我们提出一种插值方案来加速非凸优化并调用插值法。我们解释了Interpolatron背后的动机并进行了彻底的实证分析。在CIFAR-10和ImageNet上深度DNNs（例如，98层ResNet和200层ResNet）的实验结果表明，Interpolatron的收敛速度要远远高于最新的方法，如带有动量的SGD，亚当。此外，Anderson加速度也可用于改善性能，其中混合系数通过最小二乘估计来计算。 Interpolatron和Anderson的加速都很容易实现和调整。我们还表明，在一定的规律性假设下，内插子具有线性收敛速度。

##### URL
[http://arxiv.org/abs/1805.06753](http://arxiv.org/abs/1805.06753)

##### PDF
[http://arxiv.org/pdf/1805.06753](http://arxiv.org/pdf/1805.06753)

