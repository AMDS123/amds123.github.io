---
layout: post
title: "Flexible Support for Fast Parallel Commutative Updates"
date: 2017-09-26 15:29:57
categories: arXiv_CV
tags: arXiv_CV
author: Vignesh Balaji, Dhruva Tirumala, Brandon Lucia
mathjax: true
---

* content
{:toc}

##### Abstract
Privatizing data is a useful strategy for increasing parallelism in a shared memory multithreaded program. Independent cores can compute independently on duplicates of shared data, combining their results at the end of their computations. Conventional approaches to privatization, however, rely on explicit static or dynamic memory allocation for duplicated state, increasing memory footprint and contention for cache resources, especially in shared caches. In this work, we describe CCache, a system for on-demand privatization of data manipulated by commutative operations. CCache garners the benefits of privatization, without the increase in memory footprint or cache occupancy. Each core in CCache dynamically privatizes commutatively manipulated data, operating on a copy. Periodically or at the end of its computation, the core merges its value with the value resident in memory, and when all cores have merged, the in-memory copy contains the up-to-date value. We describe a low-complexity architectural implementation of CCache that extends a conventional multicore to support on-demand privatization without using additional memory for private copies. We evaluate CCache on several high-value applications, including random access key-value store, clustering, breadth first search and graph ranking, showing speedups upto 3.2X.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.09491](https://arxiv.org/abs/1709.09491)

##### PDF
[https://arxiv.org/pdf/1709.09491](https://arxiv.org/pdf/1709.09491)

