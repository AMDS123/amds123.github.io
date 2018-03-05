---
layout: post
title: "SCALAR - Simultaneous Calibration of 2D Laser and Robot's Kinematic Parameters Using Three Planar Constraints"
date: 2018-03-02 08:05:49
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Teguh Santoso Lembono, Fransisco Suarez-Ruiz, Quang-Cuong Pham
mathjax: true
---

* content
{:toc}

##### Abstract
Industrial robots are increasingly used in various applications where the robot accuracy becomes very important, hence calibrations of the robot's kinematic parameters and the measurement system's extrinsic parameters are required. However, the existing calibration approaches are either too cumbersome or require another expensive external measurement system such as laser tracker or measurement spinarm. In this paper, we propose SCALAR, a calibration method to simultaneously improve the kinematic parameters of a 6-DoF robot and the extrinsic parameters of a 2D Laser Range Finder (LRF) which is attached to the robot. Three flat planes are placed around the robot, and for each plane the robot moves to several poses such that the LRF's ray intersect the respective plane. Geometric planar constraints are then used to optimize the calibration parameters using Levenberg- Marquardt nonlinear optimization algorithm. We demonstrate through simulations that SCALAR can reduce the average position and orientation errors of the robot system from 14.6mm and 4.05 degrees to 0.09mm and 0.02 degrees.

##### Abstract (translated by Google)
工业机器人越来越多地应用于机器人精度变得非常重要的各种应用中，因此需要对机器人的运动参数和测量系统的外部参数进行校准。但是，现有的校准方法要么太麻烦，要么需要另外昂贵的外部测量系统，如激光跟踪仪或测量旋臂。在本文中，我们提出了SCALAR，这是一种校准方法，可同时改善6-DoF机器人的运动学参数和连接到机器人的2D激光测距仪（LRF）的外部参数。机器人周围放置三个平面，每个平面机器人移动到几个姿势，使得LRF的射线与相应的平面相交。然后使用几何平面约束来使用Levenberg-Marquardt非线性优化算法优化校准参数。我们通过模拟演示了SCALAR可以将机器人系统的平均位置和方向误差从14.6mm和4.05度降低到0.09mm和0.02度。

##### URL
[http://arxiv.org/abs/1803.00747](http://arxiv.org/abs/1803.00747)

##### PDF
[http://arxiv.org/pdf/1803.00747](http://arxiv.org/pdf/1803.00747)

