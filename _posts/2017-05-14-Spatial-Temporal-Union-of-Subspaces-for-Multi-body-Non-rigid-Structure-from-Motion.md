---
layout: post
title: "Spatial-Temporal Union of Subspaces for Multi-body Non-rigid Structure-from-Motion"
date: 2017-05-14 05:59:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Suryansh Kumar, Yuchao Dai, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Non-rigid structure-from-motion (NRSfM) has so far been mostly studied for recovering 3D structure of a single non-rigid/deforming object. To handle the real world challenging multiple deforming objects scenarios, existing methods either pre-segment different objects in the scene or treat multiple non-rigid objects as a whole to obtain the 3D non-rigid reconstruction. However, these methods fail to exploit the inherent structure in the problem as the solution of segmentation and the solution of reconstruction could not benefit each other. In this paper, we propose a unified framework to jointly segment and reconstruct multiple non-rigid objects. To compactly represent complex multi-body non-rigid scenes, we propose to exploit the structure of the scenes along both temporal direction and spatial direction, thus achieving a spatio-temporal representation. Specifically, we represent the 3D non-rigid deformations as lying in a union of subspaces along the temporal direction and represent the 3D trajectories as lying in the union of subspaces along the spatial direction. This spatio-temporal representation not only provides competitive 3D reconstruction but also outputs robust segmentation of multiple non-rigid objects. The resultant optimization problem is solved efficiently using the Alternating Direction Method of Multipliers (ADMM). Extensive experimental results on both synthetic and real multi-body NRSfM datasets demonstrate the superior performance of our proposed framework compared with the state-of-the-art methods.

##### Abstract (translated by Google)
迄今为止，非刚性运动结构（NRSfM）主要用于恢复单个非刚性/变形物体的三维结构。为了处理挑战多个变形对象场景的现实世界，现有方法要么预先分割场景中的不同对象，要么将多个非刚体对象作为一个整体来获得三维非刚性重建。然而，这些方法无法利用问题的内在结构作为分割的解决方案，而且重构的解决方案也不能相互获益。在本文中，我们提出了一个统一的框架来联合分割和重构多个非刚性对象。为了紧凑地表示复杂的多体非刚性场景，我们提出沿时间方向和空间方向利用场景的结构，从而实现时空表示。具体而言，我们将三维非刚性变形表示为位于沿着时间方向的子空间的并集，并将三维轨迹表示为沿空间方向位于子空间的并集中。这种时空表示不仅提供了有竞争力的3D重建，而且还输出了多个非刚性物体的健壮分割。使用交替方向乘法器（ADMM）可以有效地解决最终的优化问题。在综合和真实的多体NRSfM数据集上的广泛的实验结果证明了与现有技术方法相比，我们所提出的框架的优越性能。

##### URL
[https://arxiv.org/abs/1705.04916](https://arxiv.org/abs/1705.04916)

##### PDF
[https://arxiv.org/pdf/1705.04916](https://arxiv.org/pdf/1705.04916)

