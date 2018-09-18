---
layout: post
title: "Autonomous drone race: A computationally efficient vision-based navigation and control strategy"
date: 2018-09-16 21:17:52
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation Drone Prediction Detection
author: S.Li, M.M.O.I. Ozo, C. De Wagter, G.C.H.E. de Croon
mathjax: true
---

* content
{:toc}

##### Abstract
Drone racing is becoming a popular sport where human pilots have to control their drones to fly at high speed through complex environments and pass a number of gates in a pre-defined sequence. In this paper, we develop an autonomous system for drones to race fully autonomously using only onboard resources. Instead of commonly used visual navigation methods, such as simultaneous localization and mapping and visual inertial odometry, which are computationally expensive for micro aerial vehicles (MAVs), we developed the highly efficient snake gate detection algorithm for visual navigation, which can detect the gate at 20HZ on a Parrot Bebop drone. Then, with the gate detection result, we developed a robust pose estimation algorithm which has better tolerance to detection noise than a state-of-the-art perspective-n-point method. During the race, sometimes the gates are not in the drone's field of view. For this case, a state prediction-based feed-forward control strategy is developed to steer the drone to fly to the next gate. Experiments show that the drone can fly a half-circle with 1.5m radius within 2 seconds with only 30cm error at the end of the circle without any position feedback. Finally, the whole system is tested in a complex environment (a showroom in the faculty of Aerospace Engineering, TU Delft). The result shows that the drone can complete the track of 15 gates with a speed of 1.5m/s which is faster than the speeds exhibited at the 2016 and 2017 IROS autonomous drone races.

##### Abstract (translated by Google)
无人驾驶赛车正在成为一项受欢迎的运动，人类飞行员必须控制无人驾驶飞机在复杂的环境中高速飞行，并以预定的顺序通过多个大门。在本文中，我们开发了一个自主系统，用于无人机仅使用机载资源完全自主竞赛。我们开发了用于视觉导航的高效蛇门检测算法，而不是常用的视觉导航方法，例如同步定位和映射以及视觉惯性测距，这些算法对于微型飞行器（MAV）来说是计算上昂贵的，它可以检测到20HZ在鹦鹉Bebop无人机上。然后，利用门检测结果，我们开发了一种鲁棒的姿态估计算法，该算法比现有技术的透视n点方法具有更好的检测噪声容限。在比赛期间，有时大门不在无人机的视野中。对于这种情况，开发了基于状态预测的前馈控制策略，以引导无人机飞向下一个门。实验表明，无人机可以在2秒内以1.5米的半径飞行半圆，在圆的末端只有30厘米的误差，没有任何位置反馈。最后，整个系统在复杂的环境中进行测试（航空航天工程学院，代尔夫特理工大学的一个展厅）。结果表明，无人机可以以1.5m / s的速度完成15个门的轨道，这比2016和2017年IROS自主无人机比赛的速度更快。

##### URL
[http://arxiv.org/abs/1809.05958](http://arxiv.org/abs/1809.05958)

##### PDF
[http://arxiv.org/pdf/1809.05958](http://arxiv.org/pdf/1809.05958)

