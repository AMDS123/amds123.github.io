---
layout: post
title: "Visual-Inertial Monocular SLAM with Map Reuse"
date: 2017-01-17 15:45:14
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Raul Mur-Artal, Juan D. Tardos
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years there have been excellent results in Visual-Inertial Odometry techniques, which aim to compute the incremental motion of the sensor with high accuracy and robustness. However these approaches lack the capability to close loops, and trajectory estimation accumulates drift even if the sensor is continually revisiting the same place. In this work we present a novel tightly-coupled Visual-Inertial Simultaneous Localization and Mapping system that is able to close loops and reuse its map to achieve zero-drift localization in already mapped areas. While our approach can be applied to any camera configuration, we address here the most general problem of a monocular camera, with its well-known scale ambiguity. We also propose a novel IMU initialization method, which computes the scale, the gravity direction, the velocity, and gyroscope and accelerometer biases, in a few seconds with high accuracy. We test our system in the 11 sequences of a recent micro-aerial vehicle public dataset achieving a typical scale factor error of 1% and centimeter precision. We compare to the state-of-the-art in visual-inertial odometry in sequences with revisiting, proving the better accuracy of our method due to map reuse and no drift accumulation.

##### Abstract (translated by Google)
近年来，在视觉惯性内测技术方面取得了很好的成果，其目的是以高精度和高鲁棒性来计算传感器的增量运动。然而，这些方法缺乏闭合回路的能力，并且即使传感器不断地重新访问相同的位置，轨迹估计也会积累漂移。在这项工作中，我们提出了一个新颖的紧耦合的视觉惯性同时定位和映射系统，能够闭合循环，并重新使用其地图，以实现零漂定位已映射区域。虽然我们的方法可以应用于任何相机配置，但我们在这里解决单眼相机最普遍的问题，其众所周知的尺度模糊性。我们还提出了一种新颖的IMU初始化方法，它能在几秒钟内高精度地计算出尺度，重力方向，速度，陀螺仪和加速度计偏差。我们在最近微型飞行器公共数据集的11个序列中测试了我们的系统，实现了1％和厘米精度的典型比例因子误差。我们比较视觉惯性测深法中的先进视觉惯性测距法，并重新验证了由于地图重复使用和无漂移累积而提高了我们方法的准确性。

##### URL
[https://arxiv.org/abs/1610.05949](https://arxiv.org/abs/1610.05949)

##### PDF
[https://arxiv.org/pdf/1610.05949](https://arxiv.org/pdf/1610.05949)

