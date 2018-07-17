---
layout: post
title: "A Control Architecture with Online Predictive Planning for Position and Torque Controlled Walking of Humanoid Robots"
date: 2018-07-14 13:20:18
categories: arXiv_RO
tags: arXiv_RO
author: Stefano Dafarra, Gabriele Nava, Marie Charbonneau, Nuno Guedelha, Francisco Andrade, Silvio Traversaro, Luca Fiorio, Francesco Romano, Francesco Nori, Giorgio Metta, Daniele Pucci
mathjax: true
---

* content
{:toc}

##### Abstract
A common approach to the generation of walking patterns for humanoid robots consists in adopting a layered control architecture. This paper proposes an architecture composed of three nested control loops. The outer loop exploits a robot kinematic model to plan the footstep positions. In the mid layer, a predictive controller generates a Center of Mass trajectory according to the well-known table-cart model. Through a whole-body inverse kinematics algorithm, we can define joint references for position controlled walking. The outcomes of these two loops are then interpreted as inputs of a stack-of-task QP-based torque controller, which represents the inner loop of the presented control architecture. This resulting architecture allows the robot to walk also in torque control, guaranteeing higher level of compliance. Real world experiments have been carried on the humanoid robot iCub.

##### Abstract (translated by Google)
为人形机器人生成步行模式的常见方法在于采用分层控制架构。本文提出了一个由三个嵌套控制循环组成的体系结构。外环利用机器人运动模型来规划足迹位置。在中间层，预测控制器根据众所周知的table-cart模型生成质心轨迹。通过全身逆运动学算法，我们可以定义位置控制步行的联合参考。然后将这两个循环的结果解释为基于任务QP的扭矩控制器的输入，其表示所呈现的控制架构的内环。由此产生的结构允许机器人在转矩控制中行走，从而保证更高的顺应性。在人形机器人iCub上进行了真实世界的实验。

##### URL
[http://arxiv.org/abs/1807.05395](http://arxiv.org/abs/1807.05395)

##### PDF
[http://arxiv.org/pdf/1807.05395](http://arxiv.org/pdf/1807.05395)

