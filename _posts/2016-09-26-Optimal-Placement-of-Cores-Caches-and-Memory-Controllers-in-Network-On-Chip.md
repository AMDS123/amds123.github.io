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
并行编程正在快速兴起，密集型应用程序需要更多的资源，因此对片上多处理器有着巨大的需求。访问内核旁边的L1缓存是注册后最快的，但由于设计，成本和技术限制，私有缓存的大小不能增加。然后拆分I-cache和D-cache与共享LLC（最后一级缓存）一起使用。对于统一的共享LLC来说，总线接口是不可扩展的，似乎分布式共享LLC（DSLLC）是更好的选择。大多数论文假设片上网络中每个核心旁边都有一个分布式共享LLC。许多作品都假定DSLLC被放置在所有内核中;但是，我们将表明这种设计忽略了片上网络中的拥塞的影响。实际上，我们的工作主要集中在核心，DSLLC甚至内存控制器的最佳布局上，以便在具有固定核心数量和总缓存容量的网状片上网络中基于流量负载的预期延迟最小化。我们尝试做一些分析建模，推导出预期的成本函数，然后优化片上网络通信的平均延迟。这项工作应该使用在CSIM模拟器上运行的一些流量模式进行验证。

##### URL
[https://arxiv.org/abs/1607.04298](https://arxiv.org/abs/1607.04298)

##### PDF
[https://arxiv.org/pdf/1607.04298](https://arxiv.org/pdf/1607.04298)

