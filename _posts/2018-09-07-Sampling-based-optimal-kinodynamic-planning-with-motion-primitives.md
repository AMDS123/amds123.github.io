---
layout: post
title: "Sampling-based optimal kinodynamic planning with motion primitives"
date: 2018-09-07 10:49:02
categories: arXiv_RO
tags: arXiv_RO
author: Basak Sakcak, Luca Bascetta, Gianni Ferretti, Maria Prandini
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel sampling-based motion planner, which integrates in RRT* (Rapidly exploring Random Tree star) a database of pre-computed motion primitives to alleviate its computational load and allow for motion planning in a dynamic or partially known environment. The database is built by considering a set of initial and final state pairs in some grid space, and determining for each pair an optimal trajectory that is compatible with the system dynamics and constraints, while minimizing a cost. Nodes are progressively added to the tree {of feasible trajectories in the RRT* by extracting at random a sample in the gridded state space and selecting the best obstacle-free motion primitive in the database that joins it to an existing node. The tree is rewired if some nodes can be reached from the new sampled state through an obstacle-free motion primitive with lower cost. The computationally more intensive part of motion planning is thus moved to the preliminary offline phase of the database construction at the price of some performance degradation due to gridding. Grid resolution can be tuned so as to compromise between (sub)optimality and size of the database. The planner is shown to be asymptotically optimal as the grid resolution goes to zero and the number of sampled states grows to infinity.

##### Abstract (translated by Google)
本文提出了一种新颖的基于采样的运动规划器，它集成了RRT *（快速探索随机树星）预先计算的运动图元数据库，以减轻其计算负荷，并允许在动态或部分已知的环境中进行运动规划。通过在一些网格空间中考虑一组初始和最终状态对来构建数据库，并且为每对确定与系统动态和约束兼容的最佳轨迹，同时最小化成本。通过随机提取网格状态空间中的样本并在数据库中选择将其连接到现有节点的最佳无障碍运动原语，将节点逐渐添加到RRT *中的可行轨迹的树中。如果可以通过具有较低成本的无障碍运动原语从新采样状态到达某些节点，则重新连接树。因此，运动计划的计算上更密集的部分被转移到数据库构造的初步离线阶段，其代价是由于网格化导致的一些性能下降。可以调整网格分辨率，以便在（子）最优性和数据库大小之间进行折衷。当网格分辨率变为零并且采样状态的数量增长到无穷大时，规划器被证明是渐近最优的。

##### URL
[https://arxiv.org/abs/1809.02399](https://arxiv.org/abs/1809.02399)

##### PDF
[https://arxiv.org/pdf/1809.02399](https://arxiv.org/pdf/1809.02399)

