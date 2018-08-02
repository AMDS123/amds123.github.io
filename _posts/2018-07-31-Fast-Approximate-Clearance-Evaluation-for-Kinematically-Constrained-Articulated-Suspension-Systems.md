---
layout: post
title: "Fast Approximate Clearance Evaluation for Kinematically Constrained Articulated Suspension Systems"
date: 2018-07-31 19:09:57
categories: arXiv_RO
tags: arXiv_RO Optimization Detection
author: Kyohei Otsu, Guillaume Matheron, Sourish Ghosh, Olivier Toupet, Masahiro Ono
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a light-weight collision detection algorithm for motion planning of planetary rovers with articulated suspension systems. Extraterrestrial path planning is challenging due to the combination of terrain roughness and severe limitation in computational resources. Path planning on cluttered and/or uneven terrains requires repeated collision detection on all the candidate paths at a small interval. Solving the exact collision detection problem for articulated suspension systems requires simulating the vehicle settling on the terrain, which involves an inverse-kinematics problem with iterative nonlinear optimization under geometric constraints. However, such expensive computation is intractable for slow spacecraft computers, such as the RAD750 that is used by the Curiosity Mars rover and upcoming Mars 2020 rover. We propose the Approximate Clearance Evaluation (ACE) algorithm, which obtains conservative bounds on vehicle clearance, attitude, and suspension angles without iterative computation. It obtains those bounds by estimating the lowest and highest heights that each wheel may reach given the underlying terrain, and calculating the worst-case vehicle configuration associated with those extreme wheel heights. The bounds are guaranteed to be conservative, hence ensuring vehicle safety during autonomous navigation. ACE is planned to be used as part of the new onboard path planner of the Mars 2020 rover. This paper describes the algorithm in detail and validates our claim of conservatism and fast computation through experiments.

##### Abstract (translated by Google)
在本文中，我们提出了一种轻型碰撞检测算法，用于具有铰接悬架系统的行星车的运动规划。由于地形粗糙度和计算资源的严重限制相结合，外星路径规划具有挑战性。杂乱和/或不平坦地形上的路径规划需要以小间隔对所有候选路径进行重复碰撞检测。解决关节悬架系统的精确碰撞检测问题需要模拟车辆在地形上的稳定，这涉及在几何约束下的迭代非线性优化的逆运动学问题。然而，这种昂贵的计算对于慢速航天器计算机来说是难以处理的，例如好奇号火星探测器和即将到来的火星2020探测器使用的RAD750。我们提出了近似间隙评估（ACE）算法，该算法在没有迭代计算的情况下获得车辆间隙，姿态和悬架角度的保守界限。它通过估计每个车轮在给定潜在地形时可能达到的最高和最高高度，并计算与这些极端车轮高度相关的最坏情况车辆配置来获得这些界限。保证边界是保守的，因此在自主导航期间确保车辆安全。 ACE计划用作Mars 2020流动站的新机载路径规划器的一部分。本文详细描述了该算法，并通过实验验证了我们对保守主义和快速计算的主张。

##### URL
[https://arxiv.org/abs/1808.00031](https://arxiv.org/abs/1808.00031)

##### PDF
[https://arxiv.org/pdf/1808.00031](https://arxiv.org/pdf/1808.00031)

