---
layout: post
title: "Flexible Stereo: Constrained, Non-rigid, Wide-baseline Stereo Vision for Fixed-wing Aerial Platforms"
date: 2017-12-19 09:34:46
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Timo Hinzmann, Tim Taubner, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a computationally efficient method to estimate the time-varying relative pose between two visual-inertial sensor rigs mounted on the flexible wings of a fixed-wing unmanned aerial vehicle (UAV). The estimated relative poses are used to generate highly accurate depth maps in real-time and can be employed for obstacle avoidance in low-altitude flights or landing maneuvers. The approach is structured as follows: Initially, a wing model is identified by fitting a probability density function to measured deviations from the nominal relative baseline transformation. At run-time, the prior knowledge about the wing model is fused in an Extended Kalman filter~(EKF) together with relative pose measurements obtained from solving a relative perspective N-point problem (PNP), and the linear accelerations and angular velocities measured by the two inertial measurement units (IMU) which are rigidly attached to the cameras. Results obtained from extensive synthetic experiments demonstrate that our proposed framework is able to estimate highly accurate baseline transformations and depth maps.

##### Abstract (translated by Google)
本文提出了一种计算有效的方法来估计安装在固定翼无人机（UAV）的柔性翼上的两个视觉 - 惯性传感器钻机之间的时变相对姿态。估计的相对姿态用于实时生成高度精确的深度图，并可用于低空飞行或着陆操纵中的避障。该方法的结构如下：首先，通过拟合概率密度函数来测量与名义相对基线变换的测量偏差，来识别机翼模型。在运行时，将关于机翼模型的先验知识与扩展卡尔曼滤波器（EKF）一起进行融合，以及通过解决相对透视N点问题（PNP）获得的相对姿态测量以及测量的线性加速度和角速度通过刚性连接到摄像机的两个惯性测量单元（IMU）。从广泛的合成实验获得的结果表明，我们提出的框架能够估计高度精确的基线变换和深度图。

##### URL
[http://arxiv.org/abs/1712.06837](http://arxiv.org/abs/1712.06837)

##### PDF
[http://arxiv.org/pdf/1712.06837](http://arxiv.org/pdf/1712.06837)

