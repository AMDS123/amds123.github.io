---
layout: post
title: "Adaptive Stochastic Gradient Langevin Dynamics: Taming Convergence and Saddle Point Escape Time"
date: 2018-05-23 20:26:56
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Hejian Sang, Jia Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new adaptive stochastic gradient Langevin dynamics (ASGLD) algorithmic framework and its two specialized versions, namely adaptive stochastic gradient (ASG) and adaptive gradient Langevin dynamics(AGLD), for non-convex optimization problems. All proposed algorithms can escape from saddle points with at most $O(\log d)$ iterations, which is nearly dimension-free. Further, we show that ASGLD and ASG converge to a local minimum with at most $O(\log d/\epsilon^4)$ iterations. Also, ASGLD with full gradients or ASGLD with a slowly linearly increasing batch size converge to a local minimum with iterations bounded by $O(\log d/\epsilon^2)$, which outperforms existing first-order methods.

##### Abstract (translated by Google)
在本文中，我们针对非凸优化问题提出了一种新的自适应随机梯度Langevin动力学（ASGLD）算法框架及其两个专门版本，即自适应随机梯度（ASG）和自适应梯度Langevin动力学（AGLD）。所有提出的算法都可以避免鞍点，最多可以$ O（\ log d）$迭代，这几乎是无维度的。此外，我们显示ASGLD和ASG以最多$ O（\ log d / \ epsilon ^ 4）$迭代收敛到局部最小值。此外，具有完全梯度的ASGLD或缓慢线性增加的批量大小的ASGLD通过以$ O（\ log d / \ epsilon ^ 2）$为界的迭代收敛到局部最小值，其优于现有的一阶方法。

##### URL
[http://arxiv.org/abs/1805.09416](http://arxiv.org/abs/1805.09416)

##### PDF
[http://arxiv.org/pdf/1805.09416](http://arxiv.org/pdf/1805.09416)

