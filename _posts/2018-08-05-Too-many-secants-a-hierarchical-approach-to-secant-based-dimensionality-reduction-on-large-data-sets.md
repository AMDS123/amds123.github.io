---
layout: post
title: "Too many secants: a hierarchical approach to secant-based dimensionality reduction on large data sets"
date: 2018-08-05 21:27:32
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Henry Kvinge, Elin Farnell, Michael Kirby, Chris Peterson
mathjax: true
---

* content
{:toc}

##### Abstract
A fundamental question in many data analysis settings is the problem of discerning the "natural" dimension of a data set. That is, when a data set is drawn from a manifold (possibly with noise), a meaningful aspect of the data is the dimension of that manifold. Various approaches exist for estimating this dimension, such as the method of Secant-Avoidance Projection (SAP). Intuitively, the SAP algorithm seeks to determine a projection which best preserves the lengths of all secants between points in a data set; by applying the algorithm to find the best projections to vector spaces of various dimensions, one may infer the dimension of the manifold of origination. That is, one may learn the dimension at which it is possible to construct a diffeomorphic copy of the data in a lower-dimensional Euclidean space. Using Whitney's embedding theorem, we can relate this information to the natural dimension of the data. A drawback of the SAP algorithm is that a data set with $T$ points has $O(T^2)$ secants, making the computation and storage of all secants infeasible for very large data sets. In this paper, we propose a novel algorithm that generalizes the SAP algorithm with an emphasis on addressing this issue. That is, we propose a hierarchical secant-based dimensionality-reduction method, which can be employed for data sets where explicitly calculating all secants is not feasible.

##### Abstract (translated by Google)
许多数据分析设置中的一个基本问题是辨别数据集的“自然”维度的问题。也就是说，当从歧管（可能具有噪声）绘制数据集时，数据的有意义的方面是该流形的维度。存在用于估计该维度的各种方法，例如正割避免投影（SAP）的方法。直观地，SAP算法试图确定一个投影，该投影最好地保留数据集中各点之间所有割线的长度;通过应用算法来找到各种维度的向量空间的最佳投影，可以推断出原始流形的维度。也就是说，人们可以学习在较低维欧氏空间中构造数据的微分形复制的维度。使用Whitney的嵌入定理，我们可以将这些信息与数据的自然维度联系起来。 SAP算法的缺点是具有$ T $点的数据集具有$ O（T ^ 2）$ secants，使得所有割线的计算和存储对于非常大的数据集是不可行的。在本文中，我们提出了一种新的算法，该算法概括了SAP算法，重点是解决这个问题。也就是说，我们提出了一种基于分层割线的降维方法，该方法可用于明确计算所有割线不可行的数据集。

##### URL
[https://arxiv.org/abs/1808.01686](https://arxiv.org/abs/1808.01686)

##### PDF
[https://arxiv.org/pdf/1808.01686](https://arxiv.org/pdf/1808.01686)

