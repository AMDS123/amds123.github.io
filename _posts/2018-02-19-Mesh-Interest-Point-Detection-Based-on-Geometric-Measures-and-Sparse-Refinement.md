---
layout: post
title: "Mesh Interest Point Detection Based on Geometric Measures and Sparse Refinement"
date: 2018-02-19 12:22:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Optimization Detection
author: Xinyu Lin, Ce Zhu, Yipeng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Three dimensional (3D) interest point detection plays a fundamental role in 3D computer vision and graphics. In this paper, we introduce a new method for detecting mesh interest points based on geometric measures and sparse refinement (GMSR). The key point of our approach is to calculate the 3D interest point response function using two intuitive and effective geometric properties of the local surface on a 3D mesh model, namely Euclidean distances between the neighborhood vertices to the tangent plane of a vertex and the angles of normal vectors of them. The response function is defined in multi-scale space and can be utilized to effectively distinguish 3D interest points from edges and flat areas. Those points with local maximal 3D interest point response value are selected as the candidates of 3D interest points. Finally, we utilize an $\ell_0$ norm based optimization method to refine the candidates of 3D interest points by constraining its quality and quantity. Numerical experiments demonstrate that our proposed GMSR based 3D interest point detector outperforms current several state-of-the-art methods for different kinds of 3D mesh models.

##### Abstract (translated by Google)
三维（3D）兴趣点检测在3D计算机视觉和图形中扮演着重要角色。在本文中，我们介绍了一种基于几何量度和稀疏细化（GMSR）的网格兴趣点检测新方法。我们的方法的关键点是使用三维网格模型上的局部曲面的两个直观和有效的几何特性来计算三维兴趣点响应函数，即邻近顶点到顶点的切平面之间的欧几里德距离和它们的法向量。响应函数在多尺度空间中定义，可用于有效区分边缘和平坦区域的三维兴趣点。具有局部最大3D兴趣点响应值的点被选为3D兴趣点的候选点。最后，我们利用基于$ \ ell_0 $范数的优化方法通过约束其质量和数量来优化3D兴趣点的候选。数值实验表明，我们提出的基于GMSR的3D兴趣点检测器优于当前几种用于不同类型3D网格模型的最先进的方法。

##### URL
[http://arxiv.org/abs/1604.08806](http://arxiv.org/abs/1604.08806)

##### PDF
[http://arxiv.org/pdf/1604.08806](http://arxiv.org/pdf/1604.08806)

