---
layout: post
title: "NanoMap: Fast, Uncertainty-Aware Proximity Queries with Lazy Search over Local 3D Data"
date: 2018-02-25 20:46:15
categories: arXiv_RO
tags: arXiv_RO
author: Peter R. Florence, John Carter, Jake Ware, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
We would like robots to be able to safely navigate at high speed, efficiently use local 3D information, and robustly plan motions that consider pose uncertainty of measurements in a local map structure. This is hard to do with previously existing mapping approaches, like occupancy grids, that are focused on incrementally fusing 3D data into a common world frame. In particular, both their fragile sensitivity to state estimation errors and computational cost can be limiting. We develop an alternative framework, NanoMap, which alleviates the need for global map fusion and enables a motion planner to efficiently query pose-uncertainty-aware local 3D geometric information. The key idea of NanoMap is to store a history of noisy relative pose transforms and search over a corresponding set of depth sensor measurements for the minimum-uncertainty view of a queried point in space. This approach affords a variety of capabilities not offered by traditional mapping techniques: (a) the pose uncertainty associated with 3D data can be incorporated in motion planning, (b) poses can be updated (i.e., from loop closures) with minimal computational effort, and (c) 3D data can be fused lazily for the purpose of planning. We provide an open-source implementation of NanoMap, and analyze its capabilities and computational efficiency in simulation experiments. Finally, we demonstrate in hardware its effectiveness for fast 3D obstacle avoidance onboard a quadrotor flying up to 10 m/s.

##### Abstract (translated by Google)
我们希望机器人能够高速安全地导航，高效地使用局部3D信息，并且强大地计划考虑本地地图结构中测量的姿态不确定性的运动。这很难做到以前存在的映射方法，比如占用网格，这些方法专注于将3D数据逐步融合到一个通用的世界框架中。特别是，它们对状态估计误差和计算成本的脆弱敏感性都可能受到限制。我们开发了一种替代框架NanoMap，该框架减轻了对全球地图融合的需求，并使运动规划人员能够高效地查询姿态不确定感知的局部3D几何信息。 NanoMap的核心思想是存储噪声相对姿态变换的历史记录，并在相应的一组深度传感器测量值上搜索空间查询点的最小不确定性视图。这种方法提供了传统绘图技术所不具备的各种功能：（a）与3D数据相关的姿态不确定性可以包含在运动计划中，（b）姿势可以用最少的计算量更新（即从闭环闭合）和（c）为了规划的目的，3D数据可以被懒散地融合。我们提供了NanoMap的开源实现，并分析了它在仿真实验中的功能和计算效率。最后，我们在硬件上展示了它可以在飞行速度高达10米/秒的四旋翼飞行器上实现快速3D避障。

##### URL
[http://arxiv.org/abs/1802.09076](http://arxiv.org/abs/1802.09076)

##### PDF
[http://arxiv.org/pdf/1802.09076](http://arxiv.org/pdf/1802.09076)

