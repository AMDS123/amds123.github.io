---
layout: post
title: "Understanding symmetries in deep networks"
date: 2015-11-03 18:50:03
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Vijay Badrinarayanan, Bamdev Mishra, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works have highlighted scale invariance or symmetry present in the weight space of a typical deep network and the adverse effect it has on the Euclidean gradient based stochastic gradient descent optimization. In this work, we show that a commonly used deep network, which uses convolution, batch normalization, reLU, max-pooling, and sub-sampling pipeline, possess more complex forms of symmetry arising from scaling-based reparameterization of the network weights. We propose to tackle the issue of the weight space symmetry by constraining the filters to lie on the unit-norm manifold. Consequently, training the network boils down to using stochastic gradient descent updates on the unit-norm manifold. Our empirical evidence based on the MNIST dataset shows that the proposed updates improve the test performance beyond what is achieved with batch normalization and without sacrificing the computational efficiency of the weight updates.

##### Abstract (translated by Google)
最近的研究强调了典型深度网络权重空间中的尺度不变性或对称性，以及它对基于欧几里得梯度的随机梯度下降优化的不利影响。在这项工作中，我们展示了一个常用的深度网络，它使用卷积，批量归一化，reLU，max-pooling和sub-sampling管道，具有更复杂的对称形式，由于网络权重的基于比例的重新参数化而产生。我们建议通过将滤波器限制在单位范数流形上来解决权重空间对称性的问题。因此，训练网络归结为在单位范数流形上使用随机梯度下降更新。我们基于MNIST数据集的经验证据表明，所提出的更新提高了测试性能，超出了批量标准化所实现的性能，并且不会牺牲加权更新的计算效率。

##### URL
[https://arxiv.org/abs/1511.01029](https://arxiv.org/abs/1511.01029)

##### PDF
[https://arxiv.org/pdf/1511.01029](https://arxiv.org/pdf/1511.01029)

