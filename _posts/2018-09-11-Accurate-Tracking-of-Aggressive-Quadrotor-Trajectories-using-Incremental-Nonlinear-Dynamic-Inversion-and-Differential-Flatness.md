---
layout: post
title: "Accurate Tracking of Aggressive Quadrotor Trajectories using Incremental Nonlinear Dynamic Inversion and Differential Flatness"
date: 2018-09-11 17:30:19
categories: arXiv_RO
tags: arXiv_RO Attention Tracking
author: Ezra Tal, Sertac Karaman
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous unmanned aerial vehicles (UAVs) that can execute aggressive (i.e., high-speed and high-acceleration) maneuvers have attracted significant attention in the past few years. In this paper, we propose a novel control law for accurate tracking of aggressive quadcopter trajectories. The proposed method tracks position and yaw angle with their derivatives of up to fourth order, specifically, the position, velocity, acceleration, jerk, and snap along with the yaw angle, yaw rate and yaw acceleration. Two key aspects of the proposed method are the following. First, the controller exploits the differential flatness of the quadcopter dynamics to generate feedforward inputs for attitude rate and attitude acceleration in order to track the jerk and snap references. The tracking is enabled by direct control of body torque using closed-loop control of all four propeller speeds based on optical encoders attached to the motors. Second, the controller utilizes the incremental nonlinear dynamic inversion (INDI) method for accurate tracking of linear and angular accelerations despite external disturbances. Hence, no prior modeling of aerodynamic effects is required. We rigorously analyze the proposed controller through response analysis, and we demonstrate it in experiments. The proposed control law enables a 1-kg quadcopter UAV to track complex 3D trajectories, reaching speeds up to 8.2 m/s and accelerations up to 2g, while keeping the root-mean-square tracking error down to 4 cm, in a flight volume that is roughly 6.5 m long, 6.5 m wide, and 1.5 m tall. We also demonstrate the robustness of the controller by attaching a drag plate to the UAV in flight tests and by pulling on the UAV with a rope during hover.

##### Abstract (translated by Google)
在过去几年中，能够执行激进（即高速和高加速）机动的自主无人驾驶飞行器（UAV）引起了极大的关注。在本文中，我们提出了一种新的控制律，用于准确跟踪侵略性四轴飞行器轨迹。所提出的方法跟踪位置和偏航角，其导数高达四阶，具体地，位置，速度，加速度，加加速度和弹簧以及偏航角，偏航率和偏航加速度。所提出的方法的两个关键方面如下。首先，控制器利用四轴飞行器动力学的差动平坦度来生成姿态速率和姿态加速度的前馈输入，以便跟踪加加速度和快速参考。基于连接到电机的光学编码器，使用所有四种螺旋桨速度的闭环控制，通过直接控制车身扭矩来实现跟踪。其次，控制器利用增量非线性动态反演（INDI）方法，即使外部干扰也能精确跟踪线性和角加速度。因此，不需要先前的空气动力学效应建模。我们通过响应分析对所提出的控制器进行了严格的分析，并在实验中进行了演示。拟议的控制法使1千克四轴飞行器无人机能够跟踪复杂的3D轨迹，速度高达8.2米/秒，加速度高达2克，同时在飞行体积中保持均方根跟踪误差低至4厘米大约6.5米长，6.5米宽，1.5米高。我们还通过在飞行测试中将无挡板连接到无人机并在悬停期间用绳索拉动无人机来证明控制器的坚固性。

##### URL
[http://arxiv.org/abs/1809.04048](http://arxiv.org/abs/1809.04048)

##### PDF
[http://arxiv.org/pdf/1809.04048](http://arxiv.org/pdf/1809.04048)

