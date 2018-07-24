---
layout: post
title: "signProx: One-Bit Proximal Algorithm for Nonconvex Stochastic Optimization"
date: 2018-07-20 20:47:32
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Ulugbek S. Kamilov
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic gradient descent (SGD) is one of the most widely used optimization methods for parallel and distributed processing of large datasets. One of the key limitations of distributed SGD is the need to regularly communicate the gradients between different computation nodes. To reduce this communication bottleneck, recent work has considered a one-bit variant of SGD, where only the sign of each gradient element is used in optimization. In this paper, we extend this idea by proposing a stochastic variant of the proximal-gradient method that also uses one-bit per update element. We prove the theoretical convergence of the method for non-convex optimization under a set of explicit assumptions. Our results indicate that the compressed method can match the convergence rate of the uncompressed one, making the proposed method potentially appealing for distributed processing of large datasets.

##### Abstract (translated by Google)
随机梯度下降（SGD）是用于大数据集的并行和分布式处理的最广泛使用的优化方法之一。分布式SGD的一个关键限制是需要定期传送不同计算节点之间的梯度。为了减少这种通信瓶颈，最近的工作考虑了SGD的一位变体，其中只有每个梯度元素的符号用于优化。在本文中，我们通过提出近端梯度方法的随机变体来扩展这个想法，该方法也使用每个更新元素一位。我们证明了在一组显式假设下非凸优化方法的理论收敛性。我们的结果表明，压缩方法可以匹配未压缩方法的收敛速度，使得该方法可能对大数据集的分布式处理具有吸引力。

##### URL
[http://arxiv.org/abs/1807.08023](http://arxiv.org/abs/1807.08023)

##### PDF
[http://arxiv.org/pdf/1807.08023](http://arxiv.org/pdf/1807.08023)

