---
layout: post
title: "A Fast Factorization-based Approach to Robust PCA"
date: 2016-09-27 21:32:16
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Chong Peng, Zhao Kang, Qiang Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Robust principal component analysis (RPCA) has been widely used for recovering low-rank matrices in many data mining and machine learning problems. It separates a data matrix into a low-rank part and a sparse part. The convex approach has been well studied in the literature. However, state-of-the-art algorithms for the convex approach usually have relatively high complexity due to the need of solving (partial) singular value decompositions of large matrices. A non-convex approach, AltProj, has also been proposed with lighter complexity and better scalability. Given the true rank $r$ of the underlying low rank matrix, AltProj has a complexity of $O(r^2dn)$, where $d\times n$ is the size of data matrix. In this paper, we propose a novel factorization-based model of RPCA, which has a complexity of $O(kdn)$, where $k$ is an upper bound of the true rank. Our method does not need the precise value of the true rank. From extensive experiments, we observe that AltProj can work only when $r$ is precisely known in advance; however, when the needed rank parameter $r$ is specified to a value different from the true rank, AltProj cannot fully separate the two parts while our method succeeds. Even when both work, our method is about 4 times faster than AltProj. Our method can be used as a light-weight, scalable tool for RPCA in the absence of the precise value of the true rank.

##### Abstract (translated by Google)
在许多数据挖掘和机器学习问题中，鲁棒主成分分析（RPCA）已被广泛用于恢复低秩矩阵。它将一个数据矩阵分成一个低一部分和一个稀疏部分。凸面的方法已经在文献中得到了很好的研究。然而，由于需要解决大矩阵的（部分）奇异值分解，所以用于凸面方法的最新算法通常具有相对较高的复杂度。还提出了非凸方法AltProj，其具有更轻的复杂性和更好的可伸缩性。给定基础低秩矩阵的真实秩$ r $，AltProj的复杂度为$ O（r ^ 2dn）$，其中$ d \ times n $是数据矩阵的大小。在本文中，我们提出了一种新的基于因子分解的RPCA模型，其复杂度为$ O（kdn）$，其中$ k $是真实等级的上限。我们的方法不需要真正的等级的精确值。从广泛的实验中，我们观察到AltProj只能在事先精确地知道$ r $的情况下工作。但是，当所需的排名参数$ r $被指定为与真实排名不同的值时，AltProj在我们的方法成功时无法完全分离这两个部分。即使两者都工作，我们的方法比AltProj快4倍。我们的方法可以作为一个轻量级，可扩展的RPCA工具，在没有真实排名的精确值的情况下。

##### URL
[https://arxiv.org/abs/1609.08677](https://arxiv.org/abs/1609.08677)

##### PDF
[https://arxiv.org/pdf/1609.08677](https://arxiv.org/pdf/1609.08677)

