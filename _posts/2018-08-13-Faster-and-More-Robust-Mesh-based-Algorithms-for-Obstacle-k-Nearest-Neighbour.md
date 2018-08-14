---
layout: post
title: "Faster and More Robust Mesh-based Algorithms for Obstacle k-Nearest Neighbour"
date: 2018-08-13 02:05:27
categories: arXiv_AI
tags: arXiv_AI
author: Shizhe Zhao, Daniel D. Harabor, David Taniar
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in the problem of finding $k$ nearest neighbours in the plane and in the presence of polygonal obstacles ($\textit{OkNN}$). Widely used algorithms for OkNN are based on incremental visibility graphs, which means they require costly and online visibility checking and have worst-case quadratic running time. Recently $\mathbf{Polyanya}$, a fast point-to-point pathfinding algorithm was proposed which avoids the disadvantages of visibility graphs by searching over an alternative data structure known as a navigation mesh. Previously, we adapted $\mathbf{Polyanya}$ to multi-target scenarios by developing two specialised heuristic functions: the $\mathbf{Interval heuristic}$ $h_v$ and the $\mathbf{Target heuristic}$ $h_t$. Though these methods outperform visibility graph algorithms by orders of magnitude in all our experiments they are not robust: $h_v$ expands many redundant nodes when the set of neighbours is small while $h_t$ performs poorly when the set of neighbours is large. In this paper, we propose new algorithms and heuristics for OkNN which perform well regardless of neighbour density.

##### Abstract (translated by Google)
我们感兴趣的是在飞机上和存在多边形障碍物的情况下找到$ k $最近邻居的问题（$ \ textit {OkNN} $）。广泛使用的OkNN算法基于增量可见性图表，这意味着它们需要昂贵的在线可见性检查，并且具有最坏情况的二次运行时间。最近，$ \ mathbf {Polyanya} $是一种快速的点对点寻路算法，它通过搜索称为导航网格的替代数据结构来避免可见性图的缺点。之前，我们通过开发两个专门的启发式函数将$ \ mathbf {Polyanya} $改编为多目标场景：$ \ mathbf {Interval heuristic} $ $ h_v $和$ \ mathbf {Target heuristic} $ $ h_t $。虽然这些方法在我们所有的实验中都超过了可见性图算法的数量级但它们并不健壮：$ h_v $在邻居集很小的情况下扩展了许多冗余节点而在邻居集很大时$ h_t $表现不佳。在本文中，我们为OkNN提出了新的算法和启发式算法，无论邻居密度如何，它都表现良好。

##### URL
[http://arxiv.org/abs/1808.04043](http://arxiv.org/abs/1808.04043)

##### PDF
[http://arxiv.org/pdf/1808.04043](http://arxiv.org/pdf/1808.04043)

