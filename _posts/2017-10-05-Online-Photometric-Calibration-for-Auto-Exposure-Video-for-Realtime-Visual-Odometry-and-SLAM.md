---
layout: post
title: "Online Photometric Calibration for Auto Exposure Video for Realtime Visual Odometry and SLAM"
date: 2017-10-05 15:49:13
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Paul Bergmann, Rui Wang, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Recent direct visual odometry and SLAM algorithms have demonstrated impressive levels of precision. However, they require a photometric camera calibration in order to achieve competitive results. Hence, the respective algorithm cannot be directly applied to an off-the-shelf-camera or to a video sequence acquired with an unknown camera. In this work we propose a method for online photometric calibration which enables to process auto exposure videos with visual odometry precisions that are on par with those of photometrically calibrated videos. Our algorithm recovers the exposure times of consecutive frames, the camera response function, and the attenuation factors of the sensor irradiance due to vignetting. Gain robust KLT feature tracks are used to obtain scene point correspondences as input to a nonlinear optimization framework. We show that our approach can reliably calibrate arbitrary video sequences by evaluating it on datasets for which full photometric ground truth is available. We further show that our calibration can improve the performance of a state-of-the-art direct visual odometry method that works solely on pixel intensities, calibrating for photometric parameters in an online fashion in realtime.

##### Abstract (translated by Google)
最近的直观视觉测距和SLAM算法已经证明了令人印象深刻的精度。然而，他们需要一个光度计相机校准，以取得竞争的结果。因此，相应的算法不能直接应用于现成的照相机或者用未知的照相机获取的视频序列。在这项工作中，我们提出了一种在线光度测量校准方法，该方法能够以视觉测距精度处理与光度测量校准视频相同的自动曝光视频。我们的算法可以恢复连续帧的曝光时间，相机响应函数以及由渐晕引起的传感器辐照度的衰减因子。增益鲁棒KLT特征轨道用于获取场景点对应作为非线性优化框架的输入。我们表明，我们的方法可以可靠地校准任意视频序列，通过评估数据集上的全光度地面真实可用。我们进一步表明，我们的校准可以提高最先进的直接视觉测距方法的性能，该方法仅仅在像素强度上工作，以在线方式实时校准光度参数。

##### URL
[https://arxiv.org/abs/1710.02081](https://arxiv.org/abs/1710.02081)

##### PDF
[https://arxiv.org/pdf/1710.02081](https://arxiv.org/pdf/1710.02081)

