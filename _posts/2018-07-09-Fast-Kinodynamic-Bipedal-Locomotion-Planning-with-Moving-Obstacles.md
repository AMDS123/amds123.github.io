---
layout: post
title: "Fast Kinodynamic Bipedal Locomotion Planning with Moving Obstacles"
date: 2018-07-09 22:51:10
categories: arXiv_RO
tags: arXiv_RO
author: Junhyeok Ahn, Orion Campbell, Donghyun Kim, Luis Sentis
mathjax: true
---

* content
{:toc}

##### Abstract
We present a sampling-based kinodynamic planning framework for a bipedal robot in complex environments. Unlike other footstep planner which typically plan footstep locations and the biped dynamics in separate steps, we handle both simultaneously. Three advantages of this approach are (1) the ability to differentiate alternate routes while selecting footstep locations based on the temporal duration of the route as determined by the Linear Inverted Pendulum Model dynamics, (2) the ability to perform collision checking through time so that collisions with moving obstacles are prevented without avoiding their entire trajectory, and (3) the ability to specify a minimum forward velocity for the biped. To generate a dynamically consistent description of the walking behavior, we exploit the Phase Space Planner. To plan a collision free route toward the goal, we adapt planning strategies from non-holonomic wheeled robots to gather a sequence of inputs for the PSP. This allows us to efficiently approximate dynamic and kinematic constraints on bipedal motion, to apply a sampling based planning algorithms, and to use the Dubin's path as the steering method to connect two points in the configuration space. The results of the algorithm are sent to a Whole Body Controller to generate full body dynamic walking behavior.

##### Abstract (translated by Google)
我们为复杂环境中的双足机器人提供基于采样的动力学规划框架。与其他通常在单独步骤中计划足迹位置和两足动力学的脚步计划器不同，我们同时处理两者。这种方法的三个优点是：（1）能够根据线性倒立摆模型动力学确定的路线的时间持续时间选择足迹位置来区分替代路线，（2）通过时间执行碰撞检查的能力，以便在不避开其整个轨迹的情况下防止了与移动障碍物的碰撞，以及（3）为两足动物指定最小前进速度的能力。为了生成行走行为的动态一致描述，我们利用相空间规划器。为了规划朝向目标的无碰撞路线，我们调整来自非完整轮式机器人的规划策略，以收集PSP的一系列输入。这使我们能够有效地近似对双足运动的动态和运动学约束，应用基于采样的计划算法，并使用Dubin的路径作为连接配置空间中两个点的转向方法。算法的结果被发送到全身控制器以生成全身动态行走行为。

##### URL
[http://arxiv.org/abs/1807.03415](http://arxiv.org/abs/1807.03415)

##### PDF
[http://arxiv.org/pdf/1807.03415](http://arxiv.org/pdf/1807.03415)

