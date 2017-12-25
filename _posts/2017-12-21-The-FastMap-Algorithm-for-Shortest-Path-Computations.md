---
layout: post
title: "The FastMap Algorithm for Shortest Path Computations"
date: 2017-12-21 19:57:53
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Liron Cohen, Tansel Uras, Shiva Jahangiri, Aliyah Arunasalam, Sven Koenig, T.K. Satish Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new preprocessing algorithm for embedding the nodes of a given edge-weighted undirected graph into a Euclidean space. The Euclidean distance between any two nodes in this space approximates the length of the shortest path between them in the given graph. Later, at runtime, a shortest path between any two nodes can be computed with A* search using the Euclidean distances as heuristic. Our preprocessing algorithm, called FastMap, is inspired by the data mining algorithm of the same name and runs in near-linear time. Hence, FastMap is orders of magnitude faster than competing approaches that produce a Euclidean embedding using Semidefinite Programming. FastMap also produces admissible and consistent heuristics and therefore guarantees the generation of shortest paths. Moreover, FastMap applies to general undirected graphs for which many traditional heuristics, such as the Manhattan Distance heuristic, are not well defined. Empirically, we demonstrate that A* search using the FastMap heuristic is competitive with A* search using other state-of-the-art heuristics, such as the Differential heuristic.

##### Abstract (translated by Google)
我们提出了一个新的预处理算法，将给定的边缘加权无向图的节点嵌入到欧几里得空间中。该空间中任意两个节点之间的欧几里得距离近似于给定图中它们之间的最短路径的长度。稍后，在运行时，任何两个节点之间的最短路径可以通过使用欧几里得距离作为启发式的A *搜索来计算。我们的称为FastMap的预处理算法受到相同名称的数据挖掘算法的启发，并且运行在接近线性的时间。因此，FastMap比使用半定规划产生欧几里德嵌入的竞争方法快几个数量级。 FastMap也能产生可接受的一致的启发式，因此保证了最短路径的生成。此外，FastMap适用于许多传统启发式（如曼哈顿距离启发式）没有明确定义的普通无向图。实证上，我们证明了使用FastMap启发式的A *搜索与使用其他最先进的启发式（如差异启发式）的A *搜索相比具有竞争性。

##### URL
[http://arxiv.org/abs/1706.02792](http://arxiv.org/abs/1706.02792)

##### PDF
[http://arxiv.org/pdf/1706.02792](http://arxiv.org/pdf/1706.02792)

