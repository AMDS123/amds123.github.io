---
layout: post
title: "Bipedal Hopping: Reduced-order Model Embedding via Optimization-based Control"
date: 2018-07-20 21:29:27
categories: arXiv_RO
tags: arXiv_RO Embedding Optimization
author: Xiaobin Xiong, Aaron Ames
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the design and validation of controlling hopping on the 3D bipedal robot Cassie. A spring-mass model is identified from the kinematics and compliance of the robot. The spring stiffness and damping are encapsulated by the leg length, thus actuating the leg length can create and control hopping behaviors. Trajectory optimization via direct collocation is performed on the spring-mass model to plan jumping and landing motions. The leg length trajectories are utilized as desired outputs to synthesize a control Lyapunov function based quadratic program (CLF-QP). Centroidal angular momentum, taking as an addition output in the CLF-QP, is also stabilized in the jumping phase to prevent whole body rotation in the underactuated flight phase. The solution to the CLF-QP is a nonlinear feedback control law that achieves dynamic jumping behaviors on bipedal robots with compliance. The framework presented in this paper is verified experimentally on the bipedal robot Cassie.

##### Abstract (translated by Google)
本文介绍了控制3D双足机器人Cassie跳跃的设计和验证。根据机器人的运动学和顺应性确定弹簧质量模型。弹簧刚度和阻尼由腿长度封装，因此致动腿长度可以产生和控制跳跃行为。通过直接配置进行轨迹优化是在弹簧质量模型上进行的，以计划跳跃和着陆运动。腿长轨迹被用作期望的输出以合成基于控制Lyapunov函数的二次程序（CLF-QP）。作为CLF-QP中的附加输出的中心角动量在跳跃阶段也是稳定的，以防止在欠驱动飞行阶段的全身旋转。 CLF-QP的解决方案是一种非线性反馈控制律，可以实现具有顺应性的双足机器人的动态跳跃行为。本文提出的框架通过实验验证了双足机器人Cassie。

##### URL
[http://arxiv.org/abs/1807.08037](http://arxiv.org/abs/1807.08037)

##### PDF
[http://arxiv.org/pdf/1807.08037](http://arxiv.org/pdf/1807.08037)

