---
layout: post
title: "Build Your Own Visual-Inertial Drone: A Cost-Effective and Open-Source Autonomous Drone"
date: 2018-09-06 17:50:35
categories: arXiv_RO
tags: arXiv_RO Drone
author: Inkyu Sa, Mina Kamel, Michael Burri, Michael Bloesch, Raghav Khanna, Marija Popovic, Juan Nieto, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes an approach to building a cost-effective and research grade visual-inertial odometry aided vertical taking-off and landing (VTOL) platform. We utilize an off-the-shelf visual-inertial sensor, an onboard computer, and a quadrotor platform that are factory-calibrated and mass-produced, thereby sharing similar hardware and sensor specifications (e.g., mass, dimensions, intrinsic and extrinsic of camera-IMU systems, and signal-to-noise ratio). We then perform a system calibration and identification enabling the use of our visual-inertial odometry, multi-sensor fusion, and model predictive control frameworks with the off-the-shelf products. This implies that we can partially avoid tedious parameter tuning procedures for building a full system. The complete system is extensively evaluated both indoors using a motion capture system and outdoors using a laser tracker while performing hover and step responses, and trajectory following tasks in the presence of external wind disturbances. We achieve root-mean-square (RMS) pose errors between a reference and actual trajectories of 0.036m, while performing hover. We also conduct relatively long distance flight (~180m) experiments on a farm site and achieve 0.82% drift error of the total distance flight. This paper conveys the insights we acquired about the platform and sensor module and returns to the community as open-source code with tutorial documentation.

##### Abstract (translated by Google)
本文描述了一种建立具有成本效益和研究级视觉惯性测距辅助垂直起飞和着陆（VTOL）平台的方法。我们利用现成的视觉惯性传感器，车载计算机和四旋翼平台进行工厂校准和批量生产，从而共享类似的硬件和传感器规格（例如，相机的质量，尺寸，内在和外在性） -IMU系统和信噪比）。然后，我们执行系统校准和识别，使我们的视觉惯性测距法，多传感器融合和模型预测控制框架与现成产品一起使用。这意味着我们可以部分避免繁琐的参数调整过程来构建完整的系统。整个系统在室内使用运动捕捉系统和室外使用激光跟踪器进行广泛评估，同时执行悬停和阶跃响应，以及在存在外部风扰动时跟踪任务的轨迹。我们在执行悬停时实现0.036米的参考轨迹和实际轨迹之间的均方根（RMS）姿态误差。我们还在农场进行了相对长距离飞行（~180米）的实验，并实现了总距离飞行的0.82％漂移误差。本文传达了我们获得的关于平台和传感器模块的见解，并作为带有教程文档的开源代码返回社区。

##### URL
[http://arxiv.org/abs/1708.06652](http://arxiv.org/abs/1708.06652)

##### PDF
[http://arxiv.org/pdf/1708.06652](http://arxiv.org/pdf/1708.06652)

