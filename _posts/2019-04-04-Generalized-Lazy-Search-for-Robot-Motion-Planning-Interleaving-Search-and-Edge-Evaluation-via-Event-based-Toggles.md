---
layout: post
title: "Generalized Lazy Search for Robot Motion Planning: Interleaving Search and Edge Evaluation via Event-based Toggles"
date: 2019-04-04 21:24:29
categories: arXiv_RO
tags: arXiv_RO
author: Aditya Mandalika, Sanjiban Choudhury, Oren Salzman, Siddhartha Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
Lazy search algorithms can efficiently solve problems where edge evaluation is the bottleneck in computation, as is the case for robotic motion planning. The optimal algorithm in this class, LazySP, lazily restricts edge evaluation to only the shortest path. Doing so comes at the expense of search effort, i.e., LazySP must recompute the search tree every time an edge is found to be invalid. This becomes prohibitively expensive when dealing with large graphs or highly cluttered environments. Our key insight is the need to balance both edge evaluation and search effort to minimize the total planning time. Our contribution is two-fold. First, we propose a framework, Generalized Lazy Search (GLS), that seamlessly toggles between search and evaluation to prevent wasted efforts. We show that for a choice of toggle, GLS is provably more efficient than LazySP. Second, we leverage prior experience of edge probabilities to derive GLS policies that minimize expected planning time. We show that GLS equipped with such priors significantly outperforms competitive baselines for many simulated environments in R2, SE(2) and 7-DoF manipulation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02795](http://arxiv.org/abs/1904.02795)

##### PDF
[http://arxiv.org/pdf/1904.02795](http://arxiv.org/pdf/1904.02795)

