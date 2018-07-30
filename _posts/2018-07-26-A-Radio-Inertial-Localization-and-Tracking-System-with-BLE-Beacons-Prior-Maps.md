---
layout: post
title: "A Radio-Inertial Localization and Tracking System with BLE Beacons Prior Maps"
date: 2018-07-26 21:30:14
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Maani Ghaffari Jadidi, Mitesh Patel, Jaime Valls Miro, Gamini Dissanayake, Jacob Biehl, Andreas Girgensohn
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a system for the low-cost indoor localization and tracking problem using radio signal strength indicator, Inertial Measurement Unit (IMU), and magnetometer sensors. We develop a novel and simplified probabilistic IMU motion model as the proposal distribution of the sequential Monte-Carlo technique to track the robot trajectory. Our algorithm can globally localize and track a robot with a priori unknown location, given an informative prior map of the Bluetooth Low Energy (BLE) beacons. Also, we formulate the problem as an optimization problem that serves as the Back-end of the algorithm mentioned above (Front-end). Thus, by simultaneously solving for the robot trajectory and the map of BLE beacons, we recover a continuous and smooth trajectory of the robot, corrected locations of the BLE beacons, and the time-varying IMU bias. The evaluations achieved using hardware show that through the proposed closed-loop system the localization performance can be improved; furthermore, the system becomes robust to the error in the map of beacons by feeding back the optimized map to the Front-end.

##### Abstract (translated by Google)
在本文中，我们使用无线电信号强度指示器，惯性测量单元（IMU）和磁力计传感器开发了一种低成本室内定位和跟踪问题的系统。我们开发了一种新颖且简化的概率IMU运动模型，作为跟踪机器人轨迹的顺序蒙特卡罗技术的提议分布。我们的算法可以全局定位和跟踪具有先验未知位置的机器人，给出蓝牙低能量（BLE）信标的信息性先前地图。此外，我们将问题表述为优化问题，作为上述算法的后端（前端）。因此，通过同时求解机器人轨迹和BLE信标的映射，我们恢复了机器人的连续且平滑的轨迹，校正了BLE信标的位置以及时变IMU偏差。使用硬件实现的评估表明，通过所提出的闭环系统，可以提高定位性能;此外，通过将优化的地图反馈给前端，系统对信标地图中的错误变得鲁棒。

##### URL
[http://arxiv.org/abs/1706.05569](http://arxiv.org/abs/1706.05569)

##### PDF
[http://arxiv.org/pdf/1706.05569](http://arxiv.org/pdf/1706.05569)

