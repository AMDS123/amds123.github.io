---
layout: post
title: "Joint Layout Estimation and Global Multi-View Registration for Indoor Reconstruction"
date: 2017-09-06 11:48:16
categories: arXiv_CV
tags: arXiv_CV Optimization Quantitative
author: Jeong-Kyun Lee, Jae-Won Yea, Min-Gyu Park, Kuk-Jin Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel method to jointly solve scene layout estimation and global registration problems for accurate indoor 3D reconstruction. Given a sequence of range data, we first build a set of scene fragments using KinectFusion and register them through pose graph optimization. Afterwards, we alternate between layout estimation and layout-based global registration processes in iterative fashion to complement each other. We extract the scene layout through hierarchical agglomerative clustering and energy-based multi-model fitting in consideration of noisy measurements. Having the estimated scene layout in one hand, we register all the range data through the global iterative closest point algorithm where the positions of 3D points that belong to the layout such as walls and a ceiling are constrained to be close to the layout. We experimentally verify the proposed method with the publicly available synthetic and real-world datasets in both quantitative and qualitative ways.

##### Abstract (translated by Google)
在本文中，我们提出了一种联合求解场景布局估计和全局配准问题的新方法，以实现准确的室内三维重建。给定一系列距离数据，我们首先使用KinectFusion建立一组场景片段，并通过姿势图优化来注册它们。之后，我们在迭代的方式之间交替布局估计和基于布局的全局注册过程，以相互补充。我们通过层次凝聚聚类和基于能量的多模型拟合来提取场景布局，考虑到噪声测量。一方面估计场景布局，我们通过全局迭代最近点算法来记录所有范围数据，其中属于布局的3D点的位置（例如墙壁和天花板）被限制为接近布局。我们用定量和定性的方式用公开可用的合成和现实世界的数据集来实验性地验证所提出的方法。

##### URL
[https://arxiv.org/abs/1704.07632](https://arxiv.org/abs/1704.07632)

##### PDF
[https://arxiv.org/pdf/1704.07632](https://arxiv.org/pdf/1704.07632)

