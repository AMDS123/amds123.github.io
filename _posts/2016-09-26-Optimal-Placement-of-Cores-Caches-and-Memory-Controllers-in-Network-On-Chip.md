---
layout: post
title: "Optimal Placement of Cores, Caches and Memory Controllers in Network On-Chip"
date: 2016-09-26 16:48:31
categories: arXiv_CV
tags: arXiv_CV Face
author: Diman Zad Tootaghaj, Farshid Farhat
mathjax: true
---

* content
{:toc}

##### Abstract
Parallel programming is emerging fast and intensive applications need more resources, so there is a huge demand for on-chip multiprocessors. Accessing L1 caches beside the cores are the fastest after registers but the size of private caches cannot increase because of design, cost and technology limits. Then split I-cache and D-cache are used with shared LLC (last level cache). For a unified shared LLC, bus interface is not scalable, and it seems that distributed shared LLC (DSLLC) is a better choice. Most of papers assume a distributed shared LLC beside each core in on-chip network. Many works assume that DSLLCs are placed in all cores; however, we will show that this design ignores the effect of traffic congestion in on-chip network. In fact, our work focuses on optimal placement of cores, DSLLCs and even memory controllers to minimize the expected latency based on traffic load in a mesh on-chip network with fixed number of cores and total cache capacity. We try to do some analytical modeling deriving intended cost function and then optimize the mean delay of the on-chip network communication. This work is supposed to be verified using some traffic patterns that are run on CSIM simulator.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1607.04298](https://arxiv.org/abs/1607.04298)

##### PDF
[https://arxiv.org/pdf/1607.04298](https://arxiv.org/pdf/1607.04298)

