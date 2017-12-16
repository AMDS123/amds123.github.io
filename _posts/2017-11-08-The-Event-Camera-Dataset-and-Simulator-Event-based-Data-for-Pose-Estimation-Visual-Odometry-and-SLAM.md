---
layout: post
title: "The Event-Camera Dataset and Simulator: Event-based Data for Pose Estimation, Visual Odometry, and SLAM"
date: 2017-11-08 08:40:14
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Quantitative SLAM
author: Elias Mueggler, Henri Rebecq, Guillermo Gallego, Tobi Delbruck, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
New vision sensors, such as the Dynamic and Active-pixel Vision sensor (DAVIS), incorporate a conventional global-shutter camera and an event-based sensor in the same pixel array. These sensors have great potential for high-speed robotics and computer vision because they allow us to combine the benefits of conventional cameras with those of event-based sensors: low latency, high temporal resolution, and very high dynamic range. However, new algorithms are required to exploit the sensor characteristics and cope with its unconventional output, which consists of a stream of asynchronous brightness changes (called "events") and synchronous grayscale frames. For this purpose, we present and release a collection of datasets captured with a DAVIS in a variety of synthetic and real environments, which we hope will motivate research on new algorithms for high-speed and high-dynamic-range robotics and computer-vision applications. In addition to global-shutter intensity images and asynchronous events, we provide inertial measurements and ground-truth camera poses from a motion-capture system. The latter allows comparing the pose accuracy of ego-motion estimation algorithms quantitatively. All the data are released both as standard text files and binary files (i.e., rosbag). This paper provides an overview of the available data and describes a simulator that we release open-source to create synthetic event-camera data.

##### Abstract (translated by Google)
诸如动​​态和有源像素视觉传感器（DAVIS）之类的新视觉传感器在同一像素阵列中包含传统的全局快门相机和基于事件的传感器。这些传感器具有高速机器人和计算机视觉的巨大潜力，因为它们使我们能够将传统相机的优点与基于事件的传感器相结合：低延迟，高时间分辨率和非常高的动态范围。然而，需要新的算法来利用传感器特性并应对其非常规输出，其由非同步亮度变化（称为“事件”）流和同步灰度帧组成。为此，我们在各种合成和真实环境中呈现和发布一系列用DAVIS捕获的数据集，我们希望能够推动对高速和高动态范围机器人和计算机视觉应用的新算法的研究。除了全局快门强度图像和异步事件外，我们还提供了运动捕捉系统的惯性测量和地面实况相机姿态。后者可以定量比较自我运动估计算法的姿态精度。所有数据都以标准文本文件和二进制文件（即rosbag）的形式发布。本文提供了可用数据的概述，并描述了一个模拟器，我们发布开放源代码以创建合成事件相机数据。

##### URL
[https://arxiv.org/abs/1610.08336](https://arxiv.org/abs/1610.08336)

##### PDF
[https://arxiv.org/pdf/1610.08336](https://arxiv.org/pdf/1610.08336)

