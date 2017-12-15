---
layout: post
title: "A Riemannian Framework for Statistical Analysis of Topological Persistence Diagrams"
date: 2016-05-28 16:55:40
categories: arXiv_CV
tags: arXiv_CV Classification
author: Rushil Anirudh, Vinay Venkataraman, Karthikeyan Natesan Ramamurthy, Pavan Turaga
mathjax: true
---

* content
{:toc}

##### Abstract
Topological data analysis is becoming a popular way to study high dimensional feature spaces without any contextual clues or assumptions. This paper concerns itself with one popular topological feature, which is the number of $d-$dimensional holes in the dataset, also known as the Betti$-d$ number. The persistence of the Betti numbers over various scales is encoded into a persistence diagram (PD), which indicates the birth and death times of these holes as scale varies. A common way to compare PDs is by a point-to-point matching, which is given by the $n$-Wasserstein metric. However, a big drawback of this approach is the need to solve correspondence between points before computing the distance; for $n$ points, the complexity grows according to $\mathcal{O}($n$^3)$. Instead, we propose to use an entirely new framework built on Riemannian geometry, that models PDs as 2D probability density functions that are represented in the square-root framework on a Hilbert Sphere. The resulting space is much more intuitive with closed form expressions for common operations. The distance metric is 1) correspondence-free and also 2) independent of the number of points in the dataset. The complexity of computing distance between PDs now grows according to $\mathcal{O}(K^2)$, for a $K \times K$ discretization of $[0,1]^2$. This also enables the use of existing machinery in differential geometry towards statistical analysis of PDs such as computing the mean, geodesics, classification etc. We report competitive results with the Wasserstein metric, at a much lower computational load, indicating the favorable properties of the proposed approach.

##### Abstract (translated by Google)
拓扑数据分析正成为研究高维特征空间的一种流行方式，没有任何上下文的线索或假设。本文关注的是一个流行的拓扑特征，即数据集中$ d- $维的孔的数量，也就是Betti $ -d $数。在不同尺度上的贝蒂数的持续性被编码成持久性图（PD），其表示这些孔的出生和死亡时间随尺度变化。比较PD的常见方法是通过$ n $ -Wasserstein度量给出的点对点匹配。然而，这种方法的一大缺点是需要在计算距离之前解决点之间的对应关系;对于$ n $点，复杂性根据$ \ mathcal {O}（$ n $ ^ 3）$增长。相反，我们建议使用建立在黎曼几何上的全新框架，将PD模型化为在Hilbert球体上的平方根框架中表示的二维概率密度函数。对于常见操作，由此产生的空间更加直观。距离度量是1）无对应的，也是2）与数据集中的点数无关。计算PD之间的距离的复杂度现在根据$ \ mathcal {O}（K ^ 2）$增长，对于K $离散$ [0,1] ^ 2 $。这也使得使用微分几何中的现有机械来对PD进行统计分析，例如计算平均值，测地线，分类等。我们用低的计算负荷报告具有Wasserstein度量的竞争结果，表明所提议的有利特性做法。

##### URL
[https://arxiv.org/abs/1605.08912](https://arxiv.org/abs/1605.08912)

##### PDF
[https://arxiv.org/pdf/1605.08912](https://arxiv.org/pdf/1605.08912)

