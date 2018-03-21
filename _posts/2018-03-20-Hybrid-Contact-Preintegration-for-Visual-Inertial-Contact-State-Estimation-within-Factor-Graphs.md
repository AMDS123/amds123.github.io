---
layout: post
title: "Hybrid Contact Preintegration for Visual-Inertial-Contact State Estimation within Factor Graphs"
date: 2018-03-20 17:16:12
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Ross Hartley, Maani Ghaffari Jadidi, Lu Gan, Jiunn-Kai Huang, Jessy W. Grizzle, Ryan M. Eustice
mathjax: true
---

* content
{:toc}

##### Abstract
The factor graph framework is a convenient modeling technique for robotic state estimation and sensor fusion where states are represented as nodes and measurements are modeled as factors. In designing a sensor fusion framework using factor graphs for legged robots, one often has access to visual, inertial, encoders, and contact sensors. While visual-inertial odometry has been studied extensively in this framework, the addition of a preintegrated contact factor for legged robots has been proposed recently. In this work, to cope with the problem of switching contact frames which was not addressed previously, we propose a hybrid contact preintegration that does not require the addition of frequently broken contact factors into the estimation factor graph. This paper presents a novel method for preintegrating contact information though an arbitrary number of contact switches. The proposed hybrid modeling approach reduces the number of required variables in the nonlinear optimization problem by only requiring new states to be added alongside camera or selected keyframes. This method is evaluated using real experimental data collected from a Cassie-series robot where the trajectory of the robot produced by a motion capture system is used as a proxy for ground truth data. The evaluation shows that inclusion of the proposed preintegrated hybrid contact factor alongside visual-inertial navigation systems improves robustness to vision failure as well as the estimation accuracy for legged robots while its generalization makes it more accessible for legged platforms.

##### Abstract (translated by Google)
因子图框架是用于机器人状态估计和传感器融合的便利建模技术，其中状态被表示为节点并且测量被建模为因子。在使用有腿机器人的因子图设计传感器融合框架时，人们通常可以使用视觉，惯性，编码器和接触式传感器。尽管在这个框架中已经广泛研究了视觉惯性测距法，但最近已经提出了对腿式机器人添加预先整合的接触因子。在这项工作中，为了解决以前未涉及的切换接触框架的问题，我们提出了一种混合接触预集成，它不需要在估算因子图中添加经常断开的接触因子。本文提出了一种通过任意数量的接触开关预整合联系人信息的新方法。所提出的混合建模方法通过仅需要将新状态添加在相机或所选关键帧旁边来减少非线性优化问题中所需变量的数量。该方法使用从Cassie系列机器人收集的实际实验数据进行评估，其中由运动捕捉系统产生的机器人的轨迹被用作地面实况数据的代理。评估结果表明，将所提出的预集成混合接触因子与视觉 - 惯性导航系统结合在一起，可以提高视力失效的鲁棒性以及腿式机器人的估计精度，而其泛化使得腿式平台更易于使用。

##### URL
[http://arxiv.org/abs/1803.07531](http://arxiv.org/abs/1803.07531)

##### PDF
[http://arxiv.org/pdf/1803.07531](http://arxiv.org/pdf/1803.07531)

