---
layout: post
title: "Learning-based Feedback Controller for Deformable Object Manipulation"
date: 2018-06-25 15:02:26
categories: arXiv_RO
tags: arXiv_RO
author: Biao Jia, Zhe Hu, Zherong Pan, Dinesh Manocha, Jia Pan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a general learning-based framework to automatically visual-servo control the position and shape of a deformable object with unknown deformation parameters. The servo-control is accomplished by learning a feedback controller that determines the robotic end-effector's movement according to the deformable object's current status. This status encodes the object's deformation behavior by using a set of observed visual features, which are either manually designed or automatically extracted from the robot's sensor stream. A feedback control policy is then optimized to push the object toward a desired featured status efficiently. The feedback policy can either be learned online or offline. Our online policy learning is based on the Gaussian Process Regression (GPR), which can achieve fast and accurate manipulation and is robust to small perturbation. An offline imitation learning framework is also proposed to achieve a control policy that is robust to large perturbation in the human-robot interaction. We validate the performance of our controller on a set of deformable object manipulation tasks and demonstrate that our method can achieve effective and accurate servo-control for general deformable objects with a wide variety of goal settings.

##### Abstract (translated by Google)
在本文中，我们提出了一个通用的基于学习的框架来自动视觉伺服控制具有未知变形参数的可变形物体的位置和形状。伺服控制是通过学习反馈控制器来完成的，该反馈控制器根据可变形物体的当前状态来确定机器人末端执行器的运动。该状态通过使用一组观察到的视觉特征来编码对象的变形行为，这些特征可以手动设计或从机器人的传感器流中自动提取。然后优化反馈控制策略，以有效地将对象推向期望的特色状态。反馈政策可以在线或离线学习。我们的在线政策学习基于高斯过程回归（GPR），可以实现快速，准确的操作，并且对小扰动具有鲁棒性。还提出了离线仿制学习框架来实现对人机交互中的大扰动稳健的控制策略。我们验证了我们的控制器在一组可变形的对象操纵任务上的性能，并证明我们的方法可以针对具有各种目标设置的一般可变形对象实现有效且精确的伺服控制。

##### URL
[http://arxiv.org/abs/1806.09618](http://arxiv.org/abs/1806.09618)

##### PDF
[http://arxiv.org/pdf/1806.09618](http://arxiv.org/pdf/1806.09618)

