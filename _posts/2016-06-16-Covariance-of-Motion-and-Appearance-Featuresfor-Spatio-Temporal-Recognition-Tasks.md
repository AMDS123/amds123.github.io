---
layout: post
title: "Covariance of Motion and Appearance Featuresfor Spatio Temporal Recognition Tasks"
date: 2016-06-16 20:01:13
categories: arXiv_CV
tags: arXiv_CV Sparse Recognition
author: Subhabrata Bhattacharya, Nasim Souly, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce an end-to-end framework for video analysis focused towards practical scenarios built on theoretical foundations from sparse representation, including a novel descriptor for general purpose video analysis. In our approach, we compute kinematic features from optical flow and first and second-order derivatives of intensities to represent motion and appearance respectively. These features are then used to construct covariance matrices which capture joint statistics of both low-level motion and appearance features extracted from a video. Using an over-complete dictionary of the covariance based descriptors built from labeled training samples, we formulate low-level event recognition as a sparse linear approximation problem. Within this, we pose the sparse decomposition of a covariance matrix, which also conforms to the space of semi-positive definite matrices, as a determinant maximization problem. Also since covariance matrices lie on non-linear Riemannian manifolds, we compare our former approach with a sparse linear approximation alternative that is suitable for equivalent vector spaces of covariance matrices. This is done by searching for the best projection of the query data on a dictionary using an Orthogonal Matching pursuit algorithm. We show the applicability of our video descriptor in two different application domains - namely low-level event recognition in unconstrained scenarios and gesture recognition using one shot learning. Our experiments provide promising insights in large scale video analysis.

##### Abstract (translated by Google)
在本文中，我们介绍了一个端到端的视频分析框架，重点放在基于稀疏表示的理论基础上的实际场景，包括一个用于通用视频分析的新颖描述符。在我们的方法中，我们从光流和强度的一阶和二阶导数计算运动学特征，分别代表运动和外观。然后使用这些特征来构造协方差矩阵，其捕获从视频中提取的低级运动和外观特征的联合统计。使用基于标记训练样本的基于协方差的描述符的完整字典，我们将低级别事件识别作为稀疏线性逼近问题。在这个范围内，我们把一个协方差矩阵的稀疏分解，也符合半正定矩阵的空间，作为一个行列式最大化问题。另外，由于协方差矩阵位于非线性黎曼流形上，因此我们将前一种方法与适合于协方差矩阵的等价向量空间的稀疏线性逼近方法进行比较。这是通过使用正交匹配追踪算法在字典中搜索查询数据的最佳投影来完成的。我们展示了我们的视频描述符在两个不同的应用领域中的适用性 - 即在无约束场景下的低级别事件识别和使用一次性学习的手势识别。我们的实验为大规模视频分析提供了有希望的见解

##### URL
[https://arxiv.org/abs/1606.05355](https://arxiv.org/abs/1606.05355)

##### PDF
[https://arxiv.org/pdf/1606.05355](https://arxiv.org/pdf/1606.05355)

