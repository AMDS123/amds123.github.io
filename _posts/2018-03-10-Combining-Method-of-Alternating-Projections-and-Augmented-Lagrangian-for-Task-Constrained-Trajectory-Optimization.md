---
layout: post
title: "Combining Method of Alternating Projections and Augmented Lagrangian for Task Constrained Trajectory Optimization"
date: 2018-03-10 10:03:09
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Arun Kumar Singh, Reza Ghabcheloo, Andreas Muller, Harit Pandya
mathjax: true
---

* content
{:toc}

##### Abstract
Motion planning for manipulators under task space constraints is difficult as it constrains the joint configurations to always lie on an implicitly defined manifold. It is possible to view task constrained motion planning as an optimization problem with non-linear equality constraints which can be solved by general non-linear optimization techniques. In this paper, we present a novel custom optimizer which exploits the underlying structure present in many task constraints. 
 At the core of our approach are some simple reformulations, which when coupled with the \emph{method of alternating projection}, leads to an efficient convex optimization based routine for computing a feasible solution to the task constraints. We subsequently build on this result and use the concept of Augmented Lagrangian to guide the feasible solutions towards those which also minimize the user defined cost function. We show that the proposed optimizer is fully distributive and thus, can be easily parallelized. We validate our formulation on some common robotic benchmark problems. In particular, we show that the proposed optimizer achieves cyclic motion in the joint space corresponding to a similar nature trajectory in the task space. Furthermore, as a baseline, we compare the proposed optimizer with an off-the-shelf non-linear solver provide in open source package SciPy. We show that for similar task constraint residuals and smoothness cost, it can be upto more than three times faster than the SciPy alternative.

##### Abstract (translated by Google)
任务空间约束下的操纵器的运动规划是困难的，因为它将关节配置限制为总是位于隐式定义的流形上。可以将任务约束运动规划视为具有可以通过一般非线性优化技术来解决的非线性等式约束的优化问题。在本文中，我们提出了一种新颖的自定义优化器，它利用了许多任务约束中存在的基础结构。
 我们的方法的核心是一些简单的重新表述，当与交替投影方法相结合时，导致基于有效凸面优化的例程来计算任务约束的可行解决方案。我们随后在这个结果的基础上，使用增广拉格朗日的概念来指导那些最小化用户定义成本函数的可行解。我们表明，所提出的优化器是完全分配的，因此可以很容易地并行化。我们对一些常见的机器人基准测试问题进行了验证。具体来说，我们表明，所提出的优化器在对应于任务空间中的类似自然轨迹的联合空间中实现循环运动。此外，作为基准，我们将提议的优化器与开源软件包SciPy中提供的现成非线性求解器进行比较。我们表明，对于类似的任务约束残差和平滑成本，它可以比SciPy替代方案快三倍以上。

##### URL
[http://arxiv.org/abs/1803.03784](http://arxiv.org/abs/1803.03784)

##### PDF
[http://arxiv.org/pdf/1803.03784](http://arxiv.org/pdf/1803.03784)

