---
layout: post
title: "Contact-Aided Invariant Extended Kalman Filtering for Legged Robot State Estimation"
date: 2018-05-26 01:58:02
categories: arXiv_RO
tags: arXiv_RO
author: Ross Hartley, Maani Ghaffari Jadidi, Jessy W. Grizzle, Ryan M. Eustice
mathjax: true
---

* content
{:toc}

##### Abstract
This paper derives a contact-aided inertial navigation observer for a 3D bipedal robot using the theory of invariant observer design. Aided inertial navigation is fundamentally a nonlinear observer design problem; thus, current solutions are based on approximations of the system dynamics, such as an Extended Kalman Filter (EKF), which uses a system's Jacobian linearization along the current best estimate of its trajectory. On the basis of the theory of invariant observer design by Barrau and Bonnabel, and in particular, the Invariant EKF (InEKF), we show that the error dynamics of the point contact-inertial system follows a log-linear autonomous differential equation; hence, the observable state variables can be rendered convergent with a domain of attraction that is independent of the system's trajectory. Due to the log-linear form of the error dynamics, it is not necessary to perform a nonlinear observability analysis to show that when using an Inertial Measurement Unit (IMU) and contact sensors, the absolute position of the robot and a rotation about the gravity vector (yaw) are unobservable. We further augment the state of the developed InEKF with IMU biases, as the online estimation of these parameters has a crucial impact on system performance. We evaluate the convergence of the proposed system with the commonly used quaternion-based EKF observer using a Monte-Carlo simulation. In addition, our experimental evaluation using a Cassie-series bipedal robot shows that the contact-aided InEKF provides better performance in comparison with the quaternion-based EKF as a result of exploiting symmetries present in the system dynamics.

##### Abstract (translated by Google)
本文利用不变观测器设计理论推导出一个三维双足机器人的接触辅助惯性导航观测器。辅助惯性导航基本上是一个非线性观测器设计问题;因此，当前的解决方案基于系统动力学的近似，例如扩展卡尔曼滤波器（EKF），其使用沿着其当前最佳估计的轨迹的系统的雅可比线性化。基于Barrau和Bonnabel不变式观察器设计理论，特别是不变EKF（InEKF），我们证明了点接触 - 惯性系统的误差动力学遵循对数线性自治微分方程;因此，可观察的状态变量可以与独立于系统轨迹的吸引域呈现收敛。由于误差动态的对数线性形式，没有必要执行非线性可观测性分析以表明当使用惯性测量单元（IMU）和接触传感器时，机器人的绝对位置和绕重力的旋转矢量（偏航）是不可观测的。由于在线估计这些参数对系统性能有至关重要的影响，因此我们进一步扩大了IME偏差的发展InEKF的状态。我们使用Monte-Carlo模拟来评估所提出的系统与常用的基于四元数的EKF观测器的收敛性。此外，使用Cassie系列双足机器人进行的实验评估表明，与基于四元数的EKF相比，由于利用了系统动力学中的对称性，接触辅助InEKF提供了更好的性能。

##### URL
[http://arxiv.org/abs/1805.10410](http://arxiv.org/abs/1805.10410)

##### PDF
[http://arxiv.org/pdf/1805.10410](http://arxiv.org/pdf/1805.10410)

