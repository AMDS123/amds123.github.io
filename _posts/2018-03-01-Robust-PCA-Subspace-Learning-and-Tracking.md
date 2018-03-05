---
layout: post
title: "Robust PCA, Subspace Learning, and Tracking"
date: 2018-03-01 23:33:54
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking
author: Namrata Vaswani, Thierry Bouwmans, Sajid Javed, Praneeth Narayanamurthy
mathjax: true
---

* content
{:toc}

##### Abstract
PCA is one of the most widely used dimension reduction techniques. A related easier problem is "subspace learning" or "subspace estimation". Given relatively clean data, both are easily solved via singular value decomposition (SVD). The problem of subspace learning or PCA in the presence of outliers is called robust subspace learning or robust PCA (RPCA). For long data sequences, if one tries to use a single lower dimensional subspace to represent the data, the required subspace dimension may end up being quite large. For such data, a better model is to assume that it lies in a low-dimensional subspace that can change over time, albeit gradually. The problem of tracking such data (and the subspaces) while being robust to outliers is called robust subspace tracking (RST). This article provides a magazine-style overview of the entire field of robust subspace learning and tracking. In particular solutions for three problems are discussed in detail: RPCA via sparse+low-rank matrix decomposition (S+LR), RST via S+LR, and "robust subspace recovery". This assumes that an entire data vector is either an outlier or an inlier. The S+LR formulation instead assumes that outliers occur on only a few data vector indices and hence are well modeled as sparse corruptions.

##### Abstract (translated by Google)
PCA是最广泛使用的降维技术之一。一个相关的更容易的问题是“子空间学习”或“子空间估计”。给定相对干净的数据，都可以通过奇异值分解（SVD）轻松解决。存在异常值的子空间学习或PCA问题称为鲁棒子空间学习或强健PCA（RPCA）。对于长数据序列，如果试图使用单个较低维度的子空间来表示数据，则所需的子空间维度可能会相当大。对于这样的数据，更好的模型是假设它位于可以随时间变化的低维子空间中，尽管是逐渐变化的。跟踪这些数据（和子空间）同时对异常值具有鲁棒性的问题称为鲁棒子空间跟踪（RST）。本文提供了杂志风格的整个鲁棒子空间学习和跟踪领域的概述。具体讨论了三个问题的解决方案：通过稀疏+低秩矩阵分解（S + LR）的RPCA，通过S + LR的RST和“鲁棒子空间恢复”。这假定整个数据向量是异常值或内部值。 S + LR公式假定异常值仅出现在少数数据向量索引上，因此很好地建模为稀疏损坏。

##### URL
[http://arxiv.org/abs/1711.09492](http://arxiv.org/abs/1711.09492)

##### PDF
[http://arxiv.org/pdf/1711.09492](http://arxiv.org/pdf/1711.09492)

