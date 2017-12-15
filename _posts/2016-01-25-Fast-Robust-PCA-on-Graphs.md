---
layout: post
title: "Fast Robust PCA on Graphs"
date: 2016-01-25 20:29:57
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Recognition
author: Nauman Shahid, Nathanael Perraudin, Vassilis Kalofolias, Gilles Puy, Pierre Vandergheynst
mathjax: true
---

* content
{:toc}

##### Abstract
Mining useful clusters from high dimensional data has received significant attention of the computer vision and pattern recognition community in the recent years. Linear and non-linear dimensionality reduction has played an important role to overcome the curse of dimensionality. However, often such methods are accompanied with three different problems: high computational complexity (usually associated with the nuclear norm minimization), non-convexity (for matrix factorization methods) and susceptibility to gross corruptions in the data. In this paper we propose a principal component analysis (PCA) based solution that overcomes these three issues and approximates a low-rank recovery method for high dimensional datasets. We target the low-rank recovery by enforcing two types of graph smoothness assumptions, one on the data samples and the other on the features by designing a convex optimization problem. The resulting algorithm is fast, efficient and scalable for huge datasets with O(nlog(n)) computational complexity in the number of data samples. It is also robust to gross corruptions in the dataset as well as to the model parameters. Clustering experiments on 7 benchmark datasets with different types of corruptions and background separation experiments on 3 video datasets show that our proposed model outperforms 10 state-of-the-art dimensionality reduction models. Our theoretical analysis proves that the proposed model is able to recover approximate low-rank representations with a bounded error for clusterable data.

##### Abstract (translated by Google)
从高维数据中挖掘有用的集群近年来受到计算机视觉和模式识别界的重视。线性和非线性降维对克服维数灾难起到了重要作用。然而，这些方法通常伴随着三个不同的问题：高计算复杂性（通常与核范数最小化有关），非凸性（用于矩阵分解方法）以及数据中严重腐败的易感性。在本文中，我们提出了一个基于主成分分析（PCA）的解决方案，克服了这三个问题，并近似低维数据集的恢复方法。我们通过执行两种图平滑假设来设计低级恢复，一种是数据样本，另一种是设计凸优化问题。所得到的算法对于在数据采样数量上具有O（nlog（n））计算复杂度的大数据集是快速，高效和可扩展的。对于数据集中的严重腐败以及模型参数也是强有力的。对7个具有不同类型损坏的基准数据集和3个视频数据集上的背景分离实验进行聚类实验表明，我们提出的模型胜过了10个最新的降维模型。我们的理论分析证明，所提出的模型能够为可分簇数据恢复具有有界误差的近似低秩表示。

##### URL
[https://arxiv.org/abs/1507.08173](https://arxiv.org/abs/1507.08173)

##### PDF
[https://arxiv.org/pdf/1507.08173](https://arxiv.org/pdf/1507.08173)

