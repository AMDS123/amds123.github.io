---
layout: post
title: "k-Nearest Neighbors on Road Networks: A Journey in Experimentation and In-Memory Implementation"
date: 2016-08-10 13:58:37
categories: arXiv_CV
tags: arXiv_CV
author: Tenindra Abeywickrama, Muhammad Aamir Cheema, David Taniar
mathjax: true
---

* content
{:toc}

##### Abstract
A k nearest neighbor (kNN) query on road networks retrieves the k closest points of interest (POIs) by their network distances from a given location. Today, in the era of ubiquitous mobile computing, this is a highly pertinent query. While Euclidean distance has been used as a heuristic to search for the closest POIs by their road network distance, its efficacy has not been thoroughly investigated. The most recent methods have shown significant improvement in query performance. Earlier studies, which proposed disk-based indexes, were compared to the current state-of-the-art in main memory. However, recent studies have shown that main memory comparisons can be challenging and require careful adaptation. This paper presents an extensive experimental investigation in main memory to settle these and several other issues. We use efficient and fair memory-resident implementations of each method to reproduce past experiments and conduct additional comparisons for several overlooked evaluations. Notably we revisit a previously discarded technique (IER) showing that, through a simple improvement, it is often the best performing technique.

##### Abstract (translated by Google)
在道路网络上的k个最近邻居（kNN）查询通过距离给定位置的网络距离来检索k个最近兴趣点（POI）。今天，在无处不在的移动计算时代，这是一个非常有针对性的问题。虽然欧氏距离已被用作启发式搜索路网距离最近的兴趣点，其功效尚未被彻底调查。最新的方法已经显示出查询性能的显着改善。早期的研究，提出了基于磁盘的索引，与主要记忆中当前的最新技术进行了比较。然而，最近的研究表明，主要的记忆比较可能是具有挑战性的，需要仔细的适应。本文提出了一个广泛的实验调查来解决这些问题和其他一些问题。我们使用每种方法的有效和公平的内存驻留实现来重现以前的实验，并对几个被忽略的评估进行额外的比较。值得注意的是，我们重新审视了以前被抛弃的技术（IER），表明通过简单的改进，它通常是表现最好的技术。

##### URL
[https://arxiv.org/abs/1601.01549](https://arxiv.org/abs/1601.01549)

##### PDF
[https://arxiv.org/pdf/1601.01549](https://arxiv.org/pdf/1601.01549)

