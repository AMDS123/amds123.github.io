---
layout: post
title: "LSTM-Based Zero-Velocity Detection for Robust Inertial Navigation"
date: 2018-07-13 20:25:18
categories: arXiv_RO
tags: arXiv_RO Object_Detection RNN Detection
author: Brandon Wagstaff, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to improve the accuracy of a zero-velocity-aided inertial navigation system (INS) by replacing the standard zero-velocity detector with a long short-term memory (LSTM) neural network. While existing threshold-based zero-velocity detectors are not robust to varying motion types, our learned model accurately detects stationary periods of the inertial measurement unit (IMU) despite changes in the motion of the user. Upon detection, zero-velocity pseudo-measurements are fused with a dead reckoning motion model in an extended Kalman filter (EKF). We demonstrate that our LSTM-based zero-velocity detector, used within a zero-velocity-aided INS, improves zero-velocity detection during human localization tasks. Consequently, localization accuracy is also improved. 
 Our system is evaluated on more than 7.5 km of indoor pedestrian locomotion data, acquired from five different subjects. We show that 3D positioning error is reduced by over 34% compared to existing fixed-threshold zero-velocity detectors for walking, running, and stair climbing motions. Additionally, we demonstrate how our learned zero-velocity detector operates effectively during crawling and ladder climbing. Our system is calibration-free (no careful threshold-tuning is required) and operates consistently with differing users, IMU placements, and shoe types, while being compatible with any generic zero-velocity-aided INS.

##### Abstract (translated by Google)
我们提出了一种通过用长短期记忆（LSTM）神经网络代替标准零速度探测器来提高零速辅助惯性导航系统（INS）精度的方法。虽然现有的基于阈值的零速度检测器对于变化的运动类型不稳健，但是我们的学习模型准确地检测惯性测量单元（IMU）的静止周期，尽管用户的运动发生变化。在检测时，零速度伪测量与扩展卡尔曼滤波器（EKF）中的航位推算运动模型融合。我们证明了我们基于LSTM的零速度探测器，在零速度辅助INS中使用，改善了人类定位任务期间的零速度检测。因此，定位精度也得到改善。
 我们的系统通过从五个不同科目获得的超过7.5公里的室内行人运动数据进行评估。我们表明，与用于步行，跑步和爬楼梯运动的现有固定阈值零速度探测器相比，3D定位误差减少了34％以上。此外，我们还展示了我们学习的零速度探测器在爬行和爬梯过程中如何有效运行。我们的系统无需校准（无需仔细调整阈值），并可与不同的用户，IMU放置和鞋类型一致运行，同时兼容任何通用的零速辅助INS。

##### URL
[http://arxiv.org/abs/1807.05275](http://arxiv.org/abs/1807.05275)

##### PDF
[http://arxiv.org/pdf/1807.05275](http://arxiv.org/pdf/1807.05275)

