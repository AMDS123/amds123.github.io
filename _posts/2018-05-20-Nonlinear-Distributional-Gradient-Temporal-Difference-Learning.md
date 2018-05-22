---
layout: post
title: "Nonlinear Distributional Gradient Temporal-Difference Learning"
date: 2018-05-20 08:43:05
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Chao Qu, Shie Mannor, Huan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We devise a distributional variant of gradient temporal-difference (TD) learning. Distributional reinforcement learning has been demonstrated to outperform the regular one in the recent study \citep{bellemare2017distributional}. In our paper, we design two new algorithms called distributional GTD2 and distributional TDC using the Cram{\'e}r distance on the distributional version of the Bellman error objective function, which inherits advantages of both the nonlinear gradient TD algorithms and the distributional RL approach. We prove the asymptotic almost-sure convergence to a local optimal solution for general smooth function approximators, which includes neural networks that have been widely used in recent study to solve the real-life RL problems. In each step, the computational complexity is linear w.r.t.\ the number of the parameters of the function approximator, thus can be implemented efficiently for neural networks.

##### Abstract (translated by Google)
我们设计了梯度时间差（TD）学习的分布变体。在最近的研究中，分布式强化学习已被证明优于常规强化学习{citep {bellemare2017distributional}。在本文中，我们设计了两种新算法，称为分布式GTD2和分布式TDC，使用贝尔曼误差目标函数的分布版本上的Cram {r} r距离，该算法继承了非线性梯度TD算法和分布RL做法。我们证明了一般光滑函数逼近器的局部最优解的渐近几乎收敛性，其中包括近期研究中广泛用于解决实际RL问题的神经网络。在每一步中，计算复杂度都是函数逼近器参数的数量，因此可以有效地实现神经网络。

##### URL
[https://arxiv.org/abs/1805.07732](https://arxiv.org/abs/1805.07732)

##### PDF
[https://arxiv.org/pdf/1805.07732](https://arxiv.org/pdf/1805.07732)

