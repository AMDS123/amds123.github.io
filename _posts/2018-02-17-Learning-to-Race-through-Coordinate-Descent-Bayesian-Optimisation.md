---
layout: post
title: "Learning to Race through Coordinate Descent Bayesian Optimisation"
date: 2018-02-17 03:19:43
categories: arXiv_RO
tags: arXiv_RO
author: Rafael Oliveira, Fernando H.M. Rocha, Lionel Ott, Vitor Guizilini, Fabio Ramos, Valdir Grassi Jr
mathjax: true
---

* content
{:toc}

##### Abstract
In the automation of many kinds of processes, the observable outcome can often be described as the combined effect of an entire sequence of actions, or controls, applied throughout its execution. In these cases, strategies to optimise control policies for individual stages of the process might not be applicable, and instead the whole policy might have to be optimised at once. On the other hand, the cost to evaluate the policy's performance might also be high, being desirable that a solution can be found with as few interactions as possible with the real system. We consider the problem of optimising control policies to allow a robot to complete a given race track within a minimum amount of time. We assume that the robot has no prior information about the track or its own dynamical model, just an initial valid driving example. Localisation is only applied to monitor the robot and to provide an indication of its position along the track's centre axis. We propose a method for finding a policy that minimises the time per lap while keeping the vehicle on the track using a Bayesian optimisation (BO) approach over a reproducing kernel Hilbert space. We apply an algorithm to search more efficiently over high-dimensional policy-parameter spaces with BO, by iterating over each dimension individually, in a sequential coordinate descent-like scheme. Experiments demonstrate the performance of the algorithm against other methods in a simulated car racing environment.

##### Abstract (translated by Google)
在多种过程的自动化中，可观察的结果常常被描述为整个执行过程中应用的整个动作序列或控制的组合效果。在这些情况下，针对流程的各个阶段优化控制策略的策略可能不适用，而整个策略可能不得不一次优化。另一方面，评估政策绩效的成本可能也很高，希望可以通过尽可能少的与真实系统的互动找到解决方案。我们考虑优化控制策略的问题，以允许机器人在最短的时间内完成给定的赛道。我们假设机器人没有关于赛道或其自身动力学模型的先前信息，只是最初的有效驾驶示例。本地化仅用于监视机器人并提供沿着轨道中心轴的位置的指示。我们提出了一种方法，用于找到一种策略，在保持车辆在轨道上使用贝叶斯优化（BO）方法在再生核Hilbert空间上保持最小化每圈时间。我们应用一种算法来更有效地在BO维度上的高维策略参数空间上进行搜索，方法是在一个顺序坐标下降式方案中逐个迭代每个维度。实验证明了算法在模拟赛车环境中与其他方法的性能。

##### URL
[http://arxiv.org/abs/1802.06179](http://arxiv.org/abs/1802.06179)

##### PDF
[http://arxiv.org/pdf/1802.06179](http://arxiv.org/pdf/1802.06179)

