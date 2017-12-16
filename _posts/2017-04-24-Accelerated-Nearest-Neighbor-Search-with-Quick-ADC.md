---
layout: post
title: "Accelerated Nearest Neighbor Search with Quick ADC"
date: 2017-04-24 17:49:37
categories: arXiv_CV
tags: arXiv_CV
author: Fabien André (Technicolor), Anne-Marie Kermarrec (Inria), Nicolas Le Scouarnec (Technicolor)
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient Nearest Neighbor (NN) search in high-dimensional spaces is a foundation of many multimedia retrieval systems. Because it offers low responses times, Product Quantization (PQ) is a popular solution. PQ compresses high-dimensional vectors into short codes using several sub-quantizers, which enables in-RAM storage of large databases. This allows fast answers to NN queries, without accessing the SSD or HDD. The key feature of PQ is that it can compute distances between short codes and high-dimensional vectors using cache-resident lookup tables. The efficiency of this technique, named Asymmetric Distance Computation (ADC), remains limited because it performs many cache accesses. In this paper, we introduce Quick ADC, a novel technique that achieves a 3 to 6 times speedup over ADC by exploiting Single Instruction Multiple Data (SIMD) units available in current CPUs. Efficiently exploiting SIMD requires algorithmic changes to the ADC procedure. Namely, Quick ADC relies on two key modifications of ADC: (i) the use 4-bit sub-quantizers instead of the standard 8-bit sub-quantizers and (ii) the quantization of floating-point distances. This allows Quick ADC to exceed the performance of state-of-the-art systems, e.g., it achieves a Recall@100 of 0.94 in 3.4 ms on 1 billion SIFT descriptors (128-bit codes).

##### Abstract (translated by Google)
高维空间中的有效最近邻（NN）搜索是许多多媒体检索系统的基础。因为它提供的响应时间很短，产品量化（PQ）是一种流行的解决方案。 PQ使用几个子量化器将高维矢量压缩为短码，这使得大型数据库的RAM内存储成为可能。这允许NN查询的快速答案，而无需访问SSD或HDD。 PQ的主要特点是可以使用缓存驻留查找表来计算短代码和高维向量之间的距离。这种称为非对称距离计算（ADC）技术的效率保持有限，因为它执行许多缓存访问。在本文中，我们将介绍快速ADC，这是一种新颖的技术，通过利用当前CPU中可用的单指令多数据（SIMD）单元，实现了比ADC高3到6倍的加速比。有效利用SIMD需要对ADC过程进行算法改变。即，快速ADC依赖于ADC的两个关键修改：（i）使用4位子量化器而不是标准的8位子量化器和（ii）浮点距离的量化。这使得快速ADC能够超越现有技术系统的性能，例如，在10亿SIFT描述符（128位代码）上，其在3.4ms内达到0.94的Recall @ 100。

##### URL
[https://arxiv.org/abs/1704.07355](https://arxiv.org/abs/1704.07355)

##### PDF
[https://arxiv.org/pdf/1704.07355](https://arxiv.org/pdf/1704.07355)

