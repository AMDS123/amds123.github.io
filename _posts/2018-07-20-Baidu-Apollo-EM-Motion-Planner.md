---
layout: post
title: "Baidu Apollo EM Motion Planner"
date: 2018-07-20 22:34:17
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Haoyang Fan, Fan Zhu, Changchun Liu, Liangliang Zhang, Li Zhuang, Dong Li, Weicheng Zhu, Jiangtao Hu, Hongye Li, Qi Kong
mathjax: true
---

* content
{:toc}

##### Abstract
In this manuscript, we introduce a real-time motion planning system based on the Baidu Apollo (open source) autonomous driving platform. The developed system aims to address the industrial level-4 motion planning problem while considering safety, comfort and scalability. The system covers multilane and single-lane autonomous driving in a hierarchical manner: (1) The top layer of the system is a multilane strategy that handles lane-change scenarios by comparing lane-level trajectories computed in parallel. (2) Inside the lane-level trajectory generator, it iteratively solves path and speed optimization based on a Frenet frame. (3) For path and speed optimization, a combination of dynamic programming and spline-based quadratic programming is proposed to construct a scalable and easy-to-tune framework to handle traffic rules, obstacle decisions and smoothness simultaneously. The planner is scalable to both highway and lower-speed city driving scenarios. We also demonstrate the algorithm through scenario illustrations and on-road test results. 
 The system described in this manuscript has been deployed to dozens of Baidu Apollo autonomous driving vehicles since Apollo v1.5 was announced in September 2017. As of May 16th, 2018, the system has been tested under 3,380 hours and approximately 68,000 kilometers (42,253 miles) of closed-loop autonomous driving under various urban scenarios. 
 The algorithm described in this manuscript is available at https://github.com/ApolloAuto/apollo/tree/master/modules/planning.

##### Abstract (translated by Google)
在本手稿中，我们介绍了一个基于百度Apollo（开源）自动驾驶平台的实时运动规划系统。开发的系统旨在解决工业级别4运动规划问题，同时考虑安全性，舒适性和可扩展性。该系统以分层方式涵盖多车道和单车道自动驾驶：（1）系统的顶层是多车道战略，通过比较并行计算的车道水平轨迹来处理车道变换情景。 （2）在车道级轨迹生成器内部，迭代地求解基于Frenet帧的路径和速度优化。 （3）对于路径和速度优化，提出了动态规划和基于样条的二次规划的组合，以构建可扩展且易于调整的框架，以同时处理交通规则，障碍决策和平滑性。该规划器可扩展到高速公路和低速城市驾驶场景。我们还通过场景插图和路上测试结果演示了算法。
 自2017年9月宣布Apollo v1.5以来，本手稿中描述的系统已部署到数十台百度Apollo自动驾驶车辆中。截至2018年5月16日，该系统已经在3,380小时和大约68,000公里（42,253英里）下进行了测试。在各种城市情景下的闭环自动驾驶。
 本手稿中描述的算法可在https://github.com/ApolloAuto/apollo/tree/master/modules/planning获得。

##### URL
[http://arxiv.org/abs/1807.08048](http://arxiv.org/abs/1807.08048)

##### PDF
[http://arxiv.org/pdf/1807.08048](http://arxiv.org/pdf/1807.08048)

