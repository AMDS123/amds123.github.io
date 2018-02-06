---
layout: post
title: "Path Planning for Minimizing the Expected Cost till Success"
date: 2018-02-03 02:54:06
categories: arXiv_RO
tags: arXiv_RO
author: Arjun Muralidharan, Yasamin Mostofi
mathjax: true
---

* content
{:toc}

##### Abstract
Consider a general path planning problem of a robot on a graph with edge costs, and where each node has a Boolean value of success or failure (with respect to some task) with a given probability. The objective is to plan a path for the robot on the graph that minimizes the expected cost till success. In this paper, it is our goal to bring a foundational understanding to this problem. We start by showing how this problem can be optimally solved by formulating it as an infinite horizon Markov Decision Process, but with an exponential space complexity. We then formally prove its NP-hardness. To address the space complexity, we then propose a path planner, using a game-theoretic framework, that asymptotically gets arbitrarily close to the optimal solution. Moreover, we also propose two fast and non-myopic path planners. To show the performance of our framework, we do extensive simulations for two scenarios: a rover on Mars searching for an object for scientific studies, and a robot looking for a connected spot to a remote station (with real data from downtown San Francisco). Our numerical results show a considerable performance improvement over existing state-of-the-art approaches.

##### Abstract (translated by Google)
考虑一个具有边缘代价的图上机器人的一般路径规划问题，并且每个节点具有给定概率的成功或失败的布尔值（相对于某个任务）。目标是在图表上规划一个机器人的路径，使成本最小化。在本文中，我们的目标是为这个问题带来一个基本的理解。我们首先通过展示如何将这个问题表达为一个无限的时间马尔可夫决策过程来解决这个问题，但是却具有指数空间的复杂性。然后我们正式证明了它的NP-硬度。为了解决空间复杂性问题，我们提出了一个使用博弈论框架的路径规划器，它渐近地接近最优解。此外，我们还提出了两个快速和非近视的路径规划。为了展示我们框架的性能，我们对两种情况进行了大量的仿真：火星探测器搜索科学研究对象，机器人寻找远程站点的连接点（从旧金山市中心获取真实数据）。我们的数值结果显示，与现有的最先进的方法相比，性能有显着的提高。

##### URL
[http://arxiv.org/abs/1802.00898](http://arxiv.org/abs/1802.00898)

##### PDF
[http://arxiv.org/pdf/1802.00898](http://arxiv.org/pdf/1802.00898)

