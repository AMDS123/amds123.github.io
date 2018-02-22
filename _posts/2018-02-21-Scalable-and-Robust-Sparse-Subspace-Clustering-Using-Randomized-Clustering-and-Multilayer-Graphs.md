---
layout: post
title: "Scalable and Robust Sparse Subspace Clustering Using Randomized Clustering and Multilayer Graphs"
date: 2018-02-21 16:21:42
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation
author: Maryam Abdolali, Nicolas Gillis, Mohammad Rahmati
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse subspace clustering (SSC) is one of the current state-of-the-art method for partitioning data points into the union of subspaces, with strong theoretical guarantees. However, it is not practical for large data sets as it requires solving a LASSO problem for each data point, where the number of variables in each LASSO problem is the number of data points. To improve the scalability of SSC, we propose to select a few sets of anchor points using a randomized hierarchical clustering method, and, for each set of anchor points, solve the LASSO problems for each data point allowing only anchor points to have a non-zero weight (this reduces drastically the number of variables). This generates a multilayer graph where each layer corresponds to a different set of anchor points. Using the Grassmann manifold of orthogonal matrices, the shared connectivity among the layers is summarized within a single subspace. Finally, we use $k$-means clustering within that subspace to cluster the data points, similarly as done by spectral clustering in SSC. We show on both synthetic and real-world data sets that the proposed method not only allows SSC to scale to large-scale data sets, but that it is also much more robust as it performs significantly better on noisy data and on data with close susbspaces and outliers, while it is not prone to oversegmentation.

##### Abstract (translated by Google)
稀疏子空间聚类（SSC）是当前最先进的将数据点划分为子空间联合的方法之一，具有强大的理论保证。然而，对于大数据集来说这是不实际的，因为它需要为每个数据点解决LASSO问题，其中每个LASSO问题中的变量数量是数据点的数量。为了提高SSC的可扩展性，我们建议使用随机化分层聚类方法来选择几组锚点，并且对于每组锚点，解决每个数据点的LASSO问题，只允许锚点具有非锚点，零重量（这大大减少了变量的数量）。这会生成一个多层图，其中每个图层对应一组不同的锚点。使用正交矩阵的格拉斯曼流形，在单个子空间内汇总层间的共享连接。最后，我们在该子空间内使用$ k $ -means聚类来聚类数据点，就像SSC中的谱聚类所做的那样。我们在合成和现实世界的数据集上都展示了所提出的方法不仅可以使SSC扩展到大规模数据集，而且它还更加稳健，因为它对噪声数据和具有接近可疑空间的数据和异常值，虽然它不容易过度调整。

##### URL
[http://arxiv.org/abs/1802.07648](http://arxiv.org/abs/1802.07648)

##### PDF
[http://arxiv.org/pdf/1802.07648](http://arxiv.org/pdf/1802.07648)

