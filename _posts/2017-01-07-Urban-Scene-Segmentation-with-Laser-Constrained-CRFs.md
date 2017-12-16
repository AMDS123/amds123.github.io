---
layout: post
title: "Urban Scene Segmentation with Laser-Constrained CRFs"
date: 2017-01-07 22:58:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Charika De Alvis, Lionel Ott, Fabio Ramos
mathjax: true
---

* content
{:toc}

##### Abstract
Robots typically possess sensors of different modalities, such as colour cameras, inertial measurement units, and 3D laser scanners. Often, solving a particular problem becomes easier when more than one modality is used. However, while there are undeniable benefits to combine sensors of different modalities the process tends to be complicated. Segmenting scenes observed by the robot into a discrete set of classes is a central requirement for autonomy as understanding the scene is the first step to reason about future situations. Scene segmentation is commonly performed using either image data or 3D point cloud data. In computer vision many successful methods for scene segmentation are based on conditional random fields (CRF) where the maximum a posteriori (MAP) solution to the segmentation can be obtained by inference. In this paper we devise a new CRF inference method for scene segmentation that incorporates global constraints, enforcing the sets of nodes are assigned the same class label. To do this efficiently, the CRF is formulated as a relaxed quadratic program whose MAP solution is found using a gradient-based optimisation approach. The proposed method is evaluated on images and 3D point cloud data gathered in urban environments where image data provides the appearance features needed by the CRF, while the 3D point cloud data provides global spatial constraints over sets of nodes. Comparisons with belief propagation, conventional quadratic programming relaxation, and higher order potential CRF show the benefits of the proposed method.

##### Abstract (translated by Google)
机器人通常拥有不同形式的传感器，例如彩色相机，惯性测量单元和3D激光扫描仪。通常，当使用多种形式时，解决特定问题变得更容易。然而，虽然将不同方式的传感器组合起来是不可否认的，但是过程往往是复杂的。将机器人观察到的场景分解为一组离散的类是自主性的核心要求，因为理解场景是推导未来情况的第一步。场景分割通常使用图像数据或3D点云数据执行。在计算机视觉中，许多成功的场景分割方法都是基于条件随机场（CRF），其中通过推理可以获得最大后验概率（MAP）解决方案。在本文中，我们设计了一种新的CRF推理方法，用于合并全局约束的场景分割，强制节点集合被分配相同的类别标签。为了有效地做到这一点，CRF被制定为松弛的二次程序，其MAP解决方案是使用基于梯度的优化方法找到的。所提出的方法在图像和在城市环境中收集的三维点云数据上进行评估，其中图像数据提供CRF所需的外观特征，而三维点云数据提供对节点组的全局空间约束。与置信传播，常规二次规划松弛和高阶潜在CRF的比较显示了所提出的方法的益处。

##### URL
[https://arxiv.org/abs/1701.01892](https://arxiv.org/abs/1701.01892)

##### PDF
[https://arxiv.org/pdf/1701.01892](https://arxiv.org/pdf/1701.01892)

