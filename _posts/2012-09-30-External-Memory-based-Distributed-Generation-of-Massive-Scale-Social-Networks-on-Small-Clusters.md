---
layout: post
title: "External Memory based Distributed Generation of Massive Scale Social Networks on Small Clusters"
date: 2012-09-30 11:14:21
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Sandeep Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Small distributed systems are limited by their main memory to generate massively large graphs. Trivial extension to current graph generators to utilize external memory leads to large amount of random I/O hence do not scale with size. In this work we offer a technique to generate massive scale graphs on small cluster of compute nodes with limited main memory. We develop several distributed and external memory algorithms, primarily, shuffle, relabel, redistribute, and, compressed-sparse-row (csr) convert. The algorithms are implemented in MPI/pthread model to help parallelize the operations across multicores within each core. Using our scheme it is feasible to generate a graph of size $2^{38}$ nodes (scale 38) using only 64 compute nodes. This can be compared with the current scheme would require at least 8192 compute node, assuming 64GB of main memory. Our work has broader implications for external memory graph libraries such as STXXL and graph processing on SSD-based supercomputers such as Dash and Gordon [1][2].

##### Abstract (translated by Google)
小型分布式系统受其主内存的限制，可以生成大规模的图形。使用外部存储器的当前图形生成器的平凡扩展导致大量的随机I / O，因此不能随着大小进行缩放。在这项工作中，我们提供了一种技术，在主存储器有限的小型计算节点集群上生成大规模的图形。我们开发了几种分布式和外部存储器算法，主要是shuffle，relabel，redistribute和compression-sparse-row（csr）convert。这些算法在MPI / pthread模型中实现，以帮助并行化每个内核中多核的操作。使用我们的方案，仅使用64个计算节点来生成大小为$ 2 ^ {38} $节点（规模38）的图是可行的。这可以与目前的方案进行比较，至少需要8192个计算节点，假设64GB的主内存。我们的工作对于像Dash和Gordon这样的基于SSD的超级计算机上的外部存储器图形库（如STXXL和图形处理）具有更广泛的意义[1] [2]。

##### URL
[https://arxiv.org/abs/1210.0187](https://arxiv.org/abs/1210.0187)

##### PDF
[https://arxiv.org/pdf/1210.0187](https://arxiv.org/pdf/1210.0187)

