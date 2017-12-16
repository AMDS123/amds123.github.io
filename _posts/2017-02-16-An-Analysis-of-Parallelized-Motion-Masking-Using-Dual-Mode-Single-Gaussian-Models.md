---
layout: post
title: "An Analysis of Parallelized Motion Masking Using Dual-Mode Single Gaussian Models"
date: 2017-02-16 21:10:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Detection Recognition
author: Peter Henderson, Matthew Vertescher
mathjax: true
---

* content
{:toc}

##### Abstract
Motion detection in video is important for a number of applications and fields. In video surveillance, motion detection is an essential accompaniment to activity recognition for early warning systems. Robotics also has much to gain from motion detection and segmentation, particularly in high speed motion tracking for tactile systems. There are a myriad of techniques for detecting and masking motion in an image. Successful systems have used Gaussian Models to discern background from foreground in an image (motion from static imagery). However, particularly in the case of a moving camera or frame of reference, it is necessary to compensate for the motion of the camera when attempting to discern objects moving in the foreground. For example, it is possible to estimate motion of the camera through optical flow methods or temporal differencing and then compensate for this motion in a background subtraction model. We selection a method by Yi et al. using Dual-Mode Single Gaussian Models which does just this. We implement the technique in Intel's Thread Building Blocks (TBB) and NVIDIA's CUDA libraries. We then compare parallelization improvements with a theoretical analysis of speedups based on the characteristics of our selected model and attributes of both TBB and CUDA. We make our implementation available to the public.

##### Abstract (translated by Google)
视频中的运动检测对于许多应用和领域都很重要。在视频监控中，运动检测是早期预警系统活动识别的重要辅助手段。机器人技术在运动检测和分割方面也有很多的收获，特别是在触觉系统的高速运动跟踪方面。在图像中有无数的检测和遮蔽动作的技术。成功的系统已经使用高斯模型来从图像的前景中辨别背景（来自静态图像的运动）。但是，特别是在移动相机或参照系的情况下，当试图辨别在前景中移动的物体时，有必要补偿相机的运动。例如，可以通过光流法或时间差分来估计相机的运动，然后在背景减法模型中补偿该运动。我们选择了Yi等人的方法。使用双模单高斯模型。我们在英特尔的线程构建模块（TBB）和NVIDIA的CUDA库中实现了这项技术。然后根据我们选择的模型的特点和TBB和CUDA的属性，将并行化改进与加速的理论分析进行比较。我们使我们的实施面向公众。

##### URL
[https://arxiv.org/abs/1702.05156](https://arxiv.org/abs/1702.05156)

##### PDF
[https://arxiv.org/pdf/1702.05156](https://arxiv.org/pdf/1702.05156)

