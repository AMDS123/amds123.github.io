---
layout: post
title: "Low Rank Matrix Recovery with Simultaneous Presence of Outliers and Sparse Corruption"
date: 2017-02-07 02:08:51
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Mostafa Rahmani, George Atia
mathjax: true
---

* content
{:toc}

##### Abstract
We study a data model in which the data matrix D can be expressed as D = L + S + C, where L is a low rank matrix, S an element-wise sparse matrix and C a matrix whose non-zero columns are outlying data points. To date, robust PCA algorithms have solely considered models with either S or C, but not both. As such, existing algorithms cannot account for simultaneous element-wise and column-wise corruptions. In this paper, a new robust PCA algorithm that is robust to simultaneous types of corruption is proposed. Our approach hinges on the sparse approximation of a sparsely corrupted column so that the sparse expansion of a column with respect to the other data points is used to distinguish a sparsely corrupted inlier column from an outlying data point. We also develop a randomized design which provides a scalable implementation of the proposed approach. The core idea of sparse approximation is analyzed analytically where we show that the underlying ell_1-norm minimization can obtain the representation of an inlier in presence of sparse corruptions.

##### Abstract (translated by Google)
我们研究了一个数据模型，其中数据矩阵D可以表示为D = L + S + C，其中L是低秩矩阵，S是元素级稀疏矩阵，C是非零级数列外的矩阵点。迄今为止，稳健的PCA算法只考虑S或C模型，但不能同时考虑两者。因此，现有的算法不能说明同时逐元和列方式的损坏。在本文中，提出了一种鲁棒性同时腐败的新的鲁棒PCA算法。我们的方法取决于稀疏损坏列的稀疏近似，使得列的相对于其他数据点的稀疏扩展被用来区分离边数据点的稀疏损坏的内部列和外部数据点。我们还开发了一个随机设计，提供了一个可扩展的实现方法。稀疏近似的核心思想是分析性分析的，其中我们证明了基本的ell_1范数最小化可以在稀疏腐败存在的情况下获得一个内部表示。

##### URL
[https://arxiv.org/abs/1702.01847](https://arxiv.org/abs/1702.01847)

##### PDF
[https://arxiv.org/pdf/1702.01847](https://arxiv.org/pdf/1702.01847)

