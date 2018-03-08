---
layout: post
title: "PI-VIO: Robust and Efficient Stereo Visual Inertial Odometry using Points and Lines"
date: 2018-03-06 19:49:00
categories: arXiv_CV
tags: arXiv_CV
author: Feng Zheng, Grace Tsai, Zhe Zhang, Shaoshan Liu, Chen-Chi Chu, Hongbing Hu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present the PerceptIn Visual Inertial Odometry (PI-VIO), a tightly-coupled filtering-based stereo VIO system using both points and lines. Line features help improve system robustness in challenging scenarios when point features cannot be reliably detected or tracked, e.g. low-texture environment or lighting change. In addition, we propose a new lightweight filtering-based loop closing technique to reduce accumulated drift without global bundle adjustment. We formulate loop closure as EKF updates to optimally relocate the current sliding window maintained by the filter to past keyframes. We also present the PerceptIn Ironsides dataset, a new visual-inertial dataset, featuring high-quality synchronized stereo camera and IMU data from the Ironsides sensor with various motion types and textures and millimeter-accuracy groundtruth. To validate the performance of the proposed system, we conduct extensive comparison with state-of-the-art approaches (OKVIS, VINS-MONO and S-MSCKF) using both the public EuRoC dataset and the PerceptIn Ironsides dataset.

##### Abstract (translated by Google)
在本文中，我们将介绍PerceptIn Visual Inertial Odometry（PI-VIO），这是一种使用点和线的紧耦合滤波立体声VIO系统。当点特征不能可靠地检测或跟踪时，线特征有助于提高在具有挑战性的场景中的系统鲁棒性。低质感环境或照明变化。另外，我们提出了一种新的基于轻量级滤波的环路闭合技术，以减少累积漂移而无需全局捆绑调整我们将EKF更新制定为闭环，以便将由过滤器维护的当前滑动窗口最优地重新定位到过去的关键帧。我们还提出了PerceptIn铁甲军数据集，一个新的视觉惯性数据集，从铁甲军传感器与各种运动类型和纹理和毫米精度地面实况具有高品质的同步立体相机和IMU数据。为了验证所提出的系统的性能，我们使用公共EuRoC数据集和PerceptIn Ironsides数据集进行了与最先进方法（OKVIS，VINS-MONO和S-MSCKF）的广泛比较。

##### URL
[http://arxiv.org/abs/1803.02403](http://arxiv.org/abs/1803.02403)

##### PDF
[http://arxiv.org/pdf/1803.02403](http://arxiv.org/pdf/1803.02403)

