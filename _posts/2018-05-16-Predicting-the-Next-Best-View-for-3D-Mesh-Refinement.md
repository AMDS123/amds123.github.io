---
layout: post
title: "Predicting the Next Best View for 3D Mesh Refinement"
date: 2018-05-16 09:31:24
categories: arXiv_CV
tags: arXiv_CV Face
author: Luca Morreale, Andrea Romanoni, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
3D reconstruction is a core task in many applications such as robot navigation or sites inspections. Finding the best poses to capture part of the scene is one of the most challenging topic that goes under the name of Next Best View. Recently, many volumetric methods have been proposed; they choose the Next Best View by reasoning over a 3D voxelized space and by finding which pose minimizes the uncertainty decoded into the voxels. Such methods are effective, but they do not scale well since the underlaying representation requires a huge amount of memory. In this paper we propose a novel mesh-based approach which focuses on the worst reconstructed region of the environment mesh. We define a photo-consistent index to evaluate the 3D mesh accuracy, and an energy function over the worst regions of the mesh which takes into account the mutual parallax with respect to the previous cameras, the angle of incidence of the viewing ray to the surface and the visibility of the region. We test our approach over a well known dataset and achieve state-of-the-art results.

##### Abstract (translated by Google)
3D重建是许多应用程序的核心任务，例如机器人导航或站点检查。寻找最佳姿势来捕捉部分场景是Next Next View名下最具挑战性的主题之一。最近，已经提出了许多容积方法;他们通过对3D体素化空间进行推理并找出哪个姿态最小化解码为体素的不确定性来选择Next Best View。这种方法是有效的，但是它们不能很好地扩展，因为下层代表需要大量的内存。在本文中，我们提出了一种新颖的基于网格的方法，其侧重于环境网格的最坏的重建区域。我们定义了一个光照一致性指数来评估三维网格的精度，以及网格最差区域的能量函数，该函数考虑了相对于先前摄像机的相互视差，视线到表面的入射角以及该地区的知名度。我们通过众所周知的数据集来测试我们的方法，并获得最新的结果。

##### URL
[http://arxiv.org/abs/1805.06207](http://arxiv.org/abs/1805.06207)

##### PDF
[http://arxiv.org/pdf/1805.06207](http://arxiv.org/pdf/1805.06207)

