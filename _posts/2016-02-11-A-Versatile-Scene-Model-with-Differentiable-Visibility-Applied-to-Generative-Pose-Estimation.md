---
layout: post
title: "A Versatile Scene Model with Differentiable Visibility Applied to Generative Pose Estimation"
date: 2016-02-11 13:49:25
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation Optimization
author: Helge Rhodin, Nadia Robertini, Christian Richardt, Hans-Peter Seidel, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
Generative reconstruction methods compute the 3D configuration (such as pose and/or geometry) of a shape by optimizing the overlap of the projected 3D shape model with images. Proper handling of occlusions is a big challenge, since the visibility function that indicates if a surface point is seen from a camera can often not be formulated in closed form, and is in general discrete and non-differentiable at occlusion boundaries. We present a new scene representation that enables an analytically differentiable closed-form formulation of surface visibility. In contrast to previous methods, this yields smooth, analytically differentiable, and efficient to optimize pose similarity energies with rigorous occlusion handling, fewer local minima, and experimentally verified improved convergence of numerical optimization. The underlying idea is a new image formation model that represents opaque objects by a translucent medium with a smooth Gaussian density distribution which turns visibility into a smooth phenomenon. We demonstrate the advantages of our versatile scene model in several generative pose estimation problems, namely marker-less multi-object pose estimation, marker-less human motion capture with few cameras, and image-based 3D geometry estimation.

##### Abstract (translated by Google)
生成重建方法通过优化投影3D形状模型与图像的重叠来计算形状的3D配置（例如姿态和/或几何形状）。正确处理遮挡是一个很大的挑战，因为指示从照相机看到的表面点的可见性函数常常不能以闭合形式来表示，并且在遮挡边界处一般是离散的和不可微分的。我们提出了一个新的场景表示，使表面可视性的分析可微闭合形式的公式化。与以前的方法相反，这产生光滑的，分析上可区分的和有效的优化姿态相似能量与严格的遮挡处理，较少的局部最小值，并通过实验验证改进的数值优化收敛性。其基本思想是一个新的图像形成模型，它通过具有平滑的高斯密度分布的半透明介质来表示不透明的对象，从而将可见性转化为平滑的现象。我们展示了我们的多功能场景模型在几个生成姿态估计问题中的优势，即无标记多目标姿态估计，少标记摄像头的无标记人体运动以及基于图像的三维几何估计。

##### URL
[https://arxiv.org/abs/1602.03725](https://arxiv.org/abs/1602.03725)

##### PDF
[https://arxiv.org/pdf/1602.03725](https://arxiv.org/pdf/1602.03725)

