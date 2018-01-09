---
layout: post
title: "Push recovery with stepping strategy based on time-projection control"
date: 2018-01-07 07:15:47
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Salman Faraji, Hamed Razavi, Auke J. Ijspeert
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a simple control framework for on-line push recovery with dynamic stepping properties. Due to relatively heavy legs in our robot, we need to take swing dynamics into account and thus use a linear model called 3LP which is composed of three pendulums to simulate swing and torso dynamics. Based on 3LP equations, we formulate discrete LQR controllers and use a particular time-projection method to adjust the next footstep location on-line during the motion continuously. This adjustment, which is found based on both pelvis and swing foot tracking errors, naturally takes the swing dynamics into account. Suggested adjustments are added to the Cartesian 3LP gaits and converted to joint-space trajectories through inverse kinematics. Fixed and adaptive foot lift strategies also ensure enough ground clearance in perturbed walking conditions. The proposed structure is robust, yet uses very simple state estimation and basic position tracking. We rely on the physical series elastic actuators to absorb impacts while introducing simple laws to compensate their tracking bias. Extensive experiments demonstrate the functionality of different control blocks and prove the effectiveness of time-projection in extreme push recovery scenarios. We also show self-produced and emergent walking gaits when the robot is subject to continuous dragging forces. These gaits feature dynamic walking robustness due to relatively soft springs in the ankles and avoiding any Zero Moment Point (ZMP) control in our proposed architecture.

##### Abstract (translated by Google)
在本文中，我们提出了一个简单的控制框架，用于动态步进属性的在线推送恢复。由于我们的机器人腿较重，我们需要考虑摆动动力学，从而使用一个称为3LP的线性模型，它由三个摆组成，以模拟摆动和躯干动力学。基于3LP方程，我们制定了离散LQR控制器，并使用一个特定的时间投影方法来连续调整运动过程中的下一个脚步位置。基于骨盆和摆动脚跟踪误差找到的这种调整自然考虑到摆动动态。建议的调整将添加到笛卡尔3LP步态，并通过反向运动转换为联合空间轨迹。固定的和适应性的脚踏升降策略也确保在扰动的步行条件下足够的离地间隙。提出的结构是健壮的，但使用非常简单的状态估计和基本的位置跟踪。我们依靠物理系列弹性执行器来吸收冲击，同时引入简单的法则来补偿它们的跟踪偏差。大量的实验证明了不同控制块的功能，并证明了在极端推回恢复情况下时间投影的有效性。当机器人受到持续拖曳的力量时，我们也展示自制和紧急的步态步态。由于脚踝中的弹簧相对较软，并且避免了我们提出的架构中的零点矩（ZMP）控制，所以这些步态具有动态行走鲁棒性。

##### URL
[http://arxiv.org/abs/1801.02151](http://arxiv.org/abs/1801.02151)

##### PDF
[http://arxiv.org/pdf/1801.02151](http://arxiv.org/pdf/1801.02151)

