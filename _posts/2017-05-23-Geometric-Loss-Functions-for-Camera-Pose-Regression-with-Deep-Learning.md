---
layout: post
title: "Geometric Loss Functions for Camera Pose Regression with Deep Learning"
date: 2017-05-23 13:45:48
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Alex Kendall, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has shown to be effective for robust and real-time monocular image relocalisation. In particular, PoseNet is a deep convolutional neural network which learns to regress the 6-DOF camera pose from a single image. It learns to localize using high level features and is robust to difficult lighting, motion blur and unknown camera intrinsics, where point based SIFT registration fails. However, it was trained using a naive loss function, with hyper-parameters which require expensive tuning. In this paper, we give the problem a more fundamental theoretical treatment. We explore a number of novel loss functions for learning camera pose which are based on geometry and scene reprojection error. Additionally we show how to automatically learn an optimal weighting to simultaneously regress position and orientation. By leveraging geometry, we demonstrate that our technique significantly improves PoseNet's performance across datasets ranging from indoor rooms to a small city.

##### Abstract (translated by Google)
深度学习已被证明是有效的强大和实时的单眼图像重新定位。特别地，PoseNet是一个深度卷积神经网络，学习从单个图像中回归6-DOF相机姿态。它学习使用高级特征进行本地化，对于困难的照明，运动模糊和未知的摄像机内部函数（在基于点的SIFT注册失败的情况下）是强大的。然而，它使用天真丢失功能进行训练，需要昂贵的调谐的超参数。在本文中，我们给这个问题提供了一个更基础的理论处理。我们探索了一些基于几何和场景重投影误差的学习摄像机姿态的新型损失函数。此外，我们还演示如何自动学习最佳权重，以同时回归位置和方向。通过利用几何，我们证明了我们的技术显着提高了从室内房间到小城市的数据集的性能。

##### URL
[https://arxiv.org/abs/1704.00390](https://arxiv.org/abs/1704.00390)

##### PDF
[https://arxiv.org/pdf/1704.00390](https://arxiv.org/pdf/1704.00390)

