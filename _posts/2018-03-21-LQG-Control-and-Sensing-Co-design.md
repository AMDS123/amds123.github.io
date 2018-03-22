---
layout: post
title: "LQG Control and Sensing Co-design"
date: 2018-03-21 14:13:52
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Vasileios Tzoumas, Luca Carlone, George J. Pappas, Ali Jadbabaie
mathjax: true
---

* content
{:toc}

##### Abstract
Linear-Quadratic-Gaussian (LQG) control is concerned with the design of an optimal controller and estimator for linear Gaussian systems with imperfect state information. Standard LQG control assumes the set of sensor measurements to be fed to the estimator to be given. However, in many problems in networked systems and robotics, one is interested in designing a suitable set of sensors for LQG control. In this paper, we introduce the LQG control and sensing co-design problem, where one has to jointly design a suitable sensing, estimation, and control policy. We consider two dual instances of the co-design problem: the sensing-constrained LQG control problem, where the design maximizes the control performance subject to sensing constraints, and the minimum-sensing LQG control, where the design minimizes the amount of sensing subject to performance constraints. We focus on the case in which the sensing design has to be selected among a finite set of possible sensing modalities, where each modality is associated with a different cost. While we observe that the computation of the optimal sensing design is intractable in general, we present the first scalable LQG co-design algorithms to compute near-optimal policies with provable sub-optimality guarantees. To this end, (i) we show that a separation principle holds, which partially decouples the design of sensing, estimation, and control; (ii) we frame LQG co-design as the optimization of (approximately) supermodular set functions; (iii) we develop novel algorithms to solve the resulting optimization problems; (iv) we prove original results on the performance of these algorithms and establish connections between their sub-optimality gap and control-theoretic quantities. We conclude the paper by discussing two practical applications of the co-design problem, namely, sensing-constrained formation control and resource-constrained robot navigation.

##### Abstract (translated by Google)
线性二次高斯（LQG）控制涉及具有不完美状态信息的线性高斯系统的最优控制器和估计器的设计。标准的LQG控制假定传感器测量值集合被馈送给估计器。然而，在网络系统和机器人的许多问题中，人们有兴趣为LQG控制设计一套合适的传感器。在本文中，我们介绍LQG控制和传感协同设计问题，其中必须共同设计合适的传感，估算和控制策略。我们考虑协同设计问题的两个双重实例：感应约束LQG控制问题，其中设计最大化受控于传感约束的控制性能，以及最小感测LQG控制，其中设计最小化感测量性能限制。我们专注于感应设计必须从有限的可能感测模式集中选择的情况，其中每种模式与不同的成本相关联。虽然我们观察到最优感测设计的计算通常是棘手的，但我们提出了第一个可扩展的LQG协同设计算法，以便用可证明的次优性保证来计算接近最优策略。为此，（i）我们证明分离原理成立，这部分地解耦了传感，估计和控制的设计; （ii）我们将LQG协同设计定义为（近似）超模数集合函数的优化; （iii）我们开发新的算法来解决最终的优化问题; （iv）我们证明了这些算法的性能的原始结果，并建立了它们的次优间隙与控制理论量之间的联系。我们通过讨论协同设计问题的两个实际应用，即感测约束地层控制和资源受限机器人导航来总结本文。

##### URL
[http://arxiv.org/abs/1802.08376](http://arxiv.org/abs/1802.08376)

##### PDF
[http://arxiv.org/pdf/1802.08376](http://arxiv.org/pdf/1802.08376)

