---
layout: post
title: "Trajectory Optimization for Curvature Bounded Non-Holonomic Vehicles: Application to Autonomous Driving"
date: 2017-12-13 19:51:50
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Mithun Babu, Yash Oza, C. A. Balaji, Arun Kumar Singh, Bharath Gopakarishnan, K. Madhava Kirshna
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a trajectory optimization for computing smooth collision free trajectories for nonholonomic curvature bounded vehicles among static and dynamic obstacles. One of the key novelties of our formulation is a hierarchal optimization routine which alternately operates in the space of angular accelerations and linear velocities. That is, the optimization has a two layer structure wherein angular accelerations are optimized keeping the linear velocities fixed and vice versa. If the vehicle/obstacles are modeled as circles than the velocity optimization layer can be shown to have the computationally efficient difference of convex structure commonly observed for linear systems. This leads to a less conservative approximation as compared to that obtained by approximating each polygon individually through its circumscribing circle. On the other hand, it leads to optimization problem with less number of constraints as compared to that obtained when approximating polygons as multiple overlapping circles. We use the proposed trajectory optimization as the basis for constructing a Model Predictive Control framework for navigating an autonomous car in complex scenarios like overtaking, lane changing and merging. Moreover, we also highlight the advantages provided by the alternating optimization routine. Specifically, we show it produces trajectories which have comparable arc lengths and smoothness as compared to those produced with joint simultaneous optimization in the space of angular accelerations and linear velocities. However, importantly, the alternating optimization provides some gain in computational time.

##### Abstract (translated by Google)
在本文中，我们提出了一个轨道优化计算非完整曲率有界车辆在静态和动态障碍物之间的平滑无碰撞轨迹。我们公式的一个关键新颖之处是一个层次优化程序，它在角加速度和线速度空间交替运行。即，优化具有两层结构，其中角速度被优化，保持线速度固定，反之亦然。如果车辆/障碍物被建模为圆形，则可以示出速度优化层具有对于线性系统通常观察到的凸起结构的计算有效差异。与通过其外接圆单独逼近每个多边形所获得的近似相比，这导致较不保守的近似。另一方面，与将多边形近似为多个重叠圆所获得的约束相比，其导致约束数量较少的优化问题。我们使用所提出的轨迹优化作为构建用于在超车，车道变换和合并等复杂场景中驾驶自动驾驶汽车的模型预测控制框架的基础。此外，我们还强调了交替优化程序提供的优势。具体来说，我们表明它产生具有可比较的弧长和平滑度的轨迹，与在角加速度和线速度空间中联合同时优化产生的轨迹相比。然而，重要的是，交替优化在计算时间上提供了一些增益。

##### URL
[https://arxiv.org/abs/1712.04978](https://arxiv.org/abs/1712.04978)

##### PDF
[https://arxiv.org/pdf/1712.04978](https://arxiv.org/pdf/1712.04978)

