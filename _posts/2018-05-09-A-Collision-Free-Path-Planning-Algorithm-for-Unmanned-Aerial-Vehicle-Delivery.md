---
layout: post
title: "A Collision-Free Path Planning Algorithm for Unmanned Aerial Vehicle Delivery"
date: 2018-05-09 03:07:14
categories: arXiv_RO
tags: arXiv_RO
author: Ziji Shi, Wee Keong Ng
mathjax: true
---

* content
{:toc}

##### Abstract
Path planning is important for the autonomy of Unmanned Aerial Vehicle (UAV), especially for scheduling UAV delivery. However, the operating environment of UAVs is usually uncertain and dynamic. Without proper planning, collisions may happen where multiple UAVs are congested. Besides, there may also be temporary no-fly zone setup by authorities that makes airspace unusable. Thus, proper pre-departure planning that avoids such places is needed. 
 In this paper, we formulate this problem into a Constraint Satisfaction Problem to find a collision-free shortest path on a dynamic graph. We propose a collision-free path planning algorithm that is based on A* algorithm. The main novelty is that we invent a heuristic function that also considers waiting time. We later show that, with added waiting penalty, the proposed algorithm is optimal because the heuristic is admissible. Implementation of this algorithm simulates UAV delivery using Singapore's airspace structure. Our simulation exhibits desirable runtime performance. Using the proposed algorithm, the percentage of collision-free routes decreases as number of requests per unit area increases, and this percentage drops significantly at boundary value. Our empirical analysis could aid the decision-making of no-fly zone policy and infrastructure of UAV delivery.

##### Abstract (translated by Google)
路径规划对于无人机的自主性非常重要，特别是对无人机的调度。然而，无人机的运行环境通常是不确定和动态的。如果没有适当的计划，多个无人机拥塞时可能会发生碰撞。此外，当局也可能设置临时禁飞区，使空域无法使用。因此，需要适当的出发前规划来避免这些地方。
 在本文中，我们将此问题制定为约束满足问题，以在动态图上找到无碰撞的最短路径。我们提出一种基于A *算法的无碰撞路径规划算法。主要的新颖之处在于我们发明了一个也考虑等待时间的启发式功能。我们后来表明，由于加入等待惩罚，所提出的算法是最优的，因为启发式是可允许的。该算法的实施模拟了使用新加坡空域结构的无人机交付。我们的仿真展现了理想的运行时性能使用所提出的算法，无碰撞路线的百分比随着每单位面积的请求数量的增加而减少，并且这个百分比在边界值处显着下降。我们的实证分析有助于决策制定无人机区域政策和无人机交付基础设施。

##### URL
[http://arxiv.org/abs/1805.03358](http://arxiv.org/abs/1805.03358)

##### PDF
[http://arxiv.org/pdf/1805.03358](http://arxiv.org/pdf/1805.03358)

