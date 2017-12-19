---
layout: post
title: "3D Scan Registration using Curvelet Features in Planetary Environments"
date: 2015-09-23 17:51:03
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge
author: Siddhant Ahuja, Peter Iles, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
Topographic mapping in planetary environments relies on accurate 3D scan registration methods. However, most global registration algorithms relying on features such as FPFH and Harris-3D show poor alignment accuracy in these settings due to the poor structure of the Mars-like terrain and variable resolution, occluded, sparse range data that is hard to register without some a-priori knowledge of the environment. In this paper, we propose an alternative approach to 3D scan registration using the curvelet transform that performs multi-resolution geometric analysis to obtain a set of coefficients indexed by scale (coarsest to finest), angle and spatial position. Features are detected in the curvelet domain to take advantage of the directional selectivity of the transform. A descriptor is computed for each feature by calculating the 3D spatial histogram of the image gradients, and nearest neighbor based matching is used to calculate the feature correspondences. Correspondence rejection using Random Sample Consensus identifies inliers, and a locally optimal Singular Value Decomposition-based estimation of the rigid-body transformation aligns the laser scans given the re-projected correspondences in the metric space. Experimental results on a publicly available data-set of planetary analogue indoor facility, as well as simulated and real-world scans from Neptec Design Group's IVIGMS 3D laser rangefinder at the outdoor CSA Mars yard demonstrates improved performance over existing methods in the challenging sparse Mars-like terrain.

##### Abstract (translated by Google)
行星环境中的地形测绘依赖于准确的三维扫描注册方法。然而，大多数依赖于FPFH和Harris-3D等特征的全局配准算法由于火星状地形的结构不良和可变分辨率，在这些设置中的对准精度较差，因此如果没有一些难以注册的稀疏范围数据对环境的先验知识。在本文中，我们提出了一种三维扫描注册的替代方法，使用曲波变换进行多分辨率几何分析，以获得按比例（最粗到最好），角度和空间位置索引的一组系数。在curvelet域中检测特征以利用变换的方向选择性。通过计算图像梯度的3D空间直方图来计算每个特征的描述符，并且使用基于最近邻的匹配来计算特征对应。使用随机样本共识的对应拒绝标识内点，并且基于局部最优的基于奇异值分解的刚体变换的估计对准给定度量空间中的再投影对应的激光扫描。行星模拟室内设施的公开数据集的实验结果以及Neptec Design Group的室外CSA火星场的IVIGMS 3D激光测距仪的模拟和现实扫描，证明了在具有挑战性的稀疏Mars-像地形一样。

##### URL
[https://arxiv.org/abs/1509.07075](https://arxiv.org/abs/1509.07075)

##### PDF
[https://arxiv.org/pdf/1509.07075](https://arxiv.org/pdf/1509.07075)

