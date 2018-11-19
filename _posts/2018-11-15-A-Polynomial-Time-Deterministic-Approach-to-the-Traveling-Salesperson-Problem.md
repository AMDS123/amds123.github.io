---
layout: post
title: "A Polynomial-Time Deterministic Approach to the Traveling Salesperson Problem"
date: 2018-11-15 22:42:16
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


##### URL
[http://arxiv.org/abs/1608.01716](http://arxiv.org/abs/1608.01716)

##### PDF
[http://arxiv.org/pdf/1608.01716](http://arxiv.org/pdf/1608.01716)

