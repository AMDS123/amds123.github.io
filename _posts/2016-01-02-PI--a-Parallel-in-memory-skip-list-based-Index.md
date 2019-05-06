---
layout: post
title: "PI : a Parallel in-memory skip list based Index"
date: 2016-01-02 10:11:57
categories: arXiv_CV
tags: arXiv_CV
author: Zhongle Xie, Qingchao Cai, H.V. Jagadish, Beng Chin Ooi, Weng-Fai Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the coarse granularity of data accesses and the heavy use of latches, indices in the B-tree family are not efficient for in-memory databases, especially in the context of today's multi-core architecture. In this paper, we present PI, a Parallel in-memory skip list based Index that lends itself naturally to the parallel and concurrent environment, particularly with non-uniform memory access. In PI, incoming queries are collected, and disjointly distributed among multiple threads for processing to avoid the use of latches. For each query, PI traverses the index in a Breadth-First-Search (BFS) manner to find the list node with the matching key, exploiting SIMD processing to speed up the search process. In order for query processing to be latch-free, PI employs a light-weight communication protocol that enables threads to re-distribute the query workload among themselves such that each list node that will be modified as a result of query processing will be accessed by exactly one thread. We conducted extensive experiments, and the results show that PI can be up to three times as fast as the Masstree, a state-of-the-art B-tree based index.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1601.00159](https://arxiv.org/abs/1601.00159)

##### PDF
[https://arxiv.org/pdf/1601.00159](https://arxiv.org/pdf/1601.00159)

