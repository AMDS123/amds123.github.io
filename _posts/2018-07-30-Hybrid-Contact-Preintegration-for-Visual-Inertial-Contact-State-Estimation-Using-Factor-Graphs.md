---
layout: post
title: "Hybrid Contact Preintegration for Visual-Inertial-Contact State Estimation Using Factor Graphs"
date: 2018-07-30 05:07:52
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Ross Hartley, Maani Ghaffari Jadidi, Lu Gan, Jiunn-Kai Huang, Jessy W. Grizzle, Ryan M. Eustice
mathjax: true
---

* content
{:toc}

##### Abstract
The factor graph framework is a convenient modeling technique for robotic state estimation where states are represented as nodes, and measurements are modeled as factors. When designing a sensor fusion framework for legged robots, one often has access to visual, inertial, joint encoder, and contact sensors. While visual-inertial odometry has been studied extensively in this framework, the addition of a preintegrated contact factor for legged robots has been only recently proposed. This allowed for integration of encoder and contact measurements into existing factor graphs, however, new nodes had to be added to the graph every time contact was made or broken. In this work, to cope with the problem of switching contact frames, we propose a hybrid contact preintegration theory that allows contact information to be integrated through an arbitrary number of contact switches. The proposed hybrid modeling approach reduces the number of required variables in the nonlinear optimization problem by only requiring new states to be added alongside camera or selected keyframes. This method is evaluated using real experimental data collected from a Cassie-series robot where the trajectory of the robot produced by a motion capture system is used as a proxy for ground truth. The evaluation shows that inclusion of the proposed preintegrated hybrid contact factor alongside visual-inertial navigation systems improves estimation accuracy as well as robustness to vision failure, while its generalization makes it more accessible for legged platforms.

##### Abstract (translated by Google)
因子图框架是用于机器人状态估计的便利建模技术，其中状态表示为节点，并且测量被建模为因子。在为腿式机器人设计传感器融合框架时，人们通常可以使用视觉，惯性，关节编码器和接触传感器。虽然在该框架中已经广泛研究了视觉惯性测距法，但是最近才提出为腿式机器人添加预先整合的接触因子。这允许将编码器和接触测量集成到现有因子图中，然而，每次接触或断开时都必须将新节点添加到图中。在这项工作中，为了解决切换接触框架的问题，我们提出了一种混合接触预整合理论，该理论允许通过任意数量的接触开关集成接触信息。所提出的混合建模方法通过仅需要在相机或所选关键帧旁边添加新状态来减少非线性优化问题中所需变量的数量。使用从Cassie系列机器人收集的真实实验数据来评估该方法，其中由运动捕捉系统产生的机器人的轨迹被用作地面实况的代理。评估表明，将所提出的预集成混合接触因子与视觉惯性导航系统相结合，可以提高估计精度以及对视觉失效的鲁棒性，而其概括使其更易于进入有腿平台。

##### URL
[http://arxiv.org/abs/1803.07531](http://arxiv.org/abs/1803.07531)

##### PDF
[http://arxiv.org/pdf/1803.07531](http://arxiv.org/pdf/1803.07531)

