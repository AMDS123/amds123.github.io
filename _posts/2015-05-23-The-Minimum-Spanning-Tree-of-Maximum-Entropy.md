---
layout: post
title: "The Minimum Spanning Tree of Maximum Entropy"
date: 2015-05-23 12:49:30
categories: arXiv_CV
tags: arXiv_CV
author: Samuel de Sousa, Walter G. Kropatsch
mathjax: true
---

* content
{:toc}

##### Abstract
In computer vision, we have the problem of creating graphs out of unstructured point-sets, i.e. the data graph. A common approach for this problem consists of building a triangulation which might not always lead to the best solution. Small changes in the location of the points might generate graphs with unstable configurations and the topology of the graph could change significantly. After building the data-graph, one could apply Graph Matching techniques to register the original point-sets. In this paper, we propose a data graph technique based on the Minimum Spanning Tree of Maximum Entropty (MSTME). We aim at a data graph construction which could be more stable than the Delaunay triangulation with respect to small variations in the neighborhood of points. Our technique aims at creating data graphs which could help the point-set registration process. We propose an algorithm with a single free parameter that weighs the importance between the total weight cost and the entropy of the current spanning tree. We compare our algorithm on a number of different databases with the Delaunay triangulation.

##### Abstract (translated by Google)
在计算机视觉中，我们有从非结构化点集（即数据图）创建图的问题。这个问题的一个常见的方法是建立一个三角形，这可能并不总是导致最好的解决方案。点位置的小变化可能会生成具有不稳定配置的图形，并且图形的拓扑结构可能会发生显着变化。在构建数据图之后，可以应用图匹配技术来注册原始点集。在本文中，我们提出了一个基于最大生成树最小生成树（MSTME）的数据图技术。我们的目标是建立一个比Delaunay三角剖分更稳定的数据图结构，这些数据图对于点附近的小变化是比较稳定的。我们的技术旨在创建可帮助点集注册过程的数据图。我们提出一个单一的自由参数的算法，权衡总权重成本和当前生成树的熵之间的重要性。我们用Delaunay三角剖分将我们的算法与许多不同的数据库进行比较。

##### URL
[https://arxiv.org/abs/1505.06319](https://arxiv.org/abs/1505.06319)

##### PDF
[https://arxiv.org/pdf/1505.06319](https://arxiv.org/pdf/1505.06319)

