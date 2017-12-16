---
layout: post
title: "Structured Sparse Subspace Clustering: A Joint Affinity Learning and Subspace Clustering Framework"
date: 2017-04-05 14:22:11
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Optimization
author: Chun-Guang Li, Chong You, René Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
Subspace clustering refers to the problem of segmenting data drawn from a union of subspaces. State-of-the-art approaches for solving this problem follow a two-stage approach. In the first step, an affinity matrix is learned from the data using sparse or low-rank minimization techniques. In the second step, the segmentation is found by applying spectral clustering to this affinity. While this approach has led to state-of-the-art results in many applications, it is sub-optimal because it does not exploit the fact that the affinity and the segmentation depend on each other. In this paper, we propose a joint optimization framework --- Structured Sparse Subspace Clustering (S$^3$C) --- for learning both the affinity and the segmentation. The proposed S$^3$C framework is based on expressing each data point as a structured sparse linear combination of all other data points, where the structure is induced by a norm that depends on the unknown segmentation. Moreover, we extend the proposed S$^3$C framework into Constrained Structured Sparse Subspace Clustering (CS$^3$C) in which available partial side-information is incorporated into the stage of learning the affinity. We show that both the structured sparse representation and the segmentation can be found via a combination of an alternating direction method of multipliers with spectral clustering. Experiments on a synthetic data set, the Extended Yale B data set, the Hopkins 155 motion segmentation database, and three cancer data sets demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)
子空间聚类是指从子空间联合中抽取数据的分段问题。用于解决这个问题的最新方法采用两阶段方法。在第一步中，使用稀疏或低秩最小化技术从数据中学习亲和度矩阵。在第二步中，通过将谱聚类应用于该亲和性来发现分割。虽然这种方法已经在许多应用中导致了最先进的结果，但是它不是最优的，因为它不利用亲和性和分割相互依赖的事实。在本文中，我们提出了一个联合优化框架---结构化稀疏子空间聚类（S $ ^ 3 $ C）---学习亲和力和分割。提出的S $ ^ $ C框架是基于将每个数据点表示为所有其他数据点的结构化稀疏线性组合，其中该结构由取决于未知分割的规范引起。此外，我们将提出的S $ ^ 3 $ C框架扩展到约束结构稀疏子空间聚类（CS $ ^ 3 $ C），其中可用的部分边信息被纳入学习亲和度的阶段。我们表明，结构化稀疏表示和分割都可以通过乘法器交替方向的方法与谱聚类的组合来找到。在一个合成的数据集，扩展耶鲁B数据集，霍普金斯155运动分割数据库和三个癌症数据集的实验证明了我们的方法的有效性。

##### URL
[https://arxiv.org/abs/1610.05211](https://arxiv.org/abs/1610.05211)

##### PDF
[https://arxiv.org/pdf/1610.05211](https://arxiv.org/pdf/1610.05211)

