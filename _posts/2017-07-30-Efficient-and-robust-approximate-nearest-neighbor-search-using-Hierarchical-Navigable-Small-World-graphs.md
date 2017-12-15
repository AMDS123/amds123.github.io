---
layout: post
title: "Efficient and robust approximate nearest neighbor search using Hierarchical Navigable Small World graphs"
date: 2017-07-30 12:07:54
categories: arXiv_CV
tags: arXiv_CV
author: Yu. A. Malkov, D. A. Yashunin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new algorithm for the approximate K-nearest neighbor search based on navigable small world graphs with controllable hierarchy (Hierarchical NSW). The proposed approach is fully graph-based, without any need for additional search structures, which are typically used at the coarse search stage of the most proximity graph techniques. Hierarchical NSW incrementally builds multi-layer structure consisting from hierarchical set of proximity graphs (layers) for nested subsets of the stored elements. The maximum layer in which an element is present is selected randomly with an exponentially decaying probability distribution. This allows producing graphs similar to the previously studied Navigable Small World (NSW) structures while additionally having the links separated by their characteristic distance scales. Starting search from the upper layer together with utilizing the scale separation boosts the performance compared to NSW and allows a logarithmic complexity scaling. Additional employment of a heuristic for selecting proximity graph neighbors significantly increases performance at high recall and in case of highly clustered data. Performance evaluation has demonstrated that the proposed general metric space search index is able to strongly outperform many previous state-of-the-art vector-only approaches. Similarity of the algorithm to the skip list structure allows straightforward balanced distributed implementation.

##### Abstract (translated by Google)
我们提出了一个基于可控层次（Hierarchical NSW）的可导航小世界图的近似K近邻搜索的新算法。所提出的方法是完全基于图表的，不需要额外的搜索结构，其通常在最接近图技术的粗略搜索阶段使用。分层NSW增量式地构建由存储的元素的嵌套子集的分层集合的邻近图（层）组成的多层结构。随机选择具有指数衰减概率分布的元素存在的最大层。这允许生成类似于先前研究的可导航小世界（NSW）结构的图表，同时另外具有由其特征距离尺度分隔的链接。从上层开始搜索以及利用比例分离提高了与NSW相比的性能，并允许对数复杂度缩放。附加的启发式选择邻近图邻居显着提高了高回忆的性能，并在高度集群的数据的情况下。性能评估已经证明，所提出的通用度量空间搜索索引能够强有力地胜过许多先前的最先进的仅矢量方法。该算法与跳跃列表结构的相似性允许直接平衡的分布式实现。

##### URL
[https://arxiv.org/abs/1603.09320](https://arxiv.org/abs/1603.09320)

##### PDF
[https://arxiv.org/pdf/1603.09320](https://arxiv.org/pdf/1603.09320)

