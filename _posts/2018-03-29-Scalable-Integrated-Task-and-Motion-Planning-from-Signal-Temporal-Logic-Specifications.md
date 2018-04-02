---
layout: post
title: "Scalable Integrated Task and Motion Planning from Signal Temporal Logic Specifications"
date: 2018-03-29 20:44:55
categories: arXiv_RO
tags: arXiv_RO Optimization Inference
author: Rafael Rodrigues da Silva, Hai Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to develop formal methods to achieve a performance guaranteed integrated task and motion planning (ITMP) with respect to high-level specifications given by signal temporal logic (STL). It is a problem of practical importance because many safety-critical applications in robotics (e.g., navigation, manipulation, and surgery) and autonomous systems (e.g., unmanned aircraft and self-driving cars) require a correct-by-construction design for complex missions. Traditional approaches usually assumed a discretization of the continuous state space or a finite partition of the workspace. Instead, we propose an abstraction-free method that synthesis continuous trajectories with respect to given STL specifications directly. For this, our basic idea is to leverage incremental constraint solving by efficiently adding constraints on motion feasibility at the discrete level. Our approach solves the ITMP from STL specification problem using a scalable logic-based inference combined with optimization, which uses efficient solvers, i.e., satisfiability modulo theories (SMT) and linear programming (LP). Consequently, our method has potential to scale up to handle high dimensional continuous dynamics. The proposed design algorithms are proved to be sound and complete, and numerical results are given to illustrate the effectiveness of the design algorithms.

##### Abstract (translated by Google)
本文旨在通过信号时态逻辑（STL）给出的高级规范来开发形式化方法，以实现性能保证的集成任务和运动规划（ITMP）。这是一个具有实际重要性的问题，因为机器人（例如导航，操纵和手术）以及自主系统（例如无人驾驶飞机和自动驾驶汽车）中的许多安全关键应用需要针对复杂任务进行正确的建筑设计。传统方法通常假定连续状态空间的离散化或工作空间的有限分割。相反，我们提出了一种无抽象方法，它可以直接综合关于给定STL规范的连续轨迹。为此，我们的基本思想是通过有效地在离散级别添加运动可行性约束来利用增量约束求解。我们的方法使用可扩展的基于逻辑的推理结合使用高效求解器（即可满足性模理论（SMT）和线性规划（LP））的优化来解决STMP规范问题中的ITMP问题。因此，我们的方法有可能扩展以处理高维连续动力学。证明了所提出的设计算法的正确性和完整性，并给出了数值结果来说明设计算法的有效性。

##### URL
[http://arxiv.org/abs/1803.11247](http://arxiv.org/abs/1803.11247)

##### PDF
[http://arxiv.org/pdf/1803.11247](http://arxiv.org/pdf/1803.11247)

