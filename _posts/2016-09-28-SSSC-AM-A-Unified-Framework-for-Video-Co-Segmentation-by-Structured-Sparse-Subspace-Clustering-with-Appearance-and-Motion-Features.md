---
layout: post
title: "SSSC-AM: A Unified Framework for Video Co-Segmentation by Structured Sparse Subspace Clustering with Appearance and Motion Features"
date: 2016-09-28 22:05:15
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation
author: Junlin Yao, Frank Nielsen
mathjax: true
---

* content
{:toc}

##### Abstract
Video co-segmentation refers to the task of jointly segmenting common objects appearing in a given group of videos. In practice, high-dimensional data such as videos can be conceptually thought as being drawn from a union of subspaces corresponding to categories rather than from a smooth manifold. Therefore, segmenting data into respective subspaces --- subspace clustering --- finds widespread applications in computer vision, including co-segmentation. State-of-the-art methods via subspace clustering seek to solve the problem in two steps: First, an affinity matrix is built from data, with appearance features or motion patterns. Second, the data are segmented by applying spectral clustering to the affinity matrix. However, this process is insufficient to obtain an optimal solution since it does not take into account the {\em interdependence} of the affinity matrix with the segmentation. In this work, we present a novel unified video co-segmentation framework inspired by the recent Structured Sparse Subspace Clustering ($\mathrm{S^{3}C}$) based on the {\em self-expressiveness} model. Our method yields more consistent segmentation results. In order to improve the detectability of motion features with missing trajectories due to occlusion or tracked points moving out of frames, we add an extra-dimensional signature to the motion trajectories. Moreover, we reformulate the $\mathrm{S^{3}C}$ algorithm by adding the affine subspace constraint in order to make it more suitable to segment rigid motions lying in affine subspaces of dimension at most $3$. Our experiments on MOViCS dataset show that our framework achieves the highest overall performance among baseline algorithms and demonstrate its robustness to heavy noise.

##### Abstract (translated by Google)
视频协同分割是指共同分割出现在一组给定视频中的公共对象的任务。在实践中，视频等高维数据在概念上可以认为是从对应于类别的子空间的并集中抽取的，而不是从光滑的流形。因此，将数据分割成各子空间 - 子空间聚类 - 在计算机视觉中广泛应用，包括协同分割。通过子空间聚类的最先进的方法试图通过两个步骤来解决问题：首先，从数据建立亲和矩阵，具有外观特征或运动模式。其次，通过将谱聚类应用于亲和度矩阵来分割数据。然而，这个过程不足以获得最佳的解决方案，因为它不考虑亲和矩阵与分割的相互依赖性。在这项工作中，我们基于{\ em自我表现}模型提出了一种新的统一视频协同分割框架，这个框架受到最近的结构化稀疏子空间聚类（$ \ mathrm {S ^ {3} C} $）的启发。我们的方法产生更一致的分割结果。为了改善由于遮挡或跟踪点移出帧而导致轨迹遗漏的运动特征的可检测性，我们在运动轨迹上添加了额外的维度签名。此外，我们通过添加仿射子空间约束来重新构造$ \ mathrm {S ^ {3} C} $算法，以使其更适合于分割位于维度至多$ 3 $的仿射子空间中的刚性运动。我们在MOViCS数据集上的实验表明，我们的框架在基准算法中达到了最高的整体性能，并证明了它对强噪声的鲁棒性。

##### URL
[https://arxiv.org/abs/1603.04139](https://arxiv.org/abs/1603.04139)

##### PDF
[https://arxiv.org/pdf/1603.04139](https://arxiv.org/pdf/1603.04139)

