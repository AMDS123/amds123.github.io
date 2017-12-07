---
layout: post
title: "Multi-View 3D Object Detection Network for Autonomous Driving"
date: 2017-06-22 03:23:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Xiaozhi Chen, Huimin Ma, Ji Wan, Bo Li, Tian Xia
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at high-accuracy 3D object detection in autonomous driving scenario. We propose Multi-View 3D networks (MV3D), a sensory-fusion framework that takes both LIDAR point cloud and RGB images as input and predicts oriented 3D bounding boxes. We encode the sparse 3D point cloud with a compact multi-view representation. The network is composed of two subnetworks: one for 3D object proposal generation and another for multi-view feature fusion. The proposal network generates 3D candidate boxes efficiently from the bird's eye view representation of 3D point cloud. We design a deep fusion scheme to combine region-wise features from multiple views and enable interactions between intermediate layers of different paths. Experiments on the challenging KITTI benchmark show that our approach outperforms the state-of-the-art by around 25% and 30% AP on the tasks of 3D localization and 3D detection. In addition, for 2D detection, our approach obtains 10.3% higher AP than the state-of-the-art on the hard data among the LIDAR-based methods.

##### Abstract (translated by Google)
本文针对自动驾驶场景中的高精度三维物体检测。我们提出了多视点三维网络（MV3D），这是一个感知融合框架，将LIDAR点云和RGB图像作为输入，并预测定向的3D边界框。我们用紧凑的多视图表示编码稀疏三维点云。该网络由两个子网组成：一个用于三维物体建议生成，另一个用于多视点特征融合。提议网络从3D点云的鸟瞰图表示中有效地生成3D候选框。我们设计了一种深度融合方案，将多个视图中的区域特征相结合，并实现不同路径中间层之间的交互。在具有挑战性的KITTI基准测试中的实验表明，我们的方法在三维定位和三维检测任务方面的性能超过了25％和30％。此外，对于二维检测，我们的方法获得比基于LIDAR的方法中硬数据的最新技术高出10.3％的AP。

##### URL
[https://arxiv.org/abs/1611.07759](https://arxiv.org/abs/1611.07759)

##### PDF
[https://arxiv.org/pdf/1611.07759](https://arxiv.org/pdf/1611.07759)

