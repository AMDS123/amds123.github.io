---
layout: post
title: "Graphyti: A Semi-External Memory Graph Library for FlashGraph"
date: 2019-07-07 19:13:24
categories: arXiv_AI
tags: arXiv_AI
author: Disa Mhembere, Da Zheng, Carey E. Priebe, Joshua T. Vogelstein, Randal Burns
mathjax: true
---

* content
{:toc}

##### Abstract
Graph datasets exceed the in-memory capacity of most standalone machines. Traditionally, graph frameworks have overcome memory limitations through scale-out, distributing computing. Emerging frameworks avoid the network bottleneck of distributed data with Semi-External Memory (SEM) that uses a single multicore node and operates on graphs larger than memory. In SEM, $\mathcal{O}(m)$ data resides on disk and $\mathcal{O}(n)$ data in memory, for a graph with $n$ vertices and $m$ edges. For developers, this adds complexity because they must explicitly encode I/O within applications. We present principles that are critical for application developers to adopt in order to achieve state-of-the-art performance, while minimizing I/O and memory for algorithms in SEM. We present them in Graphyti, an extensible parallel SEM graph library built on FlashGraph and available in Python via pip. In SEM, Graphyti achieves 80% of the performance of in-memory execution and retains the performance of FlashGraph, which outperforms distributed engines, such as PowerGraph and Galois.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03335](http://arxiv.org/abs/1907.03335)

##### PDF
[http://arxiv.org/pdf/1907.03335](http://arxiv.org/pdf/1907.03335)

