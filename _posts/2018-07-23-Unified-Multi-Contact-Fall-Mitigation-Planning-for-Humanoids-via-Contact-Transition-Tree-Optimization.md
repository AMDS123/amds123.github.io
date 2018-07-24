---
layout: post
title: "Unified Multi-Contact Fall Mitigation Planning for Humanoids via Contact Transition Tree Optimization"
date: 2018-07-23 15:15:53
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Shihao Wang, Kris Hauser
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a multi-contact approach to generalized humanoid fall mitigation planning that unifies inertial shaping, protective stepping, and hand contact strategies. The planner optimizes both the contact sequence and the robot state trajectories. A high-level tree search is conducted to iteratively grow a contact transition tree. At each edge of the tree, trajectory optimization is used to calculate robot stabilization trajectories that produce the desired contact transition while minimizing kinetic energy. Also, at each node of the tree, the optimizer attempts to find a self-motion (inertial shaping movement) to eliminate kinetic energy. This paper also presents an efficient and effective method to generate initial seeds to facilitate trajectory optimization. Experiments demonstrate show that our proposed algorithm can generate complex stabilization strategies for a simulated robot under varying initial pushes and environment shapes.

##### Abstract (translated by Google)
本文介绍了一种多接触方法，用于广义人形防坠落规划，统一惯性塑形，保护性踩踏和手接触策略。规划器优化了接触顺序和机器人状态轨迹。进行高级树搜索以迭代地生长接触过渡树。在树的每个边缘处，轨迹优化用于计算机器人稳定轨迹，其产生期望的接触过渡同时使动能最小化。此外，在树的每个节点处，优化器试图找到自运动（惯性整形运动）以消除动能。本文还提出了一种有效且有效的方法来生成初始种子以促进轨迹优化。实验证明，我们提出的算法可以在不同的初始推动和环境形状下为模拟机器人生成复杂的稳定策略。

##### URL
[http://arxiv.org/abs/1807.08667](http://arxiv.org/abs/1807.08667)

##### PDF
[http://arxiv.org/pdf/1807.08667](http://arxiv.org/pdf/1807.08667)

