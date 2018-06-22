---
layout: post
title: "Error Compensated Quantized SGD and its Applications to Large-scale Distributed Optimization"
date: 2018-06-21 03:21:24
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Jiaxiang Wu, Weidong Huang, Junzhou Huang, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale distributed optimization is of great importance in various applications. For data-parallel based distributed learning, the inter-node gradient communication often becomes the performance bottleneck. In this paper, we propose the error compensated quantized stochastic gradient descent algorithm to improve the training efficiency. Local gradients are quantized to reduce the communication overhead, and accumulated quantization error is utilized to speed up the convergence. Furthermore, we present theoretical analysis on the convergence behaviour, and demonstrate its advantage over competitors. Extensive experiments indicate that our algorithm can compress gradients by a factor of up to two magnitudes without performance degradation.

##### Abstract (translated by Google)
大规模分布式优化在各种应用中非常重要。对于基于数据并行的分布式学习，节点间梯度通信常常成为性能瓶颈。在本文中，我们提出了误差补偿量化随机梯度下降算法来提高训练效率。对局部梯度进行量化以减少通信开销，并利用积累的量化误差来加速收敛。此外，我们对收敛行为进行理论分析，并展示其优于竞争对手的优势。大量的实验表明，我们的算法可以将梯度压缩高达两个量级，而不会降低性能。

##### URL
[http://arxiv.org/abs/1806.08054](http://arxiv.org/abs/1806.08054)

##### PDF
[http://arxiv.org/pdf/1806.08054](http://arxiv.org/pdf/1806.08054)

