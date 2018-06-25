---
layout: post
title: "Real-time gait planner for human walking using a lower limb exoskeleton and its implementation on Exoped robot"
date: 2018-06-22 09:42:14
categories: arXiv_RO
tags: arXiv_RO
author: Jafar Kazemi, Sadjaad Ozgoli
mathjax: true
---

* content
{:toc}

##### Abstract
Lower extremity exoskeleton has been developed as a motion assistive technology in recent years. Walking pattern generation is a fundamental topic in the design of these robots. The usual approach with most exoskeletons is to use a pre-recorded pattern as a look-up table. There are some deficiencies with this method, including data storage limitation and poor regulation relating to the walking parameters. Therefore modeling human walking patterns to use in exoskeletons is required. The few existing models provide piece by piece walking patterns, only generating at the beginning of each stride cycle in respect to fixed walking parameters. In this paper, we present a real-time walking pattern generation method which enables changing the walking parameters during the stride. For this purpose, two feedback controlled third order systems are proposed as optimal trajectory planners for generating the trajectory of the x and y components of each joints position. The boundary conditions of the trajectories are obtained according to some pre-considered walking constraints. In addition, a cost function is intended for each trajectory planner in order to increase the trajectories smoothness. We use the minimum principle of Pontryagin to design the feedback controller in order to track the boundary conditions in such a way that the cost functions are minimized. Finally, by using inverse kinematics equations, the proper joints angles are generated for and implemented on Exoped robot. The good performance of the gait planner is demonstrated by second derivative continuity of the trajectories being maintained as a result of a simulation, and user satisfaction being determined by experimental testing.

##### Abstract (translated by Google)
近年来，下肢外骨骼已经发展成为运动辅助技术。步行图案生成是这些机器人设计中的一个基本话题。大多数外骨骼的通常做法是使用预先记录的图案作为查找表。这种方法存在一些缺陷，包括数据存储限制和与步行参数有关的不规范。因此需要建模人类步行模式以用于外骨骼。少数现有模型提供逐件步行模式，仅在每个步幅周期的开始时就固定步行参数产生。在本文中，我们提出了一种实时步行模式生成方法，可以在步伐中改变步行参数。为此，提出两个反馈控制的三阶系统作为用于生成每个关节位置的x和y分量的轨迹的最优轨迹规划器。轨迹的边界条件是根据一些预先考虑的步行约束来获得的。另外，为了增加轨迹平滑度，每个轨迹规划器都有一个成本函数。我们使用Pontryagin的最小原则来设计反馈控制器，以便以最小化成本函数的方式跟踪边界条件。最后，通过使用反向运动学方程，生成适当的关节角度并在Exoped机器人上实现。步态规划器的良好性能通过模拟的结果保持轨迹的二阶导数连续性来证明，并且用户满意度由实验测试确定。

##### URL
[http://arxiv.org/abs/1806.08574](http://arxiv.org/abs/1806.08574)

##### PDF
[http://arxiv.org/pdf/1806.08574](http://arxiv.org/pdf/1806.08574)

