---
layout: post
title: "Dual Principal Component Pursuit"
date: 2017-07-22 16:24:27
categories: arXiv_CV
tags: arXiv_CV Face
author: Manolis C. Tsakiris, Rene Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of outlier rejection in single subspace learning. Classical approaches work with a direct representation of the subspace, and are thus efficient when the subspace dimension is small. Our approach works with a dual representation of the subspace and hence aims to find its orthogonal complement; as such, it is particularly suitable for subspaces whose dimension is very close to the ambient dimension (subspaces of high relative dimension). We pose the problem of computing normal vectors to the subspace as a non-convex $\ell_1$ minimization problem on the sphere, which we call Dual Principal Component Pursuit (DPCP) problem. We provide theoretical guarantees, under which every global solution of DPCP is a vector in the orthogonal complement of the inlier subspace. Moreover, we relax the non-convex DPCP problem to a recursion of linear programming problems, which, as we show, converges in a finite number of steps to a vector orthogonal to the subspace. In particular, when the inlier subspace is a hyperplane, then the linear programming recursion converges in a finite number of steps to the global minimum of the non-convex DPCP problem. We also propose algorithms based on alternating minimization and Iteratively Reweighted Least-Squares, that are suitable for dealing with large-scale data. Extensive experiments on synthetic data show that the proposed methods are able to handle more outliers and higher relative dimensions than the state-of-the-art methods, while experiments with real face and object images show that our DPCP-based methods are competitive to the state-of-the-art.

##### Abstract (translated by Google)
我们考虑单个子空间学习中的异常排斥问题。经典方法直接表示子空间，因此在子空间维数很小时是有效的。我们的方法与子空间的双重表示一起工作，因此旨在找到它的正交补充;因此，它特别适用于维度非常接近环境维度的子空间（高相对维度子空间）。我们提出将子空间的法向量作为非球面上的非凸$ \ ell_1 $最小化问题，我们称之为双主成分追踪（Dual Principal Component Pursuit，DPCP）问题。我们提供了理论上的保证，在这个理论保证下，DPCP的每个全局解都是在内点子空间正交补的一个向量。此外，我们将非凸的DPCP问题放宽为线性规划问题的递归，正如我们所表明的那样，这些问题会以有限数量的步骤收敛到与子空间正交的矢量。特别是，当内部子空间是超平面时，线性规划递归收敛在非凸DPCP问题的全局最小值的有限数量的步骤中。我们还提出了基于交替最小化和迭代重新加权最小二乘法的算法，这些算法适合处理大规模数据。综合数据的大量实验表明，所提出的方法能够处理比现有技术方法更多的异常值和更高的相对维度，而使用真实面部和目标图像的实验表明，基于DPCP的方法与最先进的。

##### URL
[https://arxiv.org/abs/1510.04390](https://arxiv.org/abs/1510.04390)

##### PDF
[https://arxiv.org/pdf/1510.04390](https://arxiv.org/pdf/1510.04390)

