---
layout: post
title: "Motion Segmentation via Global and Local Sparse Subspace Optimization"
date: 2017-01-24 15:49:53
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Optimization
author: Michael Ying Yang, Hanno Ackermann, Weiyao Lin, Sitong Feng, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new framework for segmenting feature-based moving objects under affine subspace model. Since the feature trajectories in practice are high-dimensional and contain a lot of noise, we firstly apply the sparse PCA to represent the original trajectories with a low-dimensional global subspace, which consists of the orthogonal sparse principal vectors. Subsequently, the local subspace separation will be achieved via automatically searching the sparse representation of the nearest neighbors for each projected data. In order to refine the local subspace estimation result and deal with the missing data problem, we propose an error estimation to encourage the projected data that span a same local subspace to be clustered together. In the end, the segmentation of different motions is achieved through the spectral clustering on an affinity matrix, which is constructed with both the error estimation and sparse neighbors optimization. We test our method extensively and compare it with state-of-the-art methods on the Hopkins 155 dataset and Freiburg-Berkeley Motion Segmentation dataset. The results show that our method is comparable with the other motion segmentation methods, and in many cases exceed them in terms of precision and computation time.

##### Abstract (translated by Google)
本文提出了一种仿射子空间模型下的基于特征的运动目标分割新框架。由于实际中的特征轨迹是高维的并且含有大量的噪声，我们首先应用稀疏PCA来表示具有低维全局子空间的原始轨迹，其由正交稀疏主矢量组成。随后，通过自动搜索每个投影数据的最近邻居的稀疏表示来实现局部子空间分离。为了改进局部子空间估计结果并处理丢失的数据问题，我们提出了一种误差估计来鼓励跨同一个局部子空间的投影数据聚集在一起。最后，通过在亲和矩阵上进行谱聚类，实现不同运动的分割，同时构建误差估计和稀疏邻域优化。我们广泛测试我们的方法，并将其与霍普金斯155数据集和弗莱堡伯克利运动分割数据集中的最新方法进行比较。结果表明，我们的方法与其他运动分割方法相比，在许多情况下超过精度和计算时间。

##### URL
[https://arxiv.org/abs/1701.06944](https://arxiv.org/abs/1701.06944)

##### PDF
[https://arxiv.org/pdf/1701.06944](https://arxiv.org/pdf/1701.06944)

