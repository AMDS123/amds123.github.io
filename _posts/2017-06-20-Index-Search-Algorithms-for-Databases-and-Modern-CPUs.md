---
layout: post
title: "Index Search Algorithms for Databases and Modern CPUs"
date: 2017-06-20 23:01:52
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Florian Gross
mathjax: true
---

* content
{:toc}

##### Abstract
Over the years, many different indexing techniques and search algorithms have been proposed, including CSS-trees, CSB+ trees, k-ary binary search, and fast architecture sensitive tree search. There have also been papers on how best to set the many different parameters of these index structures, such as the node size of CSB+ trees. These indices have been proposed because CPU speeds have been increasing at a dramatically higher rate than memory speeds, giving rise to the Von Neumann CPU--Memory bottleneck. To hide the long latencies caused by memory access, it has become very important to well-utilize the features of modern CPUs. In order to drive down the average number of CPU clock cycles required to execute CPU instructions, and thus increase throughput, it has become important to achieve a good utilization of CPU resources. Some of these are the data and instruction caches, and the translation lookaside buffers. But it also has become important to avoid branch misprediction penalties, and utilize vectorization provided by CPUs in the form of SIMD instructions. While the layout of index structures has been heavily optimized for the data cache of modern CPUs, the instruction cache has been neglected so far. In this paper, we present NitroGen, a framework for utilizing code generation for speeding up index traversal in main memory database systems. By bringing together data and code, we make index structures use the dormant resource of the instruction cache. We show how to combine index compilation with previous approaches, such as binary tree search, cache-sensitive tree search, and the architecture-sensitive tree search presented by Kim et al.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.06697](https://arxiv.org/abs/1706.06697)

##### PDF
[https://arxiv.org/pdf/1706.06697](https://arxiv.org/pdf/1706.06697)

