---
layout: post
title: "Vision-Aided Absolute Trajectory Estimation Using an Unsupervised Deep Network with Online Error Correction"
date: 2018-03-08 11:59:49
categories: arXiv_CV
tags: arXiv_CV SLAM
author: E. Jared Shamwell, Sarah Leung, William D. Nothwang
mathjax: true
---

* content
{:toc}

##### Abstract
We present an unsupervised deep neural network approach to the fusion of RGB-D imagery with inertial measurements for absolute trajectory estimation. Our network, dubbed the Visual-Inertial-Odometry Learner (VIOLearner), learns to perform visual-inertial odometry (VIO) without inertial measurement unit (IMU) intrinsic parameters (corresponding to gyroscope and accelerometer bias or white noise) or the extrinsic calibration between an IMU and camera. The network learns to integrate IMU measurements and generate hypothesis trajectories which are then corrected online according to the Jacobians of scaled image projection errors with respect to a spatial grid of pixel coordinates. We evaluate our network against state-of-the-art (SOA) visual-inertial odometry, visual odometry, and visual simultaneous localization and mapping (VSLAM) approaches on the KITTI Odometry dataset and demonstrate competitive odometry performance.

##### Abstract (translated by Google)
我们提出了一种无监督的深度神经网络方法，将RGB-D图像与惯性测量值进行绝对轨迹估计融合。我们的网络被称为Visual-Inertial-Odometry Learner（VIOLearner），它学习在没有惯性测量单元（IMU）固有参数（对应于陀螺仪和加速度计偏差或白噪声）的情况下执行视觉惯性测距法（VIO） IMU和相机。网络学习整合IMU测量结果并生成假设轨迹，然后根据相对于像素坐标的空间网格的缩放图像投影误差的雅可比行为在线校正假设轨迹。我们使用KITTI Odometry数据集中最先进的（SOA）视觉 - 惯性测距，视觉测距和视觉同时定位和测绘（VSLAM）方法评估我们的网络，并展示竞争性测距性能。

##### URL
[https://arxiv.org/abs/1803.05850](https://arxiv.org/abs/1803.05850)

##### PDF
[https://arxiv.org/pdf/1803.05850](https://arxiv.org/pdf/1803.05850)

