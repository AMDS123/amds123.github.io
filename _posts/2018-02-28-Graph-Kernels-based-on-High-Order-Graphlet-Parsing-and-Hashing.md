---
layout: post
title: "Graph Kernels based on High Order Graphlet Parsing and Hashing"
date: 2018-02-28 12:37:41
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Relation Recognition
author: Anjan Dutta, Hichem Sahbi
mathjax: true
---

* content
{:toc}

##### Abstract
Graph-based methods are known to be successful in many machine learning and pattern classification tasks. These methods consider semi-structured data as graphs where nodes correspond to primitives (parts, interest points, segments, etc.) and edges characterize the relationships between these primitives. However, these non-vectorial graph data cannot be straightforwardly plugged into off-the-shelf machine learning algorithms without a preliminary step of -- explicit/implicit -- graph vectorization and embedding. This embedding process should be resilient to intra-class graph variations while being highly discriminant. In this paper, we propose a novel high-order stochastic graphlet embedding (SGE) that maps graphs into vector spaces. Our main contribution includes a new stochastic search procedure that efficiently parses a given graph and extracts/samples unlimitedly high-order graphlets. We consider these graphlets, with increasing orders, to model local primitives as well as their increasingly complex interactions. In order to build our graph representation, we measure the distribution of these graphlets into a given graph, using particular hash functions that efficiently assign sampled graphlets into isomorphic sets with a very low probability of collision. When combined with maximum margin classifiers, these graphlet-based representations have positive impact on the performance of pattern comparison and recognition as corroborated through extensive experiments using standard benchmark databases.

##### Abstract (translated by Google)
已知基于图的方法在许多机器学习和模式分类任务中是成功的。这些方法将半结构化数据视为图形，其中节点对应于基元（部分，兴趣点，分段等），并且边表征这些基元之间的关系。然而，这些非矢量图形数据不能直接插入现成的机器学习算法，而没有显式/隐式图形矢量化和嵌入的初步步骤。这种嵌入过程应该对类内图变化具有弹性，同时具有高度判别力。在本文中，我们提出了一种新的高阶随机小波嵌入（SGE），它将图映射到向量空间中。我们的主要贡献包括一个新的随机搜索过程，可高效地解析给定的图并无限制地提取/抽样高阶图。我们认为这些图形单元随着订单的增加对本地原语以及它们日益复杂的交互进行建模。为了构建我们的图表表示，我们使用特定的散列函数来度量这些图表的分布情况，使用特定的散列函数将抽样的图表有效地分配到同构集合中，并且冲突概率非常低。当与最大边缘分类器相结合时，这些基于图表的表示对通过使用标准基准数据库的广泛实验证实的模式比较和识别的性能具有积极影响。

##### URL
[http://arxiv.org/abs/1803.00425](http://arxiv.org/abs/1803.00425)

##### PDF
[http://arxiv.org/pdf/1803.00425](http://arxiv.org/pdf/1803.00425)

