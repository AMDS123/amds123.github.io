---
layout: post
title: "Center-of-Mass-Based Grasp Pose Adaptation Using 3D Range and Force/Torque Sensing"
date: 2018-02-18 15:34:32
categories: arXiv_RO
tags: arXiv_RO
author: Dimitrios Kanoulas, Jinoh Lee, Darwin G. Caldwell, Nikos G. Tsagarakis
mathjax: true
---

* content
{:toc}

##### Abstract
Lifting objects, whose mass may produce high wrist torques that exceed the hardware strength limits, could lead to unstable grasps or serious robot damage. This work introduces a new Center-of-Mass (CoM)-based grasp pose adaptation method, for picking up objects using a combination of exteroceptive 3D perception and proprioceptive force/torque sensor feedback. The method works in two iterative stages to provide reliable and wrist torque efficient grasps. Initially, a geometric object CoM is estimated from the input range data. In the first stage, a set of hand-size handle grasps are localized on the object and the closest to its CoM is selected for grasping. In the second stage, the object is lifted using a single arm, while the force and torque readings from the sensor on the wrist are monitored. Based on these readings, a displacement to the new CoM estimation is calculated. The object is released and the process is repeated until the wrist torque effort is minimized. The advantage of our method is the blending of both exteroceptive (3D range) and proprioceptive (force/torque) sensing for finding the grasp location that minimizes the wrist effort, potentially improving the reliability of the grasping and the subsequent manipulation task. We experimentally validate the proposed method by executing a number of tests on a set of objects that include handles, using the humanoid robot WALK-MAN.

##### Abstract (translated by Google)
起重物体的质量可能会产生超过硬件强度限制的高手腕扭矩，可能会导致抓握不稳或严重的机器人损坏。这项工作引入了一种新的基于质量中心（CoM）的抓握姿势适应方法，用于使用外部感知3D感知和本体感应力/扭矩传感器反馈的组合来拾取物体。该方法在两个迭代阶段工作，以提供可靠和手腕扭矩高效抓握。最初，根据输入范围数据估计几何对象CoM。在第一阶段，一组手部大小的把手被定位在对象上，并且选择最接近其CoM的用于抓握。在第二阶段，使用单臂抬起物体，同时监测来自手腕上的传感器的力和扭矩读数。基于这些读数，计算到新的CoM估计的位移。物体被释放并且重复该过程直到手腕扭矩努力最小化。我们的方法的优势在于将exteroceptive（3D范围）和本体感受（力/力矩）感应混合在一起，以找到最小化手腕操作的抓握位置，从而可能提高抓握的可靠性和随后的操作任务。我们通过使用人形机器人WALK-MAN在包括手柄的一组对象上执行大量测试来验证所提出的方法。

##### URL
[http://arxiv.org/abs/1802.06392](http://arxiv.org/abs/1802.06392)

##### PDF
[http://arxiv.org/pdf/1802.06392](http://arxiv.org/pdf/1802.06392)

