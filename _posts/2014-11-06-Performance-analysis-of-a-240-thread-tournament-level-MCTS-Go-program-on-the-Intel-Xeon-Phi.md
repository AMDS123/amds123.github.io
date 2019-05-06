---
layout: post
title: "Performance analysis of a 240 thread tournament level MCTS Go program on the Intel Xeon Phi"
date: 2014-11-06 21:18:03
categories: arXiv_CV
tags: arXiv_CV
author: S. Ali Mirsoleimani, Aske Plaat, Jos Vermaseren, Jaap van den Herik
mathjax: true
---

* content
{:toc}

##### Abstract
In 2013 Intel introduced the Xeon Phi, a new parallel co-processor board. The Xeon Phi is a cache-coherent many-core shared memory architecture claiming CPU-like versatility, programmability, high performance, and power efficiency. The first published micro-benchmark studies indicate that many of Intel's claims appear to be true. The current paper is the first study on the Phi of a complex artificial intelligence application. It contains an open source MCTS application for playing tournament quality Go (an oriental board game). We report the first speedup figures for up to 240 parallel threads on a real machine, allowing a direct comparison to previous simulation studies. After a substantial amount of work, we observed that performance scales well up to 32 threads, largely confirming previous simulation results of this Go program, although the performance surprisingly deteriorates between 32 and 240 threads. Furthermore, we report (1) unexpected performance anomalies between the Xeon Phi and Xeon CPU for small problem sizes and small numbers of threads, and (2) that performance is sensitive to scheduling choices. Achieving good performance on the Xeon Phi for complex programs is not straightforward; it requires a deep understanding of (1) search patterns, (2) of scheduling, and (3) of the architecture and its many cores and caches. In practice, the Xeon Phi is less straightforward to program for than originally envisioned by Intel.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1409.4297](https://arxiv.org/abs/1409.4297)

##### PDF
[https://arxiv.org/pdf/1409.4297](https://arxiv.org/pdf/1409.4297)

