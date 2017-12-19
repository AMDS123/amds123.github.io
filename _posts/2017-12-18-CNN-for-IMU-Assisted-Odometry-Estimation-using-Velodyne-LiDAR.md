---
layout: post
title: "CNN for IMU Assisted Odometry Estimation using Velodyne LiDAR"
date: 2017-12-18 11:56:48
categories: arXiv_RO
tags: arXiv_RO Review Sparse CNN Prediction
author: Martin Velas, Michal Spanel, Michal Hradis, Adam Herout
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel method for odometry estimation using convolutional neural networks from 3D LiDAR scans. The original sparse data are encoded into 2D matrices for the training of proposed networks and for the prediction. Our networks show significantly better precision in the estimation of translational motion parameters comparing with state of the art method LOAM, while achieving real-time performance. Together with IMU support, high quality odometry estimation and LiDAR data registration is realized. Moreover, we propose alternative CNNs trained for the prediction of rotational motion parameters while achieving results also comparable with state of the art. The proposed method can replace wheel encoders in odometry estimation or supplement missing GPS data, when the GNSS signal absents (e.g. during the indoor mapping). Our solution brings real-time performance and precision which are useful to provide online preview of the mapping results and verification of the map completeness in real time.

##### Abstract (translated by Google)
我们引入了一种新的方法来测量使用来自3D LiDAR扫描的卷积神经网络的测距法。原始稀疏数据被编码成二维矩阵，用于训练提出的网络和预测。与现有技术方法LOAM相比，我们的网络在平移运动参数的估计中显示出明显更好的精度，同时实现实时性能。与IMU支持一起，实现高质量的测距和LiDAR数据注册。此外，我们提出了替代CNN的训练预测旋转运动参数，同时实现结果也与现有技术水平相媲美。当GNSS信号不存在时（例如，在室内映射期间），所提出的方法可以替代测距估计中的轮编码器或补充丢失的GPS数据。我们的解决方案带来了实时的性能和精确度，有助于实时提供地图结果的在线预览和地图完整性验证。

##### URL
[http://arxiv.org/abs/1712.06352](http://arxiv.org/abs/1712.06352)

##### PDF
[http://arxiv.org/pdf/1712.06352](http://arxiv.org/pdf/1712.06352)

