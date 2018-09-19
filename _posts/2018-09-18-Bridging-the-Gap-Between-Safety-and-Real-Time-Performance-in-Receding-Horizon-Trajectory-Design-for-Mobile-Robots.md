---
layout: post
title: "Bridging the Gap Between Safety and Real-Time Performance in Receding-Horizon Trajectory Design for Mobile Robots"
date: 2018-09-18 13:58:31
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Shreyas Kousik, Sean Vaskov, Fan Bu, Matthew Johnson-Roberson, Ram Vasudevan
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous mobile robots must operate with limited sensor horizons in unpredictable environments. To do so, they use a receding-horizon strategy to plan trajectories, by executing a short plan while creating the next plan. However, creating safe, dynamically-feasible trajectories in real time is challenging; and, planners must ensure that they are persistently feasible, meaning that a new trajectory is always available before the previous one has finished executing. Existing approaches make a tradeoff between model complexity and planning speed, which can require sacrificing guarantees of safety and dynamic feasibility. This work presents the Reachability-based Trajectory Design (RTD) method for trajectory planning. RTD begins with an offline Forward Reachable Set (FRS) computation of a robot's motion while it tracks parameterized trajectories; the FRS also provably bounds tracking error. At runtime, the FRS is used to map obstacles to the space of parameterized trajectories, which allows RTD to select a safe trajectory at every planning iteration. RTD prescribes a method of representing obstacles to ensure that these constraints can be created and evaluated in real time while maintaining provable safety. Persistent feasibility is achieved by prescribing a minimum duration of planned trajectories, and a minimum sensor horizon. A system decomposition approach is used to increase the dimension of the parameterized trajectories in the FRS, allowing for RTD to create more complex plans at runtime. RTD is compared in simulation with Rapidly-exploring Random Trees (RRT) and Nonlinear Model-Predictive Control (NMPC). RTD is also demonstrated on two hardware platforms in randomly-crafted environments: a differential-drive Segway, and a car-like Rover. The proposed method is shown as safe and persistently feasible across thousands of simulations and dozens of hardware demos.

##### Abstract (translated by Google)
自主移动机器人必须在不可预测的环境中以有限的传感器视野运行。为此，他们使用后退地平线策略来计划轨迹，在创建下一个计划时执行一个简短的计划。然而，实时创建安全，动态可行的轨迹具有挑战性;并且，规划人员必须确保它们始终可行，这意味着在前一个轨迹完成执行之前始终可用新轨迹。现有方法在模型复杂性和计划速度之间进行权衡，这可能需要牺牲安全性和动态可行性的保证。这项工作为轨迹规划提出了基于可达性的轨迹设计（RTD）方法。 RTD以机器人运动的离线前向可达集（FRS）计算开始，同时跟踪参数化轨迹; FRS也证明了跟踪误差。在运行时，FRS用于将障碍物映射到参数化轨迹的空间，这允许RTD在每次计划迭代时选择安全轨迹。 RTD规定了一种表示障碍的方法，以确保可以在保持可证明的安全性的同时实时创建和评估这些约束。通过规定计划轨迹的最小持续时间和最小传感器范围来实现持久可行性。系统分解方法用于增加FRS中参数化轨迹的维度，允许RTD在运行时创建更复杂的计划。在模拟中将RTD与快速探索随机树（RRT）和非线性模型 - 预测控制（NMPC）进行比较。 RTD还在随机制作的环境中的两个硬件平台上展示：差速驱动Segway和类似汽车的Rover。所提出的方法在数千个模拟和数十个硬件演示中显示为安全且持久可行。

##### URL
[http://arxiv.org/abs/1809.06746](http://arxiv.org/abs/1809.06746)

##### PDF
[http://arxiv.org/pdf/1809.06746](http://arxiv.org/pdf/1809.06746)

