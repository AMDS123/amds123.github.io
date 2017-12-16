---
layout: post
title: "Multi-view Low-rank Sparse Subspace Clustering"
date: 2017-08-29 13:07:56
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Maria Brbic, Ivica Kopriva
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing approaches address multi-view subspace clustering problem by constructing the affinity matrix on each view separately and afterwards propose how to extend spectral clustering algorithm to handle multi-view data. This paper presents an approach to multi-view subspace clustering that learns a joint subspace representation by constructing affinity matrix shared among all views. Relying on the importance of both low-rank and sparsity constraints in the construction of the affinity matrix, we introduce the objective that balances between the agreement across different views, while at the same time encourages sparsity and low-rankness of the solution. Related low-rank and sparsity constrained optimization problem is for each view solved using the alternating direction method of multipliers. Furthermore, we extend our approach to cluster data drawn from nonlinear subspaces by solving the corresponding problem in a reproducing kernel Hilbert space. The proposed algorithm outperforms state-of-the-art multi-view subspace clustering algorithms on one synthetic and four real-world datasets.

##### Abstract (translated by Google)
目前大多数方法通过在每个视图上分别构建亲和矩阵来解决多视图子空间聚类问题，并提出了如何扩展谱聚类算法来处理多视点数据。本文提出了一种多视点子空间聚类的方法，通过构建所有视点之间共享的亲和矩阵来学习联合子空间表示。依靠亲和度矩阵构造中的低秩和稀疏约束的重要性，我们引入了平衡不同观点之间协调的目标，同时又鼓励解决方案的稀疏性和低秩度。相关的低秩和稀疏约束优化问题是用乘法器的交替方向法解决的每个视图。此外，通过解决再生核Hilbert空间中的相应问题，我们扩展了从非线性子空间得到的聚类数据的方法。所提出的算法在一个合成数据集和四个真实世界的数据集上优于现有技术的多视图子空间聚类算法。

##### URL
[https://arxiv.org/abs/1708.08732](https://arxiv.org/abs/1708.08732)

##### PDF
[https://arxiv.org/pdf/1708.08732](https://arxiv.org/pdf/1708.08732)

