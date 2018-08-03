---
layout: post
title: "Online Temporal Calibration for Monocular Visual-Inertial Systems"
date: 2018-08-02 07:16:25
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Tong Qin, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate state estimation is a fundamental module for various intelligent applications, such as robot navigation, autonomous driving, virtual and augmented reality. Visual and inertial fusion is a popular technology for 6-DOF state estimation in recent years. Time instants at which different sensors' measurements are recorded are of crucial importance to the system's robustness and accuracy. In practice, timestamps of each sensor typically suffer from triggering and transmission delays, leading to temporal misalignment (time offsets) among different sensors. Such temporal offset dramatically influences the performance of sensor fusion. To this end, we propose an online approach for calibrating temporal offset between visual and inertial measurements. Our approach achieves temporal offset calibration by jointly optimizing time offset, camera and IMU states, as well as feature locations in a SLAM system. Furthermore, the approach is a general model, which can be easily employed in several feature-based optimization frameworks. Simulation and experimental results demonstrate the high accuracy of our calibration approach even compared with other state-of-art offline tools. The VIO comparison against other methods proves that the online temporal calibration significantly benefits visual-inertial systems. The source code of temporal calibration is integrated into our public project, VINS-Mono.

##### Abstract (translated by Google)
准确的状态估计是各种智能应用的基本模块，例如机器人导航，自动驾驶，虚拟和增强现实。视觉和惯性融合是近年来用于6-DOF状态估计的流行技术。记录不同传感器测量值的时间瞬间对系统的稳健性和准确性至关重要。实际上，每个传感器的时间戳通常遭受触发和传输延迟，导致不同传感器之间的时间错位（时间偏移）。这种时间偏移显着影响传感器融合的性能。为此，我们提出了一种在线方法，用于校准视觉和惯性测量之间的时间偏移。我们的方法通过联合优化时间偏移，相机和IMU状态以及SLAM系统中的特征位置来实现时间偏移校准。此外，该方法是一种通用模型，可以在几个基于特征的优化框架中轻松使用。仿真和实验结果表明，与其他最先进的离线工具相比，我们的校准方法具有高精度。 VIO与其他方法的比较证明，在线时间校准显着有利于视觉惯性系统。时间校准的源代码已集成到我们的公共项目VINS-Mono中。

##### URL
[http://arxiv.org/abs/1808.00692](http://arxiv.org/abs/1808.00692)

##### PDF
[http://arxiv.org/pdf/1808.00692](http://arxiv.org/pdf/1808.00692)

