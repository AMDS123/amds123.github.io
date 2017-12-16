---
layout: post
title: "Self-Similarity Based Time Warping"
date: 2017-11-20 19:43:28
categories: arXiv_CV
tags: arXiv_CV
author: Christopher J. Tralie
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we explore the problem of aligning two time-ordered point clouds which are spatially transformed and re-parameterized versions of each other. This has a diverse array of applications such as cross modal time series synchronization (e.g. MOCAP to video) and alignment of discretized curves in images. Most other works that address this problem attempt to jointly uncover a spatial alignment and correspondences between the two point clouds, or to derive local invariants to spatial transformations such as curvature before computing correspondences. By contrast, we sidestep spatial alignment completely by using self-similarity matrices (SSMs) as a proxy to the time-ordered point clouds, since self-similarity matrices are blind to isometries and respect global geometry. Our algorithm, dubbed "Isometry Blind Dynamic Time Warping" (IBDTW), is simple and general, and we show that its associated dissimilarity measure lower bounds the L1 Gromov-Hausdorff distance between the two point sets when restricted to warping paths. We also present a local, partial alignment extension of IBDTW based on the Smith Waterman algorithm. This eliminates the need for tedious manual cropping of time series, which is ordinarily necessary for global alignment algorithms to function properly.

##### Abstract (translated by Google)
在这项工作中，我们探讨了对齐两个时间有序的点云的问题，这些点云是空间变换的，并且是相互重新参数化的版本。这具有多种应用，例如交叉模式时间序列同步（例如MOCAP到视频）以及图像中离散化曲线的对齐。解决这个问题的大多数其他作品试图共同揭示两个点云之间的空间对齐和对应关系，或者在计算对应关系之前导出局部不变量以进行空间转换，例如曲率。相比之下，由于自相似矩阵对等距线是盲的并且尊重全局几何，所以我们使用自相似矩阵（SSM）作为时间有序的点云的代理，完全避开空间对准。我们的算法被称为“等距盲动态时间翘曲”（IBDTW），它是简单而通用的，并且当被限制在翘曲路径中时，其相关的相异度度量下限两点集合之间的L1格罗莫夫 - 豪斯道夫距离。我们还提出了基于Smith Waterman算法的IBDTW的局部对齐扩展。这消除了对时间序列进行繁琐的手动裁剪的需要，这对于全局对齐算法正常运行通常是必需的。

##### URL
[https://arxiv.org/abs/1711.07513](https://arxiv.org/abs/1711.07513)

##### PDF
[https://arxiv.org/pdf/1711.07513](https://arxiv.org/pdf/1711.07513)

