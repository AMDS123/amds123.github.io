---
layout: post
title: "Relaxed-Rigidity Constraints: Kinematic Trajectory Optimization and Collision Avoidance for In-Grasp Manipulation"
date: 2018-06-04 03:45:33
categories: arXiv_RO
tags: arXiv_RO Knowledge Optimization
author: Balakumar Sundaralingam, Tucker Hermans
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel approach to performing in-grasp manipulation: the problem of moving an object with reference to the palm from an initial pose to a goal pose without breaking or making contacts. Our method to perform in-grasp manipulation uses kinematic trajectory optimization which requires no knowledge of dynamic properties of the object. We implement our approach on an Allegro robot hand and perform thorough experiments on 10 objects from the YCB dataset. However, the proposed method is general enough to generate motions for most objects the robot can grasp. Experimental result support the feasibillty of its application across a variety of object shapes. We explore the adaptability of our approach to additional task requirements by including collision avoidance and joint space smoothness costs. The grasped object avoids collisions with the environment by the use of a signed distance cost function. We reduce the effects of unmodeled object dynamics by requiring smooth joint trajectories. We additionally compensate for errors encountered during trajectory execution by formulating an object pose feedback controller.

##### Abstract (translated by Google)
本文提出了一种执行抓握操纵的新颖方法：将参考手掌的物体从初始姿势移动到目标姿势而不破坏或接触的问题。我们的执行抓握操纵的方法使用运动学轨迹优化，其不需要知道物体的动态特性。我们在Allegro机器人手上实施我们的方法，并对来自YCB数据集的10个对象进行彻底的实验。然而，所提出的方法通常足以为机器人可以掌握的大多数物体产生运动。实验结果支持其在各种物体形状上的应用的可行性。我们通过包括碰撞避免和联合空间平滑成本来探索我们的方法对于额外任务要求的适应性。抓住的对象通过使用带符号距离成本函数来避免与环境的碰撞。我们通过要求平滑的关节轨迹来减少未建模物体动态的影响。我们还通过制定物体姿态反馈控制器来补偿在轨迹执行期间遇到的错误。

##### URL
[http://arxiv.org/abs/1806.00942](http://arxiv.org/abs/1806.00942)

##### PDF
[http://arxiv.org/pdf/1806.00942](http://arxiv.org/pdf/1806.00942)

