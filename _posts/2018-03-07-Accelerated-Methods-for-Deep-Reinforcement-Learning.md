---
layout: post
title: "Accelerated Methods for Deep Reinforcement Learning"
date: 2018-03-07 18:39:12
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Adam Stooke, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) has achieved many recent successes, yet experiment turn-around time remains a key bottleneck in research and in practice. We investigate how to optimize existing deep RL algorithms for modern computers, specifically for a combination of CPUs and GPUs. We confirm that both policy gradient and Q-value learning algorithms can be adapted to learn using many parallel simulator instances. We further find it possible to train using batch sizes considerably larger than are standard, without negatively affecting sample complexity or final performance. We leverage these facts to build a unified framework for parallelization that dramatically hastens experiments in both classes of algorithm. All neural network computations use GPUs, accelerating both data collection and training. Our results include using an entire NVIDIA DGX-1 to learn successful strategies in Atari games in single-digit minutes, using both synchronous and asynchronous algorithms.

##### Abstract (translated by Google)
深入强化学习（RL）已经取得了许多最近的成功，但实验周转时间仍然是研究和实践中的关键瓶颈。我们研究如何优化现代计算机的现有深度RL算法，特别是针对CPU和GPU的组合。我们确认策略梯度和Q值学习算法都可以用来学习使用许多并行模拟器实例。我们进一步发现可以使用比标准更大的批量进行培训，而不会对样品复杂性或最终性能产生负面影响。我们利用这些事实为并行化构建了一个统一的框架，大大加快了两类算法的实验。所有神经网络计算都使用GPU，加速数据收集和培训。我们的成果包括使用整个NVIDIA DGX-1，以单位数分钟学习Atari游戏的成功策略，同时使用同步和异步算法。

##### URL
[http://arxiv.org/abs/1803.02811](http://arxiv.org/abs/1803.02811)

##### PDF
[http://arxiv.org/pdf/1803.02811](http://arxiv.org/pdf/1803.02811)

