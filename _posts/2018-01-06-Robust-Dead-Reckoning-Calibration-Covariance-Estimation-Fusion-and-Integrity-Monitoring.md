---
layout: post
title: "Robust Dead Reckoning: Calibration, Covariance Estimation, Fusion and Integrity Monitoring"
date: 2018-01-06 17:50:02
categories: arXiv_RO
tags: arXiv_RO Relation
author: Maximilian Harr, Christoph Schaefer
mathjax: true
---

* content
{:toc}

##### Abstract
To measure system states and local environment directly with high precision, expensive sensors are required. However, highly accurate system states and environmental perception can also be achieved using data fusion techniques and digital maps. One crucial task of multi-sensor state estimation is to project different sensor measurements into the same temporal, spatial and physical domain, estimate their covariance matrices as well as the exclusion of erroneous measurements. This paper presents a generic approach for robust estimation of vehicle movement (odometry). We will shortly present our calibration procedure, including the estimation of sensor alignments, offset / scaling errors, covariances / correlations and time delays. An improved algorithm for wheel diameter estimation is presented. Additionally an approach for robust odometry will be shown as odometry estimations are fused under known covariances, while outliers are detected using a chi-squared test. Utilizing our robust odometry, local environmental views can be associated and fused. Furthermore our robust odometry can be used to detect and exclude erroneous position estimates.

##### Abstract (translated by Google)
为了以高精度直接测量系统状态和本地环境，需要昂贵的传感器。然而，使用数据融合技术和数字地图也可以实现高度准确的系统状态和环境感知。多传感器状态估计的一个关键任务是将不同的传感器测量结果投影到相同的时间，空间和物理域中，估计它们的协方差矩阵以及排除错误的测量结果。本文提出了一种通用的方法来稳健估计车辆的运动（odometry）。我们将很快呈现我们的校准程序，包括传感器对齐的估计，偏移/缩放误差，协方差/相关性和时间延迟。提出了一种改进的车轮直径估计算法。此外，将显示用于稳健测距的方法，因为测距估计在已知协方差下融合，而使用卡方检验来检测异常值。利用我们强大的测距仪，当地的环境意见可以相关联和融合。此外，我们强大的测距法可以用来检测和排除错误的位置估计。

##### URL
[http://arxiv.org/abs/1801.02058](http://arxiv.org/abs/1801.02058)

##### PDF
[http://arxiv.org/pdf/1801.02058](http://arxiv.org/pdf/1801.02058)

