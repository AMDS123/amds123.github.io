---
layout: post
title: "Geometry-Aware Neighborhood Search for Learning Local Models for Image Reconstruction"
date: 2016-01-05 13:37:40
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse
author: Julio Cesar Ferreira, Elif Vural, Christine Guillemot
mathjax: true
---

* content
{:toc}

##### Abstract
Local learning of sparse image models has proven to be very effective to solve inverse problems in many computer vision applications. To learn such models, the data samples are often clustered using the K-means algorithm with the Euclidean distance as a dissimilarity metric. However, the Euclidean distance may not always be a good dissimilarity measure for comparing data samples lying on a manifold. In this paper, we propose two algorithms for determining a local subset of training samples from which a good local model can be computed for reconstructing a given input test sample, where we take into account the underlying geometry of the data. The first algorithm, called Adaptive Geometry-driven Nearest Neighbor search (AGNN), is an adaptive scheme which can be seen as an out-of-sample extension of the replicator graph clustering method for local model learning. The second method, called Geometry-driven Overlapping Clusters (GOC), is a less complex nonadaptive alternative for training subset selection. The proposed AGNN and GOC methods are evaluated in image super-resolution, deblurring and denoising applications and shown to outperform spectral clustering, soft clustering, and geodesic distance based subset selection in most settings.

##### Abstract (translated by Google)
在许多计算机视觉应用中，稀疏图像模型的局部学习已被证明是非常有效的解决逆向问题。为了学习这些模型，数据样本通常使用具有欧几里得距离的K均值算法作为不相似度量来聚类。然而，欧几里德距离可能并不总是一个很好的不相似的措施，比较数据样本上的多样性。在本文中，我们提出了两种算法来确定训练样本的局部子集，从中可以计算好的局部模型来重建给定的输入测试样本，其中我们考虑数据的基本几何形状。第一种算法叫做自适应几何驱动最近邻搜索（Adaptive Geometry-driven Nearest Neighbor，AGNN），是一种自适应方案，可以看作是局部模型学习的复制图聚类方法的一个扩展。第二种方法，称为几何驱动重叠群（GOC），是一种较不复杂的非适应性训练子集的选择。所提出的AGNN和GOC方法在图像超分辨率，去模糊和去噪应用中进行评估，并且在大多数设置中被示出优于谱聚类，软聚类和基于测地距离的子集选择。

##### URL
[https://arxiv.org/abs/1505.01429](https://arxiv.org/abs/1505.01429)

##### PDF
[https://arxiv.org/pdf/1505.01429](https://arxiv.org/pdf/1505.01429)

