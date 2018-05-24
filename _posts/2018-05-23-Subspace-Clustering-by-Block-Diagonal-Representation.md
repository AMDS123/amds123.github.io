---
layout: post
title: "Subspace Clustering by Block Diagonal Representation"
date: 2018-05-23 15:58:34
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Canyi Lu, Jiashi Feng, Zhouchen Lin, Tao Mei, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the subspace clustering problem. Given some data points approximately drawn from a union of subspaces, the goal is to group these data points into their underlying subspaces. Many subspace clustering methods have been proposed and among which sparse subspace clustering and low-rank representation are two representative ones. Despite the different motivations, we observe that many existing methods own the common block diagonal property, which possibly leads to correct clustering, yet with their proofs given case by case. In this work, we consider a general formulation and provide a unified theoretical guarantee of the block diagonal property. The block diagonal property of many existing methods falls into our special case. Second, we observe that many existing methods approximate the block diagonal representation matrix by using different structure priors, e.g., sparsity and low-rankness, which are indirect. We propose the first block diagonal matrix induced regularizer for directly pursuing the block diagonal matrix. With this regularizer, we solve the subspace clustering problem by Block Diagonal Representation (BDR), which uses the block diagonal structure prior. The BDR model is nonconvex and we propose an alternating minimization solver and prove its convergence. Experiments on real datasets demonstrate the effectiveness of BDR.

##### Abstract (translated by Google)
本文研究子空间聚类问题。给定从子空间联合近似得到的一些数据点，目标是将这些数据点分组到它们的基础子空间中。许多子空间聚类方法已经被提出，其中稀疏子空间聚类和低秩表示是两个有代表性的子空间聚类方法。尽管存在不同的动机，但我们观察到许多现有的方法都具有常见的块对角属性，这可能导致正确的聚类，然而它们的证明是逐个给出的。在这项工作中，我们考虑一个通用公式，并提供块对角线属性的统一理论保证。许多现有方法的块对角线属性属于我们的特例。其次，我们观察到许多现有的方法通过使用不同的结构先验来近似块对角线表示矩阵，例如，稀疏性和低秩度是间接的。我们提出了第一个块对角矩阵诱导正则化器直接追踪块对角矩阵。使用这个正则化器，我们通过块对角线表示法（BDR）解决了子空间聚类问题，其中使用了块对角线结构。 BDR模型是非凸的，我们提出了交替最小化求解器并证明了它的收敛性。真实数据集上的实验证明了BDR的有效性。

##### URL
[http://arxiv.org/abs/1805.09243](http://arxiv.org/abs/1805.09243)

##### PDF
[http://arxiv.org/pdf/1805.09243](http://arxiv.org/pdf/1805.09243)

