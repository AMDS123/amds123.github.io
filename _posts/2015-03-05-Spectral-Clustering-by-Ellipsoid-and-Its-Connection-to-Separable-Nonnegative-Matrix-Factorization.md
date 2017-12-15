---
layout: post
title: "Spectral Clustering by Ellipsoid and Its Connection to Separable Nonnegative Matrix Factorization"
date: 2015-03-05 04:07:46
categories: arXiv_CV
tags: arXiv_CV
author: Tomohiko Mizutani
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a variant of the normalized cut algorithm for spectral clustering. Although the normalized cut algorithm applies the K-means algorithm to the eigenvectors of a normalized graph Laplacian for finding clusters, our algorithm instead uses a minimum volume enclosing ellipsoid for them. We show that the algorithm shares similarity with the ellipsoidal rounding algorithm for separable nonnegative matrix factorization. Our theoretical insight implies that the algorithm can serve as a bridge between spectral clustering and separable NMF. The K-means algorithm has the issues in that the choice of initial points affects the construction of clusters and certain choices result in poor clustering performance. The normalized cut algorithm inherits these issues since K-means is incorporated in it, whereas the algorithm proposed here does not. An empirical study is presented to examine the performance of the algorithm.

##### Abstract (translated by Google)
本文提出了谱聚类归一化切割算法的一个变种。尽管归一化的切割算法将K均值算法应用于归一化图拉普拉斯算子的特征向量以寻找聚类，但是我们的算法使用包含最小体积的椭圆体作为它们。我们证明该算法与可分离非负矩阵分解的椭圆舍入算法具有相似性。我们的理论洞察意味着该算法可以作为谱聚类和可分离NMF之间的桥梁。 K均值算法存在的问题是初始点的选择影响了簇的构建，而某些选择会导致较差的聚类性能。归一化切割算法继承了这些问题，因为包含了K-means，而这里提出的算法却没有。提出了一个实证研究来检验算法的性能。

##### URL
[https://arxiv.org/abs/1503.01531](https://arxiv.org/abs/1503.01531)

##### PDF
[https://arxiv.org/pdf/1503.01531](https://arxiv.org/pdf/1503.01531)

