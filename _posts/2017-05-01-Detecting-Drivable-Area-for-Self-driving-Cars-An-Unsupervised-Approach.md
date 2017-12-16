---
layout: post
title: "Detecting Drivable Area for Self-driving Cars: An Unsupervised Approach"
date: 2017-05-01 09:14:29
categories: arXiv_CV
tags: arXiv_CV Face Inference
author: Ziyi Liu, Siyu Yu, Xiao Wang, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
It has been well recognized that detecting drivable area is central to self-driving cars. Most of existing methods attempt to locate road surface by using lane line, thereby restricting to drivable area on which have a clear lane mark. This paper proposes an unsupervised approach for detecting drivable area utilizing both image data from a monocular camera and point cloud data from a 3D-LIDAR scanner. Our approach locates initial drivable areas based on a "direction ray map" obtained by image-LIDAR data fusion. Besides, a fusion of the feature level is also applied for more robust performance. Once the initial drivable areas are described by different features, the feature fusion problem is formulated as a Markov network and a belief propagation algorithm is developed to perform the model inference. Our approach is unsupervised and avoids common hypothesis, yet gets state-of-the-art results on ROAD-KITTI benchmark. Experiments show that our unsupervised approach is efficient and robust for detecting drivable area for self-driving cars.

##### Abstract (translated by Google)
人们已经认识到，检测可驾驶区域是自驾车的核心。现有的大多数方法都试图通过使用车道线来定位路面，从而限制了车道标线清晰的可行驶区域。本文提出了一种无监督的方法来利用单目摄像机的图像数据和来自3D-LIDAR扫描仪的点云数据来检测可驾驶区域。我们的方法基于通过图像-LIDAR数据融合获得的“方向射线图”来定位初始可驾驶区域。此外，还将特征级别的融合应用于更强大的性能。一旦初始可驱动区域被不同的特征描述，特征融合问题被表示为马尔可夫网络，并且开发一个信任传播算法来执行模型推理。我们的方法是无监督的，避免了常见的假设，但在ROAD-KITTI基准测试中获得了最新的结果。实验表明，我们的无监督的方法是有效和鲁棒的检测驾驶汽车的驾驶区域。

##### URL
[https://arxiv.org/abs/1705.00451](https://arxiv.org/abs/1705.00451)

##### PDF
[https://arxiv.org/pdf/1705.00451](https://arxiv.org/pdf/1705.00451)

