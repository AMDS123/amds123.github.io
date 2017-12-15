---
layout: post
title: "Sparse Subspace Clustering via Diffusion Process"
date: 2016-08-05 08:05:24
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Qilin Li, Ling Li, Wanquan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Subspace clustering refers to the problem of clustering high-dimensional data that lie in a union of low-dimensional subspaces. State-of-the-art subspace clustering methods are based on the idea of expressing each data point as a linear combination of other data points while regularizing the matrix of coefficients with L1, L2 or nuclear norms for a sparse solution. L1 regularization is guaranteed to give a subspace-preserving affinity (i.e., there are no connections between points from different subspaces) under broad theoretical conditions, but the clusters may not be fully connected. L2 and nuclear norm regularization often improve connectivity, but give a subspace-preserving affinity only for independent subspaces. Mixed L1, L2 and nuclear norm regularization could offer a balance between the subspace-preserving and connectedness properties, but this comes at the cost of increased computational complexity. This paper focuses on using L1 norm and alleviating the corresponding connectivity problem by a simple yet efficient diffusion process on subspace affinity graphs. Without adding any tuning parameter , our method can achieve state-of-the-art clustering performance on Hopkins 155 and Extended Yale B data sets.

##### Abstract (translated by Google)
子空间聚类是指对低维子空间的联合中的高维数据进行聚类的问题。最先进的子空间聚类方法基于这样的想法：将每个数据点表示为其他数据点的线性组合，同时用L1，L2或核准则规则化系数矩阵以获得稀疏解。在广泛的理论条件下，L1正则化保证了子空间保持的亲和性（即不同子空间的点之间没有连接），但是这些簇可能并不完全连通。 L2和核范数正则化常常改善连通性，但只给予独立子空间保留子空间的亲和力。混合的L1，L2和核范数正则化可以在子空间保留和连通性之间提供平衡，但这是以增加的计算复杂度为代价的。本文重点研究了L1范数，并通过一个简单而有效的子空间亲和图的扩散过程缓解了相应的连通性问题。在不添加任何调整参数的情况下，我们的方法可以在Hopkins 155和Extended Yale B数据集上实现最先进的聚类性能。

##### URL
[https://arxiv.org/abs/1608.01793](https://arxiv.org/abs/1608.01793)

##### PDF
[https://arxiv.org/pdf/1608.01793](https://arxiv.org/pdf/1608.01793)

