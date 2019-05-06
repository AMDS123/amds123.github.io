---
layout: post
title: "GLB: Lifeline-based Global Load Balancing library in X10"
date: 2013-12-19 18:46:00
categories: arXiv_CV
tags: arXiv_CV Face
author: Wei Zhang, Olivier Tardieu, David Grove, Benjamin Herta, Tomio Kamada, Vijay Saraswat, Mikio Takeuchi
mathjax: true
---

* content
{:toc}

##### Abstract
We present GLB, a programming model and an associated implementation that can handle a wide range of irregular paral- lel programming problems running over large-scale distributed systems. GLB is applicable both to problems that are easily load-balanced via static scheduling and to problems that are hard to statically load balance. GLB hides the intricate syn- chronizations (e.g., inter-node communication, initialization and startup, load balancing, termination and result collection) from the users. GLB internally uses a version of the lifeline graph based work-stealing algorithm proposed by Saraswat et al. Users of GLB are simply required to write several pieces of sequential code that comply with the GLB interface. GLB then schedules and orchestrates the parallel execution of the code correctly and efficiently at scale. We have applied GLB to two representative benchmarks: Betweenness Centrality (BC) and Unbalanced Tree Search (UTS). Among them, BC can be statically load-balanced whereas UTS cannot. In either case, GLB scales well-- achieving nearly linear speedup on different computer architectures (Power, Blue Gene/Q, and K) -- up to 16K cores.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1312.5691](https://arxiv.org/abs/1312.5691)

##### PDF
[https://arxiv.org/pdf/1312.5691](https://arxiv.org/pdf/1312.5691)

