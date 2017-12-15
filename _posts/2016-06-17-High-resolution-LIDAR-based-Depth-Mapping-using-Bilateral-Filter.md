---
layout: post
title: "High-resolution LIDAR-based Depth Mapping using Bilateral Filter"
date: 2016-06-17 18:14:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Segmentation Semantic_Segmentation Quantitative Detection
author: C. Premebida, L. Garrote, A. Asvadi, A. Pedro Ribeiro, U. Nunes
mathjax: true
---

* content
{:toc}

##### Abstract
High resolution depth-maps, obtained by upsampling sparse range data from a 3D-LIDAR, find applications in many fields ranging from sensory perception to semantic segmentation and object detection. Upsampling is often based on combining data from a monocular camera to compensate the low-resolution of a LIDAR. This paper, on the other hand, introduces a novel framework to obtain dense depth-map solely from a single LIDAR point cloud; which is a research direction that has been barely explored. The formulation behind the proposed depth-mapping process relies on local spatial interpolation, using sliding-window (mask) technique, and on the Bilateral Filter (BF) where the variable of interest, the distance from the sensor, is considered in the interpolation problem. In particular, the BF is conveniently modified to perform depth-map upsampling such that the edges (foreground-background discontinuities) are better preserved by means of a proposed method which influences the range-based weighting term. Other methods for spatial upsampling are discussed, evaluated and compared in terms of different error measures. This paper also researches the role of the mask's size in the performance of the implemented methods. Quantitative and qualitative results from experiments on the KITTI Database, using LIDAR point clouds only, show very satisfactory performance of the approach introduced in this work.

##### Abstract (translated by Google)
通过对来自3D-LIDAR的稀疏范围数据进行上采样而获得的高分辨率深度图在许多领域中找到应用，从感官感知到语义分割和对象检测。上采样通常基于结合单眼相机的数据来补偿激光雷达的低分辨率。另一方面，本文引入了一个新颖的框架，从单一的LIDAR点云中获得密集的深度图。这是一个勉强探索的研究方向。在所提出的深度映射过程之后的公式依赖于局部空间插值，使用滑动窗口（掩模）技术，并且在双边滤波器（BF）处，其中感兴趣的变量，距离传感器的距离在插值问题中被考虑。特别地，BF被方便地修改以执行深度图上采样，使得通过影响基于范围的加权项的所提出的方法来更好地保留边缘（前景 - 背景不连续性）。其他方法的空间上采样进行了讨论，评估和比较不同的错误措施。本文还研究了掩模大小在实现方法性能中的作用。 KITTI数据库实验的定量和定性结果，仅使用LIDAR点云，显示了本文所介绍方法的非常令人满意的性能。

##### URL
[https://arxiv.org/abs/1606.05614](https://arxiv.org/abs/1606.05614)

##### PDF
[https://arxiv.org/pdf/1606.05614](https://arxiv.org/pdf/1606.05614)

