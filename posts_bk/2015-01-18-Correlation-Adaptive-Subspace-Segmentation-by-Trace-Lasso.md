---
layout: post
title: "Correlation Adaptive Subspace Segmentation by Trace Lasso"
date: 2015-01-18 10:02:25
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Segmentation Relation
author: Canyi Lu, Jiashi Feng, Zhouchen Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the subspace segmentation problem. Given a set of data points drawn from a union of subspaces, the goal is to partition them into their underlying subspaces they were drawn from. The spectral clustering method is used as the framework. It requires to find an affinity matrix which is close to block diagonal, with nonzero entries corresponding to the data point pairs from the same subspace. In this work, we argue that both sparsity and the grouping effect are important for subspace segmentation. A sparse affinity matrix tends to be block diagonal, with less connections between data points from different subspaces. The grouping effect ensures that the highly corrected data which are usually from the same subspace can be grouped together. Sparse Subspace Clustering (SSC), by using $\ell^1$-minimization, encourages sparsity for data selection, but it lacks of the grouping effect. On the contrary, Low-Rank Representation (LRR), by rank minimization, and Least Squares Regression (LSR), by $\ell^2$-regularization, exhibit strong grouping effect, but they are short in subset selection. Thus the obtained affinity matrix is usually very sparse by SSC, yet very dense by LRR and LSR. In this work, we propose the Correlation Adaptive Subspace Segmentation (CASS) method by using trace Lasso. CASS is a data correlation dependent method which simultaneously performs automatic data selection and groups correlated data together. It can be regarded as a method which adaptively balances SSC and LSR. Both theoretical and experimental results show the effectiveness of CASS.

##### Abstract (translated by Google)
本文研究子空间分割问题。给定从子空间联合中抽取的一组数据点，其目标是将它们划分为它们从中抽取的底层子空间。谱聚类方法被用作框架。它需要找到一个接近于块对角线的亲和矩阵，其中非零项对应于来自相同子空间的数据点对。在这项工作中，我们认为稀疏性和分组效应对于子空间分割是重要的。稀疏亲和度矩阵往往是块对角线，来自不同子空间的数据点之间的连接较少。分组效应确保通常来自相同子空间的高度校正的数据可以分组在一起。通过使用$ \ ell ^ 1 $ -minimization，稀疏子空间聚类（SSC）鼓励稀疏数据选择，但缺乏分组效果。相反，通过秩最小化和最小二乘回归（LSR）的低秩表示（LRR）表现出强的分组效应，但是它们在子集选择上是短的。因此，获得的亲和矩阵通常是SSC非常稀疏的，而LRR和LSR非常密集。在这项工作中，我们提出使用跟踪套索的相关自适应子空间分割（CASS）方法。 CASS是一种数据相关性依赖方法，它同时执行自动数据选择并将相关数据组合在一起。它可以被认为是自适应平衡SSC和LSR的一种方法。理论和实验结果都显示了CASS的有效性。

##### URL
[https://arxiv.org/abs/1501.04276](https://arxiv.org/abs/1501.04276)

##### PDF
[https://arxiv.org/pdf/1501.04276](https://arxiv.org/pdf/1501.04276)

