---
layout: post
title: "Reconfigurable Inverted Index"
date: 2018-08-12 16:47:47
categories: arXiv_CV
tags: arXiv_CV Attention
author: Yusuke Matsui, Ryota Hinami, Shin&#x27;ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Existing approximate nearest neighbor search systems suffer from two fundamental problems that are of practical importance but have not received sufficient attention from the research community. First, although existing systems perform well for the whole database, it is difficult to run a search over a subset of the database. Second, there has been no discussion concerning the performance decrement after many items have been newly added to a system. We develop a reconfigurable inverted index (Rii) to resolve these two issues. Based on the standard IVFADC system, we design a data layout such that items are stored linearly. This enables us to efficiently run a subset search by switching the search method to a linear PQ scan if the size of a subset is small. Owing to the linear layout, the data structure can be dynamically adjusted after new items are added, maintaining the fast speed of the system. Extensive comparisons show that Rii achieves a comparable performance with state-of-the art systems such as Faiss.

##### Abstract (translated by Google)
现有的近似最近邻搜索系统存在两个具有实际重要性但尚未得到研究界足够关注的基本问题。首先，尽管现有系统对整个数据库表现良好，但难以在数据库的子集上运行搜索。其次，在系统中新添加了许多项目之后，没有关于性能下降的讨论。我们开发了一个可重构的倒排索引（Rii）来解决这两个问题。基于标准的IVFADC系统，我们设计了一个数据布局，使项目线性存储。如果子集的大小很小，这使我们能够通过将搜索方法切换到线性PQ扫描来有效地运行子集搜索。由于线性布局，可以在添加新项目后动态调整数据结构，从而保持系统的快速运行。广泛的比较表明，Rii与最先进的系统如Faiss实现了相当的性能。

##### URL
[http://arxiv.org/abs/1808.03969](http://arxiv.org/abs/1808.03969)

##### PDF
[http://arxiv.org/pdf/1808.03969](http://arxiv.org/pdf/1808.03969)

