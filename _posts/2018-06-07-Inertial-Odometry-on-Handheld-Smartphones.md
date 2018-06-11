---
layout: post
title: "Inertial Odometry on Handheld Smartphones"
date: 2018-06-07 20:40:20
categories: arXiv_CV
tags: arXiv_CV Inference
author: Arno Solin, Santiago Cortes, Esa Rahtu, Juho Kannala
mathjax: true
---

* content
{:toc}

##### Abstract
Building a complete inertial navigation system using the limited quality data provided by current smartphones has been regarded challenging, if not impossible. This paper shows that by careful crafting and accounting for the weak information in the sensor samples, smartphones are capable of pure inertial navigation. We present a probabilistic approach for orientation and use-case free inertial odometry, which is based on double-integrating rotated accelerations. The strength of the model is in learning additive and multiplicative IMU biases online. We are able to track the phone position, velocity, and pose in real-time and in a computationally lightweight fashion by solving the inference with an extended Kalman filter. The information fusion is completed with zero-velocity updates (if the phone remains stationary), altitude correction from barometric pressure readings (if available), and pseudo-updates constraining the momentary speed. We demonstrate our approach using an iPad and iPhone in several indoor dead-reckoning applications and in a measurement tool setup.

##### Abstract (translated by Google)
使用当前智能手​​机提供的有限质量数据构建完整的惯性导航系统，即使不是不可能，也被视为具有挑战性。本文表明，通过精心设计和计算传感器样本中的弱信息，智能手机能够实现纯粹的惯性导航。我们提出了一种基于双积分旋转加速度的定向和用例自由惯性测距的概率方法。该模型的优势在于在线学习加法和乘法IMU偏差。通过使用扩展卡尔曼滤波器进行推理，我们可以实时跟踪手机的位置，速度和姿态，并以计算轻量级的方式进行跟踪。信息融合通过零速度更新（如果手机保持静止），气压读数的高度修正（如果可用）和限制瞬时速度的伪更新完成。我们展示了我们在几种室内航位推测应用和测量工具设置中使用iPad和iPhone的方法。

##### URL
[http://arxiv.org/abs/1703.00154](http://arxiv.org/abs/1703.00154)

##### PDF
[http://arxiv.org/pdf/1703.00154](http://arxiv.org/pdf/1703.00154)

