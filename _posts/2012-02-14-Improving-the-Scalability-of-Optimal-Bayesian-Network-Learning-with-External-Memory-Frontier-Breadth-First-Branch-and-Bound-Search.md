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


##### URL
[https://arxiv.org/abs/1202.3744](https://arxiv.org/abs/1202.3744)

##### PDF
[https://arxiv.org/pdf/1202.3744](https://arxiv.org/pdf/1202.3744)

