---
layout: post
title: "Legged Robot State-Estimation Through Combined Forward Kinematic and Preintegrated Contact Factors"
date: 2017-12-15 23:04:31
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Ross Hartley, Josh Mangelson, Lu Gan, Maani Ghaffari Jadidi, Jeffrey M. Walls, Ryan M. Eustice, Jessy W. Grizzle
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art robotic perception systems have achieved sufficiently good performance using Inertial Measurement Units (IMUs), cameras, and nonlinear optimization techniques, that they are now being deployed as technologies. However, many of these methods rely significantly on vision and fail when visual tracking is lost due to lighting or scarcity of features. In addition, such systems are formulated such that the system is independent of the operating platform. This paper presents state-estimation technique for legged robots that takes into account the robot's kinematic model as well as its contact with the environment. This is achieved by introducing forward kinematic factors and preintegrated contact factors into a factor graph framework that can incrementally solved in real-time. The forward kinematics factor relates the robot's base pose to a contact frame through noisy encoder measurements. The preintegrated contact factor provides odometry measurements of this contact frame, while accounting for possible foot slippage. Taken together, the two factors constrain the graph optimization problem allowing the robot's trajectory to be estimated. The paper evaluates the method using simulated and real sensory IMU and kinematic data from experiments with a Cassie-series robot designed by Agility Robotics. These experiments show that using the proposed method in addition to IMU significantly decreases drift and improves localization accuracy, suggesting that its use can enable successful recovery from loss of visual tracking.

##### Abstract (translated by Google)
先进的机器人感知系统使用惯性测量单元（IMU），摄像机和非线性优化技术已经取得了足够好的性能，现在它们正在被部署为技术。然而，这些方法中的许多方法都很大程度上依赖于视觉，并且在由于照明或功能稀缺而导致视觉追踪丢失时失败。另外，这样的系统被制定成使系统独立于操作平台。本文提出了腿式机器人的状态估计技术，考虑到机器人的运动学模型及其与环境的接触。这是通过将正向运动因子和预先集成的接触因子引入可以实时递增求解的因子图框架来实现的。正向运动学因素通过噪声编码器测量将机器人的基本姿态与接触框架相关联。预先整合的接触系数提供了这个接触框架的测距测量结果，同时考虑了可能的滑脚滑移。总之，这两个因素限制了图形优化问题，允许估计机器人的轨迹。本文用Agility Robotics设计的Cassie系列机器人的实验，使用模拟和真实感觉IMU和运动数据评估方法。这些实验表明，除了IMU之外，使用所提出的方法显着地降低了漂移并且提高了定位准确性，表明其使用可以使失败的视觉跟踪成功恢复。

##### URL
[http://arxiv.org/abs/1712.05873](http://arxiv.org/abs/1712.05873)

##### PDF
[http://arxiv.org/pdf/1712.05873](http://arxiv.org/pdf/1712.05873)

