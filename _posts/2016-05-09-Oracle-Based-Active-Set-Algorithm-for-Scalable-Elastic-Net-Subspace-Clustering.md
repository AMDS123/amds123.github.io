---
layout: post
title: "Oracle Based Active Set Algorithm for Scalable Elastic Net Subspace Clustering"
date: 2016-05-09 15:49:36
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Chong You, Chun-Guang Li, Daniel P. Robinson, Rene Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art subspace clustering methods are based on expressing each data point as a linear combination of other data points while regularizing the matrix of coefficients with $\ell_1$, $\ell_2$ or nuclear norms. $\ell_1$ regularization is guaranteed to give a subspace-preserving affinity (i.e., there are no connections between points from different subspaces) under broad theoretical conditions, but the clusters may not be connected. $\ell_2$ and nuclear norm regularization often improve connectivity, but give a subspace-preserving affinity only for independent subspaces. Mixed $\ell_1$, $\ell_2$ and nuclear norm regularizations offer a balance between the subspace-preserving and connectedness properties, but this comes at the cost of increased computational complexity. This paper studies the geometry of the elastic net regularizer (a mixture of the $\ell_1$ and $\ell_2$ norms) and uses it to derive a provably correct and scalable active set method for finding the optimal coefficients. Our geometric analysis also provides a theoretical justification and a geometric interpretation for the balance between the connectedness (due to $\ell_2$ regularization) and subspace-preserving (due to $\ell_1$ regularization) properties for elastic net subspace clustering. Our experiments show that the proposed active set method not only achieves state-of-the-art clustering performance, but also efficiently handles large-scale datasets.

##### Abstract (translated by Google)
最先进的子空间聚类方法是基于将每个数据点表示为其他数据点的线性组合，同时用$ \ ell_1 $，$ \ ell_2 $或核准则来调整系数矩阵。在广泛的理论条件下，$ \ ell_1 $正则化保证给出一个保持子空间的亲和性（即在不同子空间的点之间没有连接），但是这些簇可能不能连通。核范数正则化常常改善连通性，但只给予独立子空间保留子空间的亲和力。混合$ \ ell_1 $，$ \ ell_2 $和核子规范正则化提供了子空间保留和连通性之间的平衡，但是这是以增加的计算复杂性为代价的。本文研究了弹性网格调节器（$ \ ell_1 $和$ \ ell_2 $范数的混合）的几何结构，并用它来导出一个证明正确和可扩展的有效集合方法来找到最优系数。我们的几何分析也为弹性网子空间聚类的连通性（由于$ \ ell_2 $正则化）和子空间保留（由于$ \ ell_1 $正则化）性质之间的平衡提供了理论上的合理性和几何解释。我们的实验表明，所提出的主动集方法不仅实现了最先进的聚类性能，而且还有效地处理大规模数据集。

##### URL
[https://arxiv.org/abs/1605.02633](https://arxiv.org/abs/1605.02633)

##### PDF
[https://arxiv.org/pdf/1605.02633](https://arxiv.org/pdf/1605.02633)

