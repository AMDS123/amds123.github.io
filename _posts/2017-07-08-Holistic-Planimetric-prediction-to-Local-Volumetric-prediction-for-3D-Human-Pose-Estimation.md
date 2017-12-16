---
layout: post
title: "Holistic Planimetric prediction to Local Volumetric prediction for 3D Human Pose Estimation"
date: 2017-07-08 17:10:18
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Prediction
author: Gyeongsik Moon, Ju Yong Chang, Yumin Suh, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach to 3D human pose estimation from a single depth map. Recently, convolutional neural network (CNN) has become a powerful paradigm in computer vision. Many of computer vision tasks have benefited from CNNs, however, the conventional approach to directly regress 3D body joint locations from an image does not yield a noticeably improved performance. In contrast, we formulate the problem as estimating per-voxel likelihood of key body joints from a 3D occupancy grid. We argue that learning a mapping from volumetric input to volumetric output with 3D convolution consistently improves the accuracy when compared to learning a regression from depth map to 3D joint coordinates. We propose a two-stage approach to reduce the computational overhead caused by volumetric representation and 3D convolution: Holistic 2D prediction and Local 3D prediction. In the first stage, Planimetric Network (P-Net) estimates per-pixel likelihood for each body joint in the holistic 2D space. In the second stage, Volumetric Network (V-Net) estimates the per-voxel likelihood of each body joints in the local 3D space around the 2D estimations of the first stage, effectively reducing the computational cost. Our model outperforms existing methods by a large margin in publicly available datasets.

##### Abstract (translated by Google)
我们提出了一种新的方法来从单个深度图进行3D人体姿态估计。最近，卷积神经网络（CNN）已经成为计算机视觉领域的一个强大的范例。许多计算机视觉任务已经从CNN中受益，然而，从图像直接回归3D身体关节位置的传统方法不会显着提高性能。相反，我们将问题描述为从3D占用网格估计关键体节点的体素可能性。我们认为，从三维卷积学习从体积输入到体积输出的映射，与学习从深度图到三维关节坐标的回归相比，一致地提高了准确性。我们提出了一个两阶段的方法来减少由体积表示和三维卷积引起的计算开销：整体二维预测和局部三维预测。在第一阶段，平面网络（P-Net）估计整体二维空间中每个身体关节的每像素可能性。在第二阶段，容积网络（V-Net）估计在第一阶段的2D估计周围的局部3D空间中的每个身体关节的每个体素可能性，有效地降低了计算成本。我们的模型在公开可用的数据集中优于现有的方法。

##### URL
[https://arxiv.org/abs/1706.04758](https://arxiv.org/abs/1706.04758)

##### PDF
[https://arxiv.org/pdf/1706.04758](https://arxiv.org/pdf/1706.04758)

