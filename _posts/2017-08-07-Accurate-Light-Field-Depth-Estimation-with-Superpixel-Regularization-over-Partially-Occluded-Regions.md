---
layout: post
title: "Accurate Light Field Depth Estimation with Superpixel Regularization over Partially Occluded Regions"
date: 2017-08-07 02:05:36
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Jie Chen, Junhui Hou, Yun Ni, Lap-Pui Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation is a fundamental problem for light field photography applications. Numerous methods have been proposed in recent years, which either focus on crafting cost terms for more robust matching, or on analyzing the geometry of scene structures embedded in the epipolar-plane images. Significant improvements have been made in terms of overall depth estimation error; however, current state-of-the-art methods still show limitations in handling intricate occluding structures and complex scenes with multiple occlusions. To address these challenging issues, we propose a very effective depth estimation framework which focuses on regularizing the initial label confidence map and edge strength weights. Specifically, we first detect partially occluded boundary regions (POBR) via superpixel based regularization. Series of shrinkage/reinforcement operations are then applied on the label confidence map and edge strength weights over the POBR. We show that after weight manipulations, even a low-complexity weighted least squares model can produce much better depth estimation than state-of-the-art methods in terms of average disparity error rate, occlusion boundary precision-recall rate, and the preservation of intricate visual features.

##### Abstract (translated by Google)
深度估计是光场摄影应用的根本问题。近年来已经提出了许多方法，其重点在于制造用于更鲁棒匹配的成本项，或者分析嵌入在核面图像中的场景结构的几何形状。在整体深度估计误差方面取得了重大进展;然而，当前最先进的方法在处理错综复杂的遮挡结构和具有多个遮挡的复杂场景中仍然存在限制。为了解决这些具有挑战性的问题，我们提出了一个非常有效的深度估计框架，其重点在于规范初始标签置信度图和边缘强度权重。具体而言，我们首先通过基于超像素的正则化检测部分遮挡的边界区域（POBR）。然后将一系列收缩/加固操作应用于标签置信度图和边缘强度权重上的POBR。我们表明，在权重操纵之后，即使是一个低复杂度的加权最小二乘模型，在平均视差错率，遮挡边界的精确查全率，以及保留错综复杂的视觉特征。

##### URL
[https://arxiv.org/abs/1708.01964](https://arxiv.org/abs/1708.01964)

##### PDF
[https://arxiv.org/pdf/1708.01964](https://arxiv.org/pdf/1708.01964)

