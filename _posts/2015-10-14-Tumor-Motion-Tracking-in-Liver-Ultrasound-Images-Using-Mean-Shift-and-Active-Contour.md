---
layout: post
title: "Tumor Motion Tracking in Liver Ultrasound Images Using Mean Shift and Active Contour"
date: 2015-10-14 23:15:38
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Jalil Rasekhi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a new method for motion tracking of tumors in liver ultrasound image sequences. Our algorithm has two main steps. In the first step, we apply mean shift algorithm with multiple features to estimate the center of the target in each frame. Target in the first frame is defined using an ellipse. Edge, texture, and intensity features are extracted from the first frame, and then mean shift algorithm is applied to each feature separately to find the center of ellipse related to that feature in the next frame. The center of ellipse will be the weighted average of these centers. By using mean shift actually we estimate the target movement between two consecutive frames. Once the correct ellipsoid in each frame is known, in the second step we apply the Dynamic Directional Gradient Vector Flow (DDGVF) version of active contour models, in order to find the correct boundary of tumors. We sample a few points on the boundary of active contour then translate those points based on the translation of the center of ellipsoid in two consecutive frames to determine the target movement. We use these translated sample points as an initial guess for active contour in the next frame. Our experimental results show that, the suggested method provides a reliable performance for liver tumor tracking in ultrasound image sequences.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的肝脏超声图像序列中的肿瘤运动跟踪方法。我们的算法有两个主要步骤。在第一步中，我们应用多特征的均值漂移算法来估计每帧中目标的中心。第一帧中的目标是使用椭圆定义的。从第一帧中提取边缘，纹理和亮度特征，然后分别对每个特征应用均值漂移算法，在下一帧中找到与该特征相关的椭圆的中心。椭圆的中心将是这些中心的加权平均值。实际上通过使用均值偏移，我们估计两个连续帧之间的目标移动。一旦每帧中的正确椭球体已知，在第二步中，我们应用动态方向梯度矢量流（DDGVF）版本的活动轮廓模型，以找到正确的肿瘤边界。我们在活动轮廓的边界上采样几个点，然后根据两个连续帧中椭球体中心的平移来转换这些点，以确定目标运动。我们使用这些已翻译的样本点作为下一帧中活动轮廓的初始猜测。实验结果表明，所提出的方法为超声图像序列中的肝脏肿瘤跟踪提供了可靠的性能。

##### URL
[https://arxiv.org/abs/1509.00154](https://arxiv.org/abs/1509.00154)

##### PDF
[https://arxiv.org/e-print/1509.00154](https://arxiv.org/e-print/1509.00154)

