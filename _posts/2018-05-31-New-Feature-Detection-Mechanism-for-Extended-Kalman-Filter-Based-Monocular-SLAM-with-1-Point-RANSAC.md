---
layout: post
title: "New Feature Detection Mechanism for Extended Kalman Filter Based Monocular SLAM with 1-Point RANSAC"
date: 2018-05-31 12:49:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection SLAM
author: Agniva Sengupta, Shafeeq Elanattil
mathjax: true
---

* content
{:toc}

##### Abstract
We present a different approach of feature point detection for improving the accuracy of SLAM using single, monocular camera. Traditionally, Harris Corner detection, SURF or FAST corner detectors are used for finding feature points of interest in the image. We replace this with another approach, which involves building a non-linear scale-space representation of images using Perona and Malik Diffusion equation and computing the scale normalized Hessian at multiple scale levels (KAZE feature). The feature points so detected are used to estimate the state and pose of a mono camera using extended Kalman filter. By using accelerated KAZE features and a more rigorous feature rejection routine combined with 1-point RANSAC for outlier rejection, short baseline matching of features are significantly improved, even with a lesser number of feature points, especially in the presence of motion blur. We present a comparative study of our proposal with FAST and show improved localization accuracy in terms of absolute trajectory error.

##### Abstract (translated by Google)
我们提出了一种不同的特征点检测方法，以提高使用单个单目照相机的SLAM的精度。传统上，Harris Corner检测，SURF或FAST角点检测器用于查找图像中感兴趣的特征点。我们用另一种方法取代这种方法，该方法涉及使用Perona和Malik扩散方程来构建图像的非线性尺度空间表示，并且在多个尺度水平（KAZE特征）下计算尺度标准化的Hessian。如此检测的特征点被用来使用扩展卡尔曼滤波器来估计单相机的状态和姿态。通过使用加速的KAZE特征和更加严格的特征拒绝例程以及1点RANSAC异常排斥，即使特征点数量较少，特征的短基线匹配也会得到显着改善，特别是在存在运动模糊的情况下。我们用FAST提出了我们提案的比较研究，并且在绝对轨迹误差方面显示了改进的定位精度。

##### URL
[http://arxiv.org/abs/1805.12443](http://arxiv.org/abs/1805.12443)

##### PDF
[http://arxiv.org/pdf/1805.12443](http://arxiv.org/pdf/1805.12443)

