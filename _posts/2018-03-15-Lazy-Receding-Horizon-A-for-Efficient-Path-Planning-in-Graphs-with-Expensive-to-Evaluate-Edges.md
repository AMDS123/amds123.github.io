---
layout: post
title: "Lazy Receding Horizon A* for Efficient Path Planning in Graphs with Expensive-to-Evaluate Edges"
date: 2018-03-15 10:41:02
categories: arXiv_RO
tags: arXiv_RO
author: Aditya Mandalika, Oren Salzman, Siddhartha Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
Motion-planning problems, such as manipulation in cluttered environments, often require a collision-free shortest path to be computed quickly given a roadmap graph. Typically, the computational cost of evaluating whether an edge of the roadmap graph is collision-free dominates the running time of search algorithms. Algorithms such as Lazy Weighted A* (LWA*) and LazySP have been proposed to reduce the number of edge evaluations by employing a lazy lookahead (one-step lookahead and infinite-step lookahead, respectively). However, this comes at the expense of additional graph operations: the larger the lookahead, the more the graph operations that are typically required. We propose Lazy Receding-Horizon A* (LRA*) to minimize the total planning time by balancing edge evaluations and graph operations. Endowed with a lazy lookahead, LRA* represents a family of lazy shortest-path graph-search algorithms that generalizes LWA* and LazySP. We analyze the theoretic properties of LRA* and demonstrate empirically that, in many cases, to minimize the total planning time, the algorithm requires an intermediate lazy lookahead. Namely, using an intermediate lazy lookahead, our algorithm outperforms both LWA* and LazySP. These experiments span simulated random worlds in $\mathbb{R}^2$ and $\mathbb{R}^4$, and manipulation problems using a 7-DOF manipulator.

##### Abstract (translated by Google)
运动规划问题（如混乱环境中的操纵）通常需要在给定路线图的情况下快速计算无碰撞最短路径。通常，评估路标图的边缘是否是无碰撞的计算成本支配搜索算法的运行时间。已经提出了诸如Lazy Weighted A *（LWA *）和LazySP之类的算法，以通过采用懒惰预测（分别为一步预测和无限步骤预测）来减少边缘评估的数量。但是，这是以牺牲额外的图表操作为代价的：预览越大，通常需要的图表操作越多。我们提出Lazy Receding-Horizo​​n A *（LRA *），通过平衡边缘评估和图表操作来最小化总计划时间。 LRA *具有懒惰的前瞻性，代表了LWA *和LazySP的延迟最短路径图搜索算法。我们分析了LRA *的理论特性，并且经验地证明，在很多情况下，为了最小化总计划时间，算法需要一个中间懒惰的预测。也就是说，我们的算法使用中间的懒惰lookahead，优于LWA *和LazySP。这些实验在$ \ mathbb {R} ^ 2 $和$ \ mathbb {R} ^ 4 $中模拟随机世界，并使用7自由度机械手操纵问题。

##### URL
[https://arxiv.org/abs/1803.04998](https://arxiv.org/abs/1803.04998)

##### PDF
[https://arxiv.org/pdf/1803.04998](https://arxiv.org/pdf/1803.04998)

