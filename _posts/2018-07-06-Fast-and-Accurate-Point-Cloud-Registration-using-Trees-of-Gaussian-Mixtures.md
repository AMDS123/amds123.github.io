---
layout: post
title: "Fast and Accurate Point Cloud Registration using Trees of Gaussian Mixtures"
date: 2018-07-06 23:44:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization SLAM Recognition
author: Ben Eckart, Kihwan Kim, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Point cloud registration sits at the core of many important and challenging 3D perception problems including autonomous navigation, SLAM, object/scene recognition, and augmented reality. In this paper, we present a new registration algorithm that is able to achieve state-of-the-art speed and accuracy through its use of a hierarchical Gaussian Mixture Model (GMM) representation. Our method constructs a top-down multi-scale representation of point cloud data by recursively running many small-scale data likelihood segmentations in parallel on a GPU. We leverage the resulting representation using a novel PCA-based optimization criterion that adaptively finds the best scale to perform data association between spatial subsets of point cloud data. Compared to previous Iterative Closest Point and GMM-based techniques, our tree-based point association algorithm performs data association in logarithmic-time while dynamically adjusting the level of detail to best match the complexity and spatial distribution characteristics of local scene geometry. In addition, unlike other GMM methods that restrict covariances to be isotropic, our new PCA-based optimization criterion well-approximates the true MLE solution even when fully anisotropic Gaussian covariances are used. Efficient data association, multi-scale adaptability, and a robust MLE approximation produce an algorithm that is up to an order of magnitude both faster and more accurate than current state-of-the-art on a wide variety of 3D datasets captured from LiDAR to structured light.

##### Abstract (translated by Google)
点云注册是许多重要且具有挑战性的3D感知问题的核心，包括自主导航，SLAM，对象/场景识别和增强现实。在本文中，我们提出了一种新的配准算法，它能够通过使用分层高斯混合模型（GMM）表示来实现最先进的速度和准确性。我们的方法通过在GPU上并行递归地运行许多小规模数据似然分段来构建点云数据的自上而下的多尺度表示。我们利用基于PCA的新颖优化标准来利用所得到的表示，该标准自适应地找到用于在点云数据的空间子集之间执行数据关联的最佳比例。与先前的迭代最近点和基于GMM的技术相比，我们的基于树的点关联算法以对数时间执行数据关联，同时动态调整细节水平以最佳地匹配局部场景几何的复杂性和空间分布特征。此外，与将协方差限制为各向同性的其他GMM方法不同，即使使用完全各向异性的高斯协方差，我们新的基于PCA的优化准则也能很好地逼近真正的MLE解决方案。高效的数据关联，多尺度适应性和强大的MLE近似产生了一种算法，该算法比从LiDAR捕获的各种3D数据集中的当前最先进技术更快且更准确地达到一个数量级。结构光。

##### URL
[http://arxiv.org/abs/1807.02587](http://arxiv.org/abs/1807.02587)

##### PDF
[http://arxiv.org/pdf/1807.02587](http://arxiv.org/pdf/1807.02587)

