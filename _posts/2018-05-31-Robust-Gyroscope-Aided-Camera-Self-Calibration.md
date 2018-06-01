---
layout: post
title: "Robust Gyroscope-Aided Camera Self-Calibration"
date: 2018-05-31 15:08:35
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Santiago Cort&#xe9;s Reina, Arno Solin, Juho Kannala
mathjax: true
---

* content
{:toc}

##### Abstract
Camera calibration for estimating the intrinsic parameters and lens distortion is a prerequisite for various monocular vision applications including feature tracking and video stabilization. This application paper proposes a model for estimating the parameters on the fly by fusing gyroscope and camera data, both readily available in modern day smartphones. The model is based on joint estimation of visual feature positions, camera parameters, and the camera pose, the movement of which is assumed to follow the movement predicted by the gyroscope. Our model assumes the camera movement to be free, but continuous and differentiable, and individual features are assumed to stay stationary. The estimation is performed online using an extended Kalman filter, and it is shown to outperform existing methods in robustness and insensitivity to initialization. We demonstrate the method using simulated data and empirical data from an iPad.

##### Abstract (translated by Google)
用于估计固有参数和镜头畸变的相机校准是各种单眼视觉应用（包括特征跟踪和视频稳定）的先决条件。本应用论文提出了一种通过融合陀螺仪和相机数据来实时估算参数的模型，这两种模型都可以在现代智能手机中使用。该模型基于视觉特征位置，摄像机参数和摄像机姿态的联合估计，其运动假定为跟随由陀螺仪预测的运动。我们的模型假定摄像机的运动是自由的，但是连续的和可微的，并且假设个体特征保持静止。该估计是使用扩展卡尔曼滤波器在线执行的，并且其显示在对初始化的鲁棒性和不敏感性方面优于现有方法。我们使用iPad的模拟数据和经验数据演示该方法。

##### URL
[http://arxiv.org/abs/1805.12506](http://arxiv.org/abs/1805.12506)

##### PDF
[http://arxiv.org/pdf/1805.12506](http://arxiv.org/pdf/1805.12506)

