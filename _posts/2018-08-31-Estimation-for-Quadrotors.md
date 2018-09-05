---
layout: post
title: "Estimation for Quadrotors"
date: 2018-08-31 19:27:08
categories: arXiv_RO
tags: arXiv_RO Knowledge Drone
author: Stefanie Tellex, Andy Brown, Sergei Lupashin
mathjax: true
---

* content
{:toc}

##### Abstract
This document describes standard approaches for filtering and estimation for quadrotors, created for the Udacity Flying Cars course. We assume previous knowledge of probability and some knowledge of linear algebra. We do not assume previous knowledge of Kalman filters or Bayes filters. This document derives an EKF for various models of drones in 1D, 2D, and 3D. We use the EKF and notation as defined in Thrun et al. [13]. We also give pseudocode for the Bayes filter, the EKF, and the Unscented Kalman filter [14]. The motivation behind this document is the lack of a step-by-step EKF tutorial that provides the derivations for a quadrotor helicopter. The goal of estimation is to infer the drone's state (pose, velocity, acceleration, and biases) from its sensor values and control inputs. This problem is challenging because sensors are noisy. Additionally, because of weight and cost issues, many drones have limited on-board computation so we want to estimate these values as quickly as possible. The standard method for performing this method is the Extended Kalman filter, a nonlinear extension of the Kalman filter which linearizes a nonlinear transition and measurement model around the current state. However the Unscented Kalman filter is better in almost every respect: simpler to implement, more accurate to estimate, and comparable runtimes.

##### Abstract (translated by Google)
本文档描述了为Udacity Flying Cars课程创建的用于四旋翼飞行器滤波和估算的标准方法。我们假设先前的概率知识和线性代数的一些知识。我们不假设先前有关卡尔曼滤波器或贝叶斯滤波器的知识。本文档为一维，二维和三维无人机模型推导出一个EKF。我们使用Thrun等人定义的EKF和符号。 [13]。我们还给贝叶斯滤波器，EKF和Unscented卡尔曼滤波器[14]提供了伪码。这份文件背后的动机是缺乏一步一步的EKF教程，该教程为四旋翼直升机提供了推导。估计的目标是从其传感器值和控制输入推断出无人机的状态（姿势，速度，加速度和偏差）。这个问题具有挑战性，因为传感器很嘈杂。此外，由于重量和成本问题，许多无人机限制了机载计算，因此我们希望尽快估算这些值。执行该方法的标准方法是扩展卡尔曼滤波器，卡尔曼滤波器的非线性扩展，其线性化围绕当前状态的非线性转换和测量模型。然而，Unscented卡尔曼滤波器在几乎所有方面都更好：实现更简单，估计更准确，运行时间相当。

##### URL
[http://arxiv.org/abs/1809.00037](http://arxiv.org/abs/1809.00037)

##### PDF
[http://arxiv.org/pdf/1809.00037](http://arxiv.org/pdf/1809.00037)

