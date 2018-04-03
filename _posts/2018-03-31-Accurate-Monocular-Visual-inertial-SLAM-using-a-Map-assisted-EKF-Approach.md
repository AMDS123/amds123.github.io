---
layout: post
title: "Accurate Monocular Visual-inertial SLAM using a Map-assisted EKF Approach"
date: 2018-03-31 11:56:03
categories: arXiv_RO
tags: arXiv_RO Detection SLAM
author: Meixiang Quan, Songhao Piao, Minglang Tan, Shi-Sheng Huang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel tightly-coupled monocular visual-inertial Simultaneous Localization and Mapping algorithm, which provides accurate and robust localization within the globally consistent map in real time on a standard CPU. This is achieved by firstly performing the visual-inertial extended kalman filter(EKF) to provide motion estimate at a high rate. However the filter becomes inconsistent due to the well known linearization issues. So we perform a keyframe-based visual-inertial bundle adjustment to improve the consistency and accuracy of the system. In addition, a loop closure detection and correction module is also added to eliminate the accumulated drift when revisiting an area. Finally, the optimized motion estimates and map are fed back to the EKF-based visual-inertial odometry module, thus the inconsistency and estimation error of the EKF estimator are reduced. In this way, the system can continuously provide reliable motion estimates for the long-term operation. The performance of the algorithm is validated on public datasets and real-world experiments, which proves the superiority of the proposed algorithm.

##### Abstract (translated by Google)
本文提出了一种新颖的紧耦合单目视觉 - 惯性同时定位和映射算法，该算法在标准CPU上实时地在全局一致的地图内提供精确和鲁棒的定位。这是通过首先执行视觉惯性扩展卡尔曼滤波器（EKF）以高速提供运动估计来实现的。然而，由于众所周知的线性化问题，滤波器变得不一致。所以我们执行基于关键帧的视觉 - 惯性束调整来提高系统的一致性和准确性。此外，还增加了闭环检测和校正模块，以消除重新访问区域时的累积漂移。最后，将优化运动估计和映射反馈给基于EKF的视觉 - 惯性测距模块，从而减少EKF估计器的不一致性和估计误差。这样，该系统可以连续地为长期操作提供可靠的运动估计。该算法的性能在公开数据集和实际实验中得到验证，证明了该算法的优越性。

##### URL
[http://arxiv.org/abs/1706.03648](http://arxiv.org/abs/1706.03648)

##### PDF
[http://arxiv.org/pdf/1706.03648](http://arxiv.org/pdf/1706.03648)

