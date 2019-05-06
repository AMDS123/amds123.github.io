---
layout: post
title: "Programming Strategies for Irregular Algorithms on the Emu Chick"
date: 2018-12-03 16:02:51
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Eric Hein, Srinivas Eswar, Abdurrahman Yaşar, Jiajia Li, Jeffrey S. Young, Thomas M. Conte, Ümit V. Çatalyürek, Rich Vuduc, Jason Riedy, Bora Uçar
mathjax: true
---

* content
{:toc}

##### Abstract
The Emu Chick prototype implements migratory memory-side processing in a novel hardware system. Rather than transferring large amounts of data across the system interconnect, the Emu Chick moves lightweight thread contexts to near-memory cores before the beginning of each remote memory read. Previous work has characterized the performance of the Chick prototype in terms of memory bandwidth and programming differences from more typical, non-migratory platforms, but there has not yet been an analysis of algorithms on this system. This work evaluates irregular algorithms that could benefit from the lightweight, memory-side processing of the Chick and demonstrates techniques and optimization strategies for achieving performance in sparse matrix-vector multiply operation (SpMV), breadth-first search (BFS), and graph alignment across up to eight distributed nodes encompassing 64 nodelets in the Chick system. We also define and justify relative metrics to compare prototype FPGA-based hardware with established ASIC architectures. The Chick currently supports up to 68x scaling for graph alignment, 80 MTEPS for BFS on balanced graphs, and 50\% of measured STREAM bandwidth for SpMV.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.02775](https://arxiv.org/abs/1901.02775)

##### PDF
[https://arxiv.org/pdf/1901.02775](https://arxiv.org/pdf/1901.02775)

