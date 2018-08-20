---
layout: post
title: "Informed Sampling for Asymptotically Optimal Path Planning"
date: 2018-08-17 07:41:14
categories: arXiv_RO
tags: arXiv_RO Knowledge
author: Jonathan D Gammell, Timothy D Barfoot, Siddhartha S Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
Anytime almost-surely asymptotically optimal planners, such as RRT*, incrementally find paths to every state in the search domain. This is inefficient once an initial solution is found as then only states that can provide a better solution need to be considered. Exact knowledge of these states requires solving the problem but can be approximated with heuristics. 
 This paper formally defines these sets of states and demonstrates how they can be used to analyze arbitrary planning problems. It uses the well-known $L^2$ norm (i.e., Euclidean distance) to analyze minimum-path-length problems and shows that existing approaches decrease in effectiveness factorially (i.e., faster than exponentially) with state dimension. It presents a method to address this curse of dimensionality by directly sampling the prolate hyperspheroids (i.e., symmetric $n$-dimensional ellipses) that define the $L^2$ informed set. 
 The importance of this direct informed sampling technique is demonstrated with Informed RRT*. This extension of RRT* has less theoretical dependence on state dimension and problem size than existing techniques and allows for linear convergence on some problems. It is shown experimentally to find better solutions faster than existing techniques on both abstract planning problems and HERB, a two-arm manipulation robot.

##### Abstract (translated by Google)
任何时候几乎肯定渐近最优的规划器，例如RRT *，逐步找到搜索域中每个状态的路径。一旦找到初始解决方案，这是低效的，因为只需要考虑能够提供更好解决方案的状态。对这些状态的准确了解需要解决问题，但可以用启发式方法进行近似。
 本文正式定义了这些状态集，并演示了如何使用它们来分析任意规划问题。它使用众所周知的$ L ^ 2 $范数（即欧几里德距离）来分析最小路径长度问题，并且表明现有方法随着状态维度在因子上（即，比指数地更快）有效地降低。它提出了一种通过直接采样定义$ L ^ 2 $通知集的长椭球（即，对称$ n $  - 维椭圆）来解决这种维数灾难的方法。
 使用Informed RRT *证明了这种直接知情抽样技术的重要性。与现有技术相比，RRT *的这种扩展对状态维度和问题大小的理论依赖性较小，并且允许在一些问题上进行线性收敛。实验证明，在抽象规划问题和双臂操纵机器人HERB上，比现有技术更快地找到更好的解决方案。

##### URL
[http://arxiv.org/abs/1706.06454](http://arxiv.org/abs/1706.06454)

##### PDF
[http://arxiv.org/pdf/1706.06454](http://arxiv.org/pdf/1706.06454)

