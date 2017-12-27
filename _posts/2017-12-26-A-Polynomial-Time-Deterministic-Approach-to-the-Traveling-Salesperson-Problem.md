---
layout: post
title: "A Polynomial-Time Deterministic Approach to the Traveling Salesperson Problem"
date: 2017-12-26 03:46:44
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Ali Jazayeri, Hiroki Sayama
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new polynomial-time deterministic algorithm that produces an approximated solution for the traveling salesperson problem. The proposed algorithm ranks cities based on their priorities calculated using a power function of means and standard deviations of their distances from other cities and then connects the cities to their neighbors in the order of their priorities. When connecting a city, a neighbor is selected based on their neighbors' priorities calculated as another power function that additionally includes their distance from the focal city to be connected. This repeats until all the cities are connected into a single loop. The time complexity of the proposed algorithm is $O(n^2)$, where $n$ is the number of cities. Numerical evaluation shows that, despite its simplicity, the proposed algorithm produces shorter tours with less time complexity than other conventional tour construction heuristics. The proposed algorithm can be used by itself or as an initial tour generator for other more complex heuristic optimization algorithms.

##### Abstract (translated by Google)
我们提出了一个新的多项式时间确定性算法，为旅行商问题产生一个近似解。该算法根据城市的优先次序对城市进行排序，使用均值的幂函数和与其他城市距离的标准差进行计算，然后按优先次序将城市与邻居相连。当连接一个城市时，根据邻居的优先级来计算邻居的优先级，作为另一个幂函数，另外还包括它们与要连接的焦点城市的距离。这一直重复，直到所有的城市连接成一个单一的循环。该算法的时间复杂度为$ O（n ^ 2）$，其中$ n $为城市数量。数值计算表明，尽管简单，但与其他传统的旅游建设启发式算法相比，所提出的算法能够以更短的时间生成更短的旅程。所提出的算法可以单独使用或作为其他更复杂的启发式优化算法的初始游览生成器使用。

##### URL
[http://arxiv.org/abs/1608.01716](http://arxiv.org/abs/1608.01716)

##### PDF
[http://arxiv.org/pdf/1608.01716](http://arxiv.org/pdf/1608.01716)

