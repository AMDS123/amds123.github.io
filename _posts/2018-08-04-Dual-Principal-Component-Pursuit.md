---
layout: post
title: "Dual Principal Component Pursuit"
date: 2018-08-04 18:53:49
categories: arXiv_CV
tags: arXiv_CV
author: Manolis C. Tsakiris, Rene Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of learning a linear subspace from data corrupted by outliers. Classical approaches are typically designed for the case in which the subspace dimension is small relative to the ambient dimension. Our approach works with a dual representation of the subspace and hence aims to find its orthogonal complement; as such, it is particularly suitable for subspaces whose dimension is close to the ambient dimension (subspaces of high relative dimension). We pose the problem of computing normal vectors to the inlier subspace as a non-convex $\ell_1$ minimization problem on the sphere, which we call Dual Principal Component Pursuit (DPCP) problem. We provide theoretical guarantees under which every global solution to DPCP is a vector in the orthogonal complement of the inlier subspace. Moreover, we relax the non-convex DPCP problem to a recursion of linear programs whose solutions are shown to converge in a finite number of steps to a vector orthogonal to the subspace. In particular, when the inlier subspace is a hyperplane, the solutions to the recursion of linear programs converge to the global minimum of the non-convex DPCP problem in a finite number of steps. We also propose algorithms based on alternating minimization and iteratively re-weighted least squares, which are suitable for dealing with large-scale data. Experiments on synthetic data show that the proposed methods are able to handle more outliers and higher relative dimensions than current state-of-the-art methods, while experiments in the context of the three-view geometry problem in computer vision suggest that the proposed methods can be a useful or even superior alternative to traditional RANSAC-based approaches for computer vision and other applications.

##### Abstract (translated by Google)
我们考虑从异常值破坏的数据中学习线性子空间的问题。经典方法通常针对子空间维度相对于环境维度较小的情况而设计。我们的方法与子空间的双重表示一起工作，因此旨在找到它的正交补码;因此，它特别适用于尺寸接近环境尺寸的子空间（高相对尺寸的子空间）。我们将向内部子空间计算法向量的问题作为球体上的非凸$ \ ell_1 $最小化问题，我们称之为双主成分追踪（DPCP）问题。我们提供理论保证，根据这种保证，DPCP的每个全局解决方案都是inlier子空间的正交补码中的向量。此外，我们将非凸DPCP问题放宽到线性程序的递归，其线性程序的解被显示为以有限数量的步长收敛到与子空间正交的向量。特别地，当内部子空间是超平面时，线性程序的递归的解决方案在有限数量的步骤中收敛到非凸DPCP问题的全局最小值。我们还提出了基于交替最小化和迭代重新加权最小二乘的算法，这些算法适用于处理大规模数据。对合成数据的实验表明，与当前最先进的方法相比，所提出的方法能够处理更多的异常值和更高的相对维度，而在计算机视觉中的三视图几何问题的上下文中的实验表明所提出的方法对于计算机视觉和其他应用，可以是传统的基于RANSAC的方法的有用甚至更好的替代方案。

##### URL
[http://arxiv.org/abs/1510.04390](http://arxiv.org/abs/1510.04390)

##### PDF
[http://arxiv.org/pdf/1510.04390](http://arxiv.org/pdf/1510.04390)

