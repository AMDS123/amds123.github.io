---
layout: post
title: "Finding Optimal Solutions to Token Swapping by Conflict-based Search and Reduction to SAT"
date: 2018-06-25 14:28:09
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Pavel Surynek
mathjax: true
---

* content
{:toc}

##### Abstract
We study practical approaches to solving the token swapping (TSWAP) problem optimally in this short paper. In TSWAP, we are given an undirected graph with colored vertices. A colored token is placed in each vertex. A pair of tokens can be swapped between adjacent vertices. The goal is to perform a sequence of swaps so that token and vertex colors agree across the graph. The minimum number of swaps is required in the optimization variant of the problem. We observed similarities between the TSWAP problem and multi-agent path finding (MAPF) where instead of tokens we have multiple agents that need to be moved from their current vertices to given unique target vertices. The difference between both problems consists in local conditions that state transitions (swaps/moves) must satisfy. We developed two algorithms for solving TSWAP optimally by adapting two different approaches to MAPF - CBS and MDD- SAT. This constitutes the first attempt to design optimal solving algorithms for TSWAP. Experimental evaluation on various types of graphs shows that the reduction to SAT scales better than CBS in optimal TSWAP solving.

##### Abstract (translated by Google)
我们研究了在这篇短文中最优化解决令牌交换（TSWAP）问题的实用方法。在TSWAP中，我们给出了一个带有彩色顶点的无向图。一个彩色的标记被放置在每个顶点。一对标记可以在相邻顶点之间交换。目标是执行一系列交换，以便令牌和顶点颜色在整个图上保持一致。问题的优化变体需要交换的最小数量。我们观察到TSWAP问题和多智能体路径寻找（MAPF）之间的相似性，其中代替令牌，我们有多个智能体需要从其当前顶点移动到给定的唯一目标顶点。两个问题之间的区别在于状态转换（交换/移动）必须满足的地方条件。我们通过适应两种不同的MAPF-CBS和MDD-SAT方法，开发了两种算法来优化求解TSWAP。这构成了为TSWAP设计最佳求解算法的第一次尝试。各种类型图的实验评估表明，在最佳TSWAP求解中，SAT的缩减比CBS的缩小更好。

##### URL
[http://arxiv.org/abs/1806.09487](http://arxiv.org/abs/1806.09487)

##### PDF
[http://arxiv.org/pdf/1806.09487](http://arxiv.org/pdf/1806.09487)

