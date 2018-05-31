---
layout: post
title: "Resilient Non-Submodular Maximization over Matroid Constraints"
date: 2018-05-28 20:44:03
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Vasileios Tzoumas, Ali Jadbabaie, George J. Pappas
mathjax: true
---

* content
{:toc}

##### Abstract
The control and sensing of large-scale systems results in combinatorial problems not only for sensor and actuator placement but also for scheduling or observability/controllability. Such combinatorial constraints in system design and implementation can be captured using a structure known as matroids. In particular, the algebraic structure of matroids can be exploited to develop scalable algorithms for sensor and actuator selection, along with quantifiable approximation bounds. However, in large-scale systems, sensors and actuators may fail or may be (cyber-)attacked. The objective of this paper is to focus on resilient matroid-constrained problems arising in control and sensing but in the presence of sensor and actuator failures. In general, resilient matroid-constrained problems are computationally hard. Contrary to the non-resilient case (with no failures), even though they often involve objective functions that are monotone or submodular, no scalable approximation algorithms are known for their solution. In this paper, we provide the first algorithm, that also has the following properties: First, it achieves system-wide resiliency, i.e., the algorithm is valid for any number of denial-of-service attacks or failures. Second, it is scalable, as our algorithm terminates with the same running time as state-of-the-art algorithms for (non-resilient) matroid-constrained optimization. Third, it provides provable approximation bounds on the system performance, since for monotone objective functions our algorithm guarantees a solution close to the optimal. We quantify our algorithm's approximation performance using a notion of curvature for monotone (not necessarily submodular) set functions. Finally, we support our theoretical analyses with numerical experiments, by considering a control-aware sensor selection scenario, namely, sensing-constrained robot navigation.

##### Abstract (translated by Google)
大型系统的控制和感测不仅导致传感器和致动器布置的组合问题，而且导致调度或可观察性/可控性。系统设计和实现中的这种组合约束可以使用称为matroids的结构来捕获。具体而言，可以利用矩阵的代数结构来开发用于传感器和执行器选择的可扩展算法以及可量化的近似边界。但是，在大型系统中，传感器和执行器可能会失效或可能（网络）受到攻击。本文的目标是着重讨论在控制和传感中出现的弹性模拟约束问题，但存在传感器和执行器故障时。一般来说，弹性的matroid约束问题在计算上很难。与非弹性的情况（没有失败）相反，尽管它们通常涉及单调或子模块的目标函数，但是他们的解决方案中没有可扩展的近似算法。在本文中，我们提供了第一种算法，它也具有以下特性：首先，它实现了系统范围内的弹性，即该算法适用于任何数量的拒绝服务攻击或失败。其次，它是可扩展的，因为我们的算法终止运行时间与最先进的（非弹性）matroid约束优化算法相同。第三，它提供了对系统性能的可证明的近似界限，因为对于单调目标函数，我们的算法保证解决方案接近最优。我们使用单调（不一定是子模块）集函数的曲率概念来量化我们的算法的逼近性能。最后，我们通过考虑控制感知传感器选择场景，即感测约束机器人导航，通过数值实验支持我们的理论分析。

##### URL
[http://arxiv.org/abs/1804.01013](http://arxiv.org/abs/1804.01013)

##### PDF
[http://arxiv.org/pdf/1804.01013](http://arxiv.org/pdf/1804.01013)

