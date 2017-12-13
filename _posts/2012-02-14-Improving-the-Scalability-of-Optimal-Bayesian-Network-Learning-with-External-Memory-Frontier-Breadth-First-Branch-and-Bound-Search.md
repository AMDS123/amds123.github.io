---
layout: post
title: "Improving the Scalability of Optimal Bayesian Network Learning with External-Memory Frontier Breadth-First Branch and Bound Search"
date: 2012-02-14 16:41:17
categories: arXiv_CV
tags: arXiv_CV
author: Brandon Malone, Changhe Yuan, Eric A. Hansen, Susan Bridges
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work has shown that the problem of learning the optimal structure of a Bayesian network can be formulated as a shortest path finding problem in a graph and solved using A* search. In this paper, we improve the scalability of this approach by developing a memory-efficient heuristic search algorithm for learning the structure of a Bayesian network. Instead of using A*, we propose a frontier breadth-first branch and bound search that leverages the layered structure of the search graph of this problem so that no more than two layers of the graph, plus solution reconstruction information, need to be stored in memory at a time. To further improve scalability, the algorithm stores most of the graph in external memory, such as hard disk, when it does not fit in RAM. Experimental results show that the resulting algorithm solves significantly larger problems than the current state of the art.

##### Abstract (translated by Google)
以前的研究表明，学习贝叶斯网络最优结构的问题可以用图表中的最短路径查找问题来描述，并用A *搜索来解决。在本文中，我们通过开发用于学习贝叶斯网络结构的高效的启发式搜索算法来改进这种方法的可扩展性。我们不使用A *，而是提出了一个边界宽度优先的分支和边界搜索，它利用了这个问题的搜索图的分层结构，以便不超过两层的图和解重构信息需要存储在内存一次。为了进一步提高可伸缩性，算法将大部分图形存储在外部存储器（如硬盘）中，而不适合RAM。实验结果表明，所得到的算法解决了比现有技术更大的问题。

##### URL
[https://arxiv.org/abs/1202.3744](https://arxiv.org/abs/1202.3744)

##### PDF
[https://arxiv.org/pdf/1202.3744](https://arxiv.org/pdf/1202.3744)

