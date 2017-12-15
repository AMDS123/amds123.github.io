---
layout: post
title: "Latent-Class Hough Forests for 6 DoF Object Pose Estimation"
date: 2016-02-03 20:53:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Pose_Estimation Detection
author: Rigas Kouskouridas, Alykhan Tejani, Andreas Doumanoglou, Danhang Tang, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present Latent-Class Hough Forests, a method for object detection and 6 DoF pose estimation in heavily cluttered and occluded scenarios. We adapt a state of the art template matching feature into a scale-invariant patch descriptor and integrate it into a regression forest using a novel template-based split function. We train with positive samples only and we treat class distributions at the leaf nodes as latent variables. During testing we infer by iteratively updating these distributions, providing accurate estimation of background clutter and foreground occlusions and, thus, better detection rate. Furthermore, as a by-product, our Latent-Class Hough Forests can provide accurate occlusion aware segmentation masks, even in the multi-instance scenario. In addition to an existing public dataset, which contains only single-instance sequences with large amounts of clutter, we have collected two, more challenging, datasets for multiple-instance detection containing heavy 2D and 3D clutter as well as foreground occlusions. We provide extensive experiments on the various parameters of the framework such as patch size, number of trees and number of iterations to infer class distributions at test time. We also evaluate the Latent-Class Hough Forests on all datasets where we outperform state of the art methods.

##### Abstract (translated by Google)
在本文中，我们提出潜在级霍夫森林，一种方法对象检测和6 DoF姿态估计在严重杂乱和闭塞的情况。我们将先进的模板匹配特征调整为尺度不变的补丁描述符，并使用新颖的基于模板的分割函数将其集成到回归森林中。我们只训练阳性样本，我们把叶节点上的类分布看作潜变量。在测试过程中，我们通过迭代更新这些分布来推断，提供背景杂波和前景遮挡的准确估计，从而提高检测率。此外，作为副产品，即使在多实例场景下，我们的潜类Hough Forests也能提供准确的遮挡感知分割遮罩。除了现有的公共数据集，其中只包含具有大量杂波的单实例序列，我们还收集了包含重二维和三维杂波以及前景遮挡的多实例检测的两个更具挑战性的数据集。我们在框架的各种参数上提供了广泛的实验，例如补丁大小，树数和迭代次数以推断测试时的类分布。我们还评估潜在级霍夫森林在所有数据集，我们超越了最先进的方法。

##### URL
[https://arxiv.org/abs/1602.01464](https://arxiv.org/abs/1602.01464)

##### PDF
[https://arxiv.org/pdf/1602.01464](https://arxiv.org/pdf/1602.01464)

