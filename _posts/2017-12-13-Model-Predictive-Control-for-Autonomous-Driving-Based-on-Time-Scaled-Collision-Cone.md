---
layout: post
title: "Model Predictive Control for Autonomous Driving Based on Time Scaled Collision Cone"
date: 2017-12-13 19:15:41
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Mithun Babu, Yash Oza, Arun Kumar Singh, K. Madhava Krishna, Shanti Medasani
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a Model Predictive Control (MPC) framework based on path velocity decomposition paradigm for autonomous driving. The optimization underlying the MPC has a two layer structure wherein first, an appropriate path is computed for the vehicle followed by the computation of optimal forward velocity along it. The very nature of the proposed path velocity decomposition allows for seamless compatibility between the two layers of the optimization. A key feature of the proposed work is that it offloads most of the responsibility of collision avoidance to velocity optimization layer for which computationally efficient formulations can be derived. In particular, we extend our previously developed concept of time scaled collision cone (TSCC) constraints and formulate the forward velocity optimization layer as a convex quadratic programming problem. We perform validation on autonomous driving scenarios wherein proposed MPC repeatedly solves both the optimization layers in receding horizon manner to compute lane change, overtaking and merging maneuvers among multiple dynamic obstacles.

##### Abstract (translated by Google)
在本文中，我们提出了一个基于路径速度分解范式的自主驾驶模型预测控制（MPC）框架。基于MPC的优化具有双层结构，其中首先，为车辆计算适当的路径，然后计算沿其的最佳前进速度。所提出的路径速度分解的本质允许两层优化之间的无缝兼容性。所提出的工作的一个关键特点是将避免碰撞的大部分责任转移到速度优化层上，从而可以导出计算有效的公式。特别地，我们扩展了我们以前开发的时间尺度碰撞锥（TSCC）约束的概念，并将前向速度优化层作为凸二次规划问题。我们对自主驾驶场景进行验证，其中提出的MPC重复地以后退视界方式解决优化层以计算车道变化，超车和合并多个动态障碍物之间的机动。

##### URL
[https://arxiv.org/abs/1712.04965](https://arxiv.org/abs/1712.04965)

##### PDF
[https://arxiv.org/pdf/1712.04965](https://arxiv.org/pdf/1712.04965)

