---
layout: post
title: "Hybrid Multi-camera Visual Servoing to Moving Target"
date: 2018-03-06 16:25:15
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Hanz Cuevas-Velasquez, Nanbo Li, Radim Tylecek, Marcelo Saval-Calvo, Robert B. Fisher
mathjax: true
---

* content
{:toc}

##### Abstract
Visual servoing is a well-known task in robotics. However, there are still challenges when multiple sources are combined to accurately guide the robot or occlusions appear. In this paper we present a novel visual servoing approach using hybrid multi-camera input data to lead a robot arm accurately to dynamically moving target points in the presence of partial occlusions. The approach uses four RGBD sensors as Eye-to-Hand (EtoH) visual input, and an arm-mounted stereo camera as Eye-in-Hand (EinH). A Master supervisor task selects between using the EtoH or the EinH, depending on the distance between the robot and target. The Master also selects the subset of EtoH cameras that best perceive the target. When the EinH sensor is used, if the target becomes occluded or goes out of the sensor's view-frustrum, the Master switches back to the EtoH sensors to re-track the object. Using this adaptive visual input data, the robot is then controlled using an iterative planner that uses position, orientation and joint configuration to estimate the trajectory. Since the target is dynamic, this trajectory is updated every time-step. Experiments show good performance in three different situations: tracking a ball, targeting a bulls-eye, and guiding a straw to a mouth. The experiments cover both simple situations such as the ball that is completely visible from all cameras, and more complex situations such as the mouth which is partially occluded from some of the sensors.

##### Abstract (translated by Google)
视觉伺服是机器人领域众所周知的任务。但是，将多个信号源组合起来准确指导机器人或遮挡物出现时，仍然存在挑战。在本文中，我们提出了一种新颖的视觉伺服方法，使用混合多相机输入数据来准确地引导机器人手臂在存在部分遮挡的情况下动态移动目标点。该方法使用四个RGBD传感器作为眼睛到手（EtoH）视觉输入，以及手臂安装的立体相机作为Eye-in-Hand（EinH）。主监督员任务根据机器人和目标之间的距离来选择使用EtoH还是EinH。大师还会选择最能感知目标的EtoH摄像机的子集。当使用EinH传感器时，如果目标被遮挡或不在传感器的视野内，主控器会切换回EtoH传感器以重新跟踪物体。使用这种自适应视觉输入数据，然后使用迭代规划器来控制机器人，该迭代规划器使用位置，方向和关节配置来估计轨迹。由于目标是动态的，因此该轨迹在每个时间步更新。实验在三种不同的情况下表现出良好的表现：跟踪球，瞄准靶心，并将吸管引导至嘴巴。这些实验包括简单的情况，例如所有相机完全可见的球，以及更复杂的情况，例如部分传感器部分遮挡的嘴巴。

##### URL
[http://arxiv.org/abs/1803.02285](http://arxiv.org/abs/1803.02285)

##### PDF
[http://arxiv.org/pdf/1803.02285](http://arxiv.org/pdf/1803.02285)

