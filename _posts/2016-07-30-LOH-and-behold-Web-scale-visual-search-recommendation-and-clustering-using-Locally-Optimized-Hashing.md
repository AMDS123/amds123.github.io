---
layout: post
title: "LOH and behold: Web-scale visual search, recommendation and clustering using Locally Optimized Hashing"
date: 2016-07-30 02:34:52
categories: arXiv_CV
tags: arXiv_CV Recommendation
author: Yannis Kalantidis, Lyndon Kennedy, Huy Nguyen, Clayton Mellina, David A. Shamma
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel hashing-based matching scheme, called Locally Optimized Hashing (LOH), based on a state-of-the-art quantization algorithm that can be used for efficient, large-scale search, recommendation, clustering, and deduplication. We show that matching with LOH only requires set intersections and summations to compute and so is easily implemented in generic distributed computing systems. We further show application of LOH to: a) large-scale search tasks where performance is on par with other state-of-the-art hashing approaches; b) large-scale recommendation where queries consisting of thousands of images can be used to generate accurate recommendations from collections of hundreds of millions of images; and c) efficient clustering with a graph-based algorithm that can be scaled to massive collections in a distributed environment or can be used for deduplication for small collections, like search results, performing better than traditional hashing approaches while only requiring a few milliseconds to run. In this paper we experiment on datasets of up to 100 million images, but in practice our system can scale to larger collections and can be used for other types of data that have a vector representation in a Euclidean space.

##### Abstract (translated by Google)
我们提出了一种新颖的基于散列的匹配方案，称为本地优化散列（LOH），基于最先进的量化算法，可用于高效的大规模搜索，推荐，聚类和重复数据删除。我们证明，与LOH匹配只需要设置交集和求和就可以计算，所以很容易在通用分布式计算系统中实现。我们进一步展示了LOH的应用：a）大规模的搜索任务，其性能与其他最先进的哈希方法相同; b）大规模的建议，可以使用包含数千幅图像的查询，从数亿幅图像的集合中生成精确的建议; c）利用基于图形的算法进行高效聚类，该算法可以在分布式环境中扩展为海量集合，也可以用于小集合（如搜索结果）的重复数据删除，性能优于传统哈希方法，而只需要几毫秒。在本文中，我们对多达1亿个图像的数据集进行了实验，但是实际上，我们的系统可以扩展到更大的集合，并且可以用于在欧几里得空间中具有矢量表示的其他类型的数据。

##### URL
[https://arxiv.org/abs/1604.06480](https://arxiv.org/abs/1604.06480)

##### PDF
[https://arxiv.org/pdf/1604.06480](https://arxiv.org/pdf/1604.06480)

