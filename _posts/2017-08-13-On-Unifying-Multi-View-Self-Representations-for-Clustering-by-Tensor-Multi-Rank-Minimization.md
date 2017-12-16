---
layout: post
title: "On Unifying Multi-View Self-Representations for Clustering by Tensor Multi-Rank Minimization"
date: 2017-08-13 16:50:01
categories: arXiv_CV
tags: arXiv_CV Relation
author: Yuan Xie, Dacheng Tao, Wensheng Zhang, Lei Zhang, Yan Liu, Yanyun Qu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the multi-view subspace clustering problem. Our method utilizes the circulant algebra for tensor, which is constructed by stacking the subspace representation matrices of different views and then rotating, to capture the low rank tensor subspace so that the refinement of the view-specific subspaces can be achieved, as well as the high order correlations underlying multi-view data can be explored.} By introducing a recently proposed tensor factorization, namely tensor-Singular Value Decomposition (t-SVD) \cite{kilmer13}, we can impose a new type of low-rank tensor constraint on the rotated tensor to capture the complementary information from multiple views. Different from traditional unfolding based tensor norm, this low-rank tensor constraint has optimality properties similar to that of matrix rank derived from SVD, so the complementary information among views can be explored more efficiently and thoroughly. The established model, called t-SVD based Multi-view Subspace Clustering (t-SVD-MSC), falls into the applicable scope of augmented Lagrangian method, and its minimization problem can be efficiently solved with theoretical convergence guarantee and relatively low computational complexity. Extensive experimental testing on eight challenging image dataset shows that the proposed method has achieved highly competent objective performance compared to several state-of-the-art multi-view clustering methods.

##### Abstract (translated by Google)
在本文中，我们解决了多视图子空间聚类问题。我们的方法利用张量的循环代数，它是通过叠加不同视图的子空间表示矩阵，然后旋转来捕获低秩张量子空间，从而可以实现视图特定的子空间的细化，以及通过引入最近提出的张量分解，即张量 - 奇异值分解（t-SVD）\ cite {kilmer13}，我们可以施加一种新的低秩张量约束在旋转的张量上捕捉来自多个视图的补充信息。与传统的基于张量的张量规范不同，这种低秩张量约束具有与SVD矩阵秩相似的最优性质，可以更加有效地探索视图间的互补信息。所建立的基于t-SVD的多视图子空间聚类算法（t-SVD-MSC）属于增广拉格朗日方法的适用范围，其理论收敛性和计算复杂度相对较低，可以有效解决其最小化问题。对8个具有挑战性的图像数据集进行广泛的实验测试表明，与几种最先进的多视图聚类方法相比，所提出的方法已经实现了非常胜任的客观性能。

##### URL
[https://arxiv.org/abs/1610.07126](https://arxiv.org/abs/1610.07126)

##### PDF
[https://arxiv.org/pdf/1610.07126](https://arxiv.org/pdf/1610.07126)

