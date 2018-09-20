---
layout: post
title: "Trifo-VIO: Robust and Efficient Stereo Visual Inertial Odometry using Points and Lines"
date: 2018-09-18 23:05:27
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Feng Zheng, Grace Tsai, Zhe Zhang, Shaoshan Liu, Chen-Chi Chu, Hongbing Hu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present the Trifo Visual Inertial Odometry (Trifo-VIO), a tightly-coupled filtering-based stereo VIO system using both points and lines. Line features help improve system robustness in challenging scenarios when point features cannot be reliably detected or tracked, e.g. low-texture environment or lighting change. In addition, we propose a novel lightweight filtering-based loop closing technique to reduce accumulated drift without global bundle adjustment or pose graph optimization. We formulate loop closure as EKF updates to optimally relocate the current sliding window maintained by the filter to past keyframes. We also present the Trifo Ironsides dataset, a new visual-inertial dataset, featuring high-quality synchronized stereo camera and IMU data from the Ironsides sensor [3] with various motion types and textures and millimeter-accuracy groundtruth. To validate the performance of the proposed system, we conduct extensive comparison with state-of-the-art approaches (OKVIS, VINS-MONO and S-MSCKF) using both the public EuRoC dataset and the Trifo Ironsides dataset.

##### Abstract (translated by Google)
在本文中，我们介绍了Trifo Visual Inertial Odometry（Trifo-VIO），这是一种使用点和线的紧密耦合滤波立体声VIO系统。当无法可靠地检测或跟踪点特征时，线特征有助于在挑战性场景中提高系统稳健性，例如，低纹理环境或照明变化。此外，我们提出了一种新颖的基于轻量级滤波的闭环技术，可以在不进行全局束调整或姿势图优化的情况下减少累积漂移。我们在EKF更新时制定循环闭包，以便将过滤器维护的当前滑动窗口最佳地重新定位到过去的关键帧。我们还提供了Trifo Ironsides数据集，这是一个新的视觉惯性数据集，具有来自Ironsides传感器[3]的高质量同步立体相机和IMU数据，具有各种运动类型和纹理以及毫米级精度的groundtruth。为了验证所提出系统的性能，我们使用公共EuRoC数据集和Trifo Ironsides数据集对最先进的方法（OKVIS，VINS-MONO和S-MSCKF）进行了广泛的比较。

##### URL
[http://arxiv.org/abs/1803.02403](http://arxiv.org/abs/1803.02403)

##### PDF
[http://arxiv.org/pdf/1803.02403](http://arxiv.org/pdf/1803.02403)

