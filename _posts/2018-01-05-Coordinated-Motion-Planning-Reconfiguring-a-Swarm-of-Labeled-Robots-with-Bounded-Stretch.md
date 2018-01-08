---
layout: post
title: "Coordinated Motion Planning: Reconfiguring a Swarm of Labeled Robots with Bounded Stretch"
date: 2018-01-05 10:15:31
categories: arXiv_RO
tags: arXiv_RO
author: Erik D. Demaine, S&#xe1;ndor P. Fekete, Phillip Keldenich, Henk Meijer, Christian Scheffer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a number of breakthroughs for coordinated motion planning, in which the objective is to reconfigure a swarm of labeled convex objects by a combination of parallel, continuous, collision-free translations into a given target arrangement. Problems of this type can be traced back to the classic work of Schwartz and Sharir (1983), who gave a method for deciding the existence of a coordinated motion for a set of disks between obstacles; their approach is polynomial in the complexity of the obstacles, but exponential in the number of disks. Other previous work has largely focused on {\em sequential} schedules, in which one robot moves at a time. 
 We provide constant-factor approximation algorithms for minimizing the execution time of a coordinated, {\em parallel} motion plan for a swarm of robots in the absence of obstacles, provided some amount of separability. 
 Our algorithm achieves {\em constant stretch factor}: If all robots are at most $d$ units from their respective starting positions, the total duration of the overall schedule is $O(d)$. Extensions include unlabeled robots and different classes of robots. We also prove that finding a plan with minimal execution time is NP-hard, even for a grid arrangement without any stationary obstacles. On the other hand, we show that for densely packed disks that cannot be well separated, a stretch factor $\Omega(N^{1/4})$ may be required. On the positive side, we establish a stretch factor of $O(N^{1/2})$ even in this case.

##### Abstract (translated by Google)
我们提出了协调运动规划的一些突破，其目标是通过将平行，连续，无碰撞的翻译组合成一个给定的目标排列来重新配置一组标记的凸面物体。这种类型的问题可以追溯到Schwartz和Sharir（1983）的经典着作，他们给出了一种方法来确定障碍物之间一组圆盘的协调运动的存在性;他们的方法是在复杂的障碍物的多项式中，但在磁盘的数量指数。以前的其他工作主要集中在一个机器人一次移动的时间顺序上。
 我们提供了常数因子近似算法，用于在不存在障碍物的情况下最小化机器人群的协调运动计划的执行时间，并提供一定量的可分离性。
 我们的算法实现了{\ em不变的拉伸因子}：如果所有的机器人从他们各自的起始位置起最多$ d $个单位，则整个时间表的总时间是$ O（d）$。扩展包括无标签的机器人和不同类型的机器人。我们还证明，即使对于没有任何固定障碍的网格布置，找到一个执行时间最少的计划也是NP难的。另一方面，我们表明对于不能很好地分离的密集的盘，可能需要拉伸因子$ \ Omega（N ^ {1/4}）$。从积极的方面来看，即使在这种情况下，我们也建立了一个$ O（N ^ {1/2}）$的拉伸因子。

##### URL
[http://arxiv.org/abs/1801.01689](http://arxiv.org/abs/1801.01689)

##### PDF
[http://arxiv.org/pdf/1801.01689](http://arxiv.org/pdf/1801.01689)

