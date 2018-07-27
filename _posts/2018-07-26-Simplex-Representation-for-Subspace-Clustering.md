---
layout: post
title: "Simplex Representation for Subspace Clustering"
date: 2018-07-26 02:51:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Relation
author: Jun Xu, Deyu Meng, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Spectral clustering based methods have achieved leading performance on subspace clustering problem. State-of-the-art subspace clustering methods follow a three-stage framework: compute a coefficient matrix from the data by solving an optimization problem; construct an affinity matrix from the coefficient matrix; and obtain the final segmentation by applying spectral clustering to the affinity matrix. To construct a feasible affinity matrix, these methods mostly employ the operations of exponentiation, absolutely symmetrization, or squaring, etc. However, all these operations will force the negative entries (which cannot be explicitly avoided) in the coefficient matrix to be positive in computing the affinity matrix, and consequently damage the inherent correlations among the data. In this paper, we introduce the simplex representation (SR) to remedy this problem of representation based subspace clustering. We propose an SR based least square regression (SRLSR) model to construct a physically more meaningful affinity matrix by integrating the nonnegative property of graph into the representation coefficient computation while maintaining the discrimination of original data. The SRLSR model is reformulated as a linear equality-constrained problem, which is solved efficiently under the alternating direction method of multipliers framework. Experiments on benchmark datasets demonstrate that the proposed SRLSR algorithm is very efficient and outperforms state-of-the-art subspace clustering methods on accuracy.

##### Abstract (translated by Google)
基于谱聚类的方法在子空间聚类问题上取得了领先的性能。最先进的子空间聚类方法遵循三阶段框架：通过求解优化问题从数据计算系数矩阵;从系数矩阵构造亲和度矩阵;并通过将谱聚类应用于亲和度矩阵来获得最终分割。为了构造一个可行的亲和矩阵，这些方法主要采用取幂，绝对对称或平方等操作。但是，所有这些操作都会迫使系数矩阵中的否定条目（不能明确避免）在计算中为正亲和度矩阵，并因此破坏数据之间的固有相关性。在本文中，我们引入单纯形式表示（SR）来解决基于表示的子空间聚类问题。我们提出了一种基于SR的最小二乘回归（SRLSR）模型，通过将图的非负性质整合到表示系数计算中，同时保持对原始数据的区分，来构建物理上更有意义的亲和度矩阵。 SRLSR模型被重新表述为线性等式约束问题，在乘法器框架的交替方向方法下有效地求解。对基准数据集的实验表明，所提出的SRLSR算法非常有效，并且在精度方面优于最先进的子空间聚类方法。

##### URL
[http://arxiv.org/abs/1807.09930](http://arxiv.org/abs/1807.09930)

##### PDF
[http://arxiv.org/pdf/1807.09930](http://arxiv.org/pdf/1807.09930)

