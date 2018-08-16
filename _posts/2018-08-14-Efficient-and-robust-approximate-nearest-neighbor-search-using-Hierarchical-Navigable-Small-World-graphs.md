---
layout: post
title: "Efficient and robust approximate nearest neighbor search using Hierarchical Navigable Small World graphs"
date: 2018-08-14 19:29:07
categories: arXiv_CV
tags: arXiv_CV
author: Yu. A. Malkov, D. A. Yashunin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach for the approximate K-nearest neighbor search based on navigable small world graphs with controllable hierarchy (Hierarchical NSW, HNSW). The proposed solution is fully graph-based, without any need for additional search structures, which are typically used at the coarse search stage of the most proximity graph techniques. Hierarchical NSW incrementally builds a multi-layer structure consisting from hierarchical set of proximity graphs (layers) for nested subsets of the stored elements. The maximum layer in which an element is present is selected randomly with an exponentially decaying probability distribution. This allows producing graphs similar to the previously studied Navigable Small World (NSW) structures while additionally having the links separated by their characteristic distance scales. Starting search from the upper layer together with utilizing the scale separation boosts the performance compared to NSW and allows a logarithmic complexity scaling. Additional employment of a heuristic for selecting proximity graph neighbors significantly increases performance at high recall and in case of highly clustered data. Performance evaluation has demonstrated that the proposed general metric space search index is able to strongly outperform previous opensource state-of-the-art vector-only approaches. Similarity of the algorithm to the skip list structure allows straightforward balanced distributed implementation.

##### Abstract (translated by Google)
我们提出了一种基于具有可控层次结构的可导航小世界图（Hierarchical NSW，HNSW）的近似K-最近邻搜索的新方法。所提出的解决方案是完全基于图形的，不需要额外的搜索结构，其通常在最接近图形技术的粗略搜索阶段使用。 Hierarchical NSW逐步构建一个多层结构，该结构由存储元素的嵌套子集的接近图（层）的分层集组成。存在元素的最大层是以指数衰减的概率分布随机选择的。这允许产生类似于先前研究的可导航小世界（NSW）结构的图形，同时另外具有由其特征距离标度分开的链接。与NSW相比，从上层开始搜索并利用比例分离提高了性能，并允许对数复杂度缩放。用于选择邻近图邻居的启发式的额外使用显着地提高了高召回率和高度集群数据的性能。性能评估已经证明，所提出的通用度量空间搜索索引能够强大地优于先前开源的最先进的向量方法。算法与跳过列表结构的相似性允许直接平衡的分布式实现。

##### URL
[http://arxiv.org/abs/1603.09320](http://arxiv.org/abs/1603.09320)

##### PDF
[http://arxiv.org/pdf/1603.09320](http://arxiv.org/pdf/1603.09320)

