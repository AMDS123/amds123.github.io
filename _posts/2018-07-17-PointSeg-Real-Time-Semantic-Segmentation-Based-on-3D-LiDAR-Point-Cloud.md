---
layout: post
title: "PointSeg: Real-Time Semantic Segmentation Based on 3D LiDAR Point Cloud"
date: 2018-07-17 09:06:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Prediction Detection
author: Yuan Wang, Tianyue Shi, Peng Yun, Lei Tai, Ming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose PointSeg, a real-time end-to-end semantic segmentation method for road-objects based on spherical images. We take the spherical image, which is transformed from the 3D LiDAR point clouds, as input of the convolutional neural networks (CNNs) to predict the point-wise semantic map. To make PointSeg applicable on a mobile system, we build the model based on the light-weight network, SqueezeNet, with several improvements. It maintains a good balance between memory cost and prediction performance. Our model is trained on spherical images and label masks projected from the KITTI 3D object detection dataset. Experiments show that PointSeg can achieve competitive accuracy with 90fps on a single GPU 1080ti. which makes it quite compatible for autonomous driving applications.

##### Abstract (translated by Google)
在本文中，我们提出了PointSeg，一种基于球形图像的道路对象的实时端到端语义分割方法。我们将从3D LiDAR点云转换的球形图像作为卷积神经网络（CNN）的输入来预测逐点语义图。为了使PointSeg适用于移动系统，我们基于轻量级网络SqueezeNet构建模型，并进行了多项改进。它在内存成本和预测性能之间保持良好的平衡。我们的模型是根据KITTI 3D物体检测数据集投影的球形图像和标签蒙版进行训练的。实验表明，PointSeg可以在单个GPU 1080ti上以90fps实现竞争精度。这使它非常适合自动驾驶应用。

##### URL
[http://arxiv.org/abs/1807.06288](http://arxiv.org/abs/1807.06288)

##### PDF
[http://arxiv.org/pdf/1807.06288](http://arxiv.org/pdf/1807.06288)

