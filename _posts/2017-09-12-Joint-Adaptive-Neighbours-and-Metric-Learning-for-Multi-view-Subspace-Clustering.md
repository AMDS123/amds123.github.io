---
layout: post
title: "Joint Adaptive Neighbours and Metric Learning for Multi-view Subspace Clustering"
date: 2017-09-12 02:09:29
categories: arXiv_CV
tags: arXiv_CV Attention Optimization
author: Nan Xu, Yanqing Guo, Jiujun Wang, Xiangyang Luo, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the existence of various views or representations in many real-world data, multi-view learning has drawn much attention recently. Multi-view spectral clustering methods based on similarity matrixes or graphs are pretty popular. Generally, these algorithms learn informative graphs by directly utilizing original data. However, in the real-world applications, original data often contain noises and outliers that lead to unreliable graphs. In addition, different views may have different contributions to data clustering. In this paper, a novel Multiview Subspace Clustering method unifying Adaptive neighbours and Metric learning (MSCAM), is proposed to address the above problems. In this method, we use the subspace representations of different views to adaptively learn a consensus similarity matrix, uncovering the subspace structure and avoiding noisy nature of original data. For all views, we also learn different Mahalanobis matrixes that parameterize the squared distances and consider the contributions of different views. Further, we constrain the graph constructed by the similarity matrix to have exact c (c is the number of clusters) connected components. An iterative algorithm is developed to solve this optimization problem. Moreover, experiments on a synthetic dataset and different real-world datasets demonstrate the effectiveness of MSCAM.

##### Abstract (translated by Google)
由于许多现实世界的数据中存在各种不同的观点或表征，多视角学习近来备受关注。基于相似矩阵或图的多视图谱聚类方法非常流行。通常，这些算法通过直接利用原始数据来学习信息图。但是，在现实世界的应用程序中，原始数据通常包含噪声和异常值，从而导致不可靠的图形。另外，不同的观点可能对数据聚类有不同的贡献。为了解决上述问题，本文提出了一种统一自适应邻居和度量学习（MSCAM）的多视点子空间聚类方法。在这种方法中，我们使用不同视图的子空间表示来自适应学习共识相似矩阵，揭示子空间结构，避免原始数据的噪声性质。对于所有的观点，我们也学习不同的Mahalanobis矩阵参数化平方距离，并考虑不同视图的贡献。进一步，我们限制由相似度矩阵构造的图具有确切的c（c是簇的数量）连通分量。迭代算法被开发来解决这个优化问题。此外，对合成数据集和不同实际数据集的实验证明了MSCAM的有效性。

##### URL
[https://arxiv.org/abs/1709.03656](https://arxiv.org/abs/1709.03656)

##### PDF
[https://arxiv.org/pdf/1709.03656](https://arxiv.org/pdf/1709.03656)

