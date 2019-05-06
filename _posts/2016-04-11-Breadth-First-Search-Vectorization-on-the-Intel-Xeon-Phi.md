---
layout: post
title: "Breadth First Search Vectorization on the Intel Xeon Phi"
date: 2016-04-11 09:02:17
categories: arXiv_CV
tags: arXiv_CV
author: Mireya Paredes, Graham Riley, Mikel Lujan
mathjax: true
---

* content
{:toc}

##### Abstract
Breadth First Search (BFS) is a building block for graph algorithms and has recently been used for large scale analysis of information in a variety of applications including social networks, graph databases and web searching. Due to its importance, a number of different parallel programming models and architectures have been exploited to optimize the BFS. However, due to the irregular memory access patterns and the unstructured nature of the large graphs, its efficient parallelization is a challenge. The Xeon Phi is a massively parallel architecture available as an off-the-shelf accelerator, which includes a powerful 512 bit vector unit with optimized scatter and gather functions. Given its potential benefits, work related to graph traversing on this architecture is an active area of research. We present a set of experiments in which we explore architectural features of the Xeon Phi and how best to exploit them in a top-down BFS algorithm but the techniques can be applied to the current state-of-the-art hybrid, top-down plus bottom-up, algorithms. We focus on the exploitation of the vector unit by developing an improved highly vectorized OpenMP parallel algorithm, using vector intrinsics, and understanding the use of data alignment and prefetching. In addition, we investigate the impact of hyperthreading and thread affinity on performance, a topic that appears under researched in the literature. As a result, we achieve what we believe is the fastest published top-down BFS algorithm on the version of Xeon Phi used in our experiments. The vectorized BFS top-down source code presented in this paper can be available on request as free-to-use software.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1604.02844](https://arxiv.org/abs/1604.02844)

##### PDF
[https://arxiv.org/pdf/1604.02844](https://arxiv.org/pdf/1604.02844)

