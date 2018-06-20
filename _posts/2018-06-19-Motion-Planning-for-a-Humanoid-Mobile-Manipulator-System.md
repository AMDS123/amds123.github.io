---
layout: post
title: "Motion Planning for a Humanoid Mobile Manipulator System"
date: 2018-06-19 17:02:30
categories: arXiv_RO
tags: arXiv_RO Optimization Gradient_Descent
author: Yan Wei, Wei Jiang, Ahmed Rahmani, Qiang Zhan
mathjax: true
---

* content
{:toc}

##### Abstract
A high redundant non-holonomic humanoid mobile dual-arm manipulator system is presented in this paper where the motion planning to realize "human-like" autonomous navigation and manipulation tasks is studied. Firstly, an improved MaxiMin NSGA-II algorithm, which optimizes five objective functions to solve the problems of singularity, redundancy, and coupling between mobile base and manipulator simultaneously, is proposed to design the optimal pose to manipulate the target object. Then, in order to link the initial pose and that optimal pose, an off-line motion planning algorithm is designed. In detail, an efficient direct-connect bidirectional RRT and gradient descent algorithm is proposed to reduce the sampled nodes largely, and a geometric optimization method is proposed for path pruning. Besides, head forward behaviors are realized by calculating the reasonable orientations and assigning them to the mobile base to improve the quality of human-robot interaction. Thirdly, the extension to on-line planning is done by introducing real-time sensing, collision-test and control cycles to update robotic motion in dynamic environments. Fourthly, an EEs' via-point-based multi-objective genetic algorithm is proposed to design the "human-like" via-poses by optimizing four objective functions. Finally, numerous simulations are presented to validate the effectiveness of proposed algorithms.

##### Abstract (translated by Google)
本文提出了一种高冗余非完整人形移动双臂机械手系统，研究了实现“类人”自主导航与操纵任务的运动规划。首先，提出了一种改进的MaxiMin NSGA-II算法，该算法优化了五个目标函数，同时解决了移动基与机械手之间的奇异性，冗余性和耦合性问题，设计了最优姿态来操纵目标对象。然后，为了链接初始姿态和最佳姿态，设计了离线运动规划算法。详细地说，提出了一种高效的直接连接双向RRT和梯度下降算法来大量减少采样节点，并提出了一种几何优化方法用于路径修剪。此外，通过计算合理的方位并将它们分配给移动基站来实现前向行为，从而提高人机交互的质量。第三，通过引入实时感测，碰撞测试和控制周期来更新在线计划，以更新动态环境中的机器人运动。第四，提出了基于EEs的基于经验点的多目标遗传算法，通过优化四个目标函数来设计“类人”过孔。最后，提出了许多仿真来验证所提出的算法的有效性。

##### URL
[http://arxiv.org/abs/1806.07349](http://arxiv.org/abs/1806.07349)

##### PDF
[http://arxiv.org/pdf/1806.07349](http://arxiv.org/pdf/1806.07349)

