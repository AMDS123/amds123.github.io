---
layout: post
title: "Direct Sparse Odometry"
date: 2016-10-07 04:31:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Tracking Optimization Detection
author: Jakob Engel, Vladlen Koltun, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel direct sparse visual odometry formulation. It combines a fully direct probabilistic model (minimizing a photometric error) with consistent, joint optimization of all model parameters, including geometry -- represented as inverse depth in a reference frame -- and camera motion. This is achieved in real time by omitting the smoothness prior used in other direct methods and instead sampling pixels evenly throughout the images. Since our method does not depend on keypoint detectors or descriptors, it can naturally sample pixels from across all image regions that have intensity gradient, including edges or smooth intensity variations on mostly white walls. The proposed model integrates a full photometric calibration, accounting for exposure time, lens vignetting, and non-linear response functions. We thoroughly evaluate our method on three different datasets comprising several hours of video. The experiments show that the presented approach significantly outperforms state-of-the-art direct and indirect methods in a variety of real-world settings, both in terms of tracking accuracy and robustness.

##### Abstract (translated by Google)
我们提出了一种新颖的直接稀疏视觉测距法。它将完全直接的概率模型（使光度误差最小化）与所有模型参数（包括几何参数 - 表示为参考帧中的反向深度）以及相机运动的一致性联合优化相结合。这是通过省略先前在其他直接方法中使用的平滑度而实时实现的，而是在整个图像中均匀地采样像素。由于我们的方法不依赖于关键点检测器或描述符，所以它可以自然地从具有强度梯度的所有图像区域采样像素，包括在大多数白色墙壁上的边缘或平滑的强度变化。所提出的模型集成了全面的光度校准，考虑曝光时间，镜头渐晕和非线性响应函数。我们通过三个不同的数据集彻底评估我们的方法，包括几个小时的视频。实验表明，在跟踪精度和鲁棒性方面，所提出的方法在各种现实世界设置中明显优于最先进的直接和间接方法。

##### URL
[https://arxiv.org/abs/1607.02565](https://arxiv.org/abs/1607.02565)

##### PDF
[https://arxiv.org/pdf/1607.02565](https://arxiv.org/pdf/1607.02565)

