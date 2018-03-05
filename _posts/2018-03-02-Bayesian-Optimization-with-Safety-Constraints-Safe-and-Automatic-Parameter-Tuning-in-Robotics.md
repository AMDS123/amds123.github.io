---
layout: post
title: "Bayesian Optimization with Safety Constraints: Safe and Automatic Parameter Tuning in Robotics"
date: 2018-03-02 17:42:52
categories: arXiv_RO
tags: arXiv_RO Knowledge Tracking Optimization
author: Felix Berkenkamp, Andreas Krause, Angela P. Schoellig
mathjax: true
---

* content
{:toc}

##### Abstract
Robotic algorithms typically depend on various parameters, the choice of which significantly affects the robot's performance. While an initial guess for the parameters may be obtained from dynamic models of the robot, parameters are usually tuned manually on the real system to achieve the best performance. Optimization algorithms, such as Bayesian optimization, have been used to automate this process. However, these methods may evaluate unsafe parameters during the optimization process that lead to safety-critical system failures. Recently, a safe Bayesian optimization algorithm, called SafeOpt, has been developed, which guarantees that the performance of the system never falls below a critical value; that is, safety is defined based on the performance function. However, coupling performance and safety is often not desirable in robotics. For example, high-gain controllers might achieve low average tracking error (performance), but can overshoot and violate input constraints. In this paper, we present a generalized algorithm that allows for multiple safety constraints separate from the objective. Given an initial set of safe parameters, the algorithm maximizes performance but only evaluates parameters that satisfy safety for all constraints with high probability. To this end, it carefully explores the parameter space by exploiting regularity assumptions in terms of a Gaussian process prior. Moreover, we show how context variables can be used to safely transfer knowledge to new situations and tasks. We provide a theoretical analysis and demonstrate that the proposed algorithm enables fast, automatic, and safe optimization of tuning parameters in experiments on a quadrotor vehicle.

##### Abstract (translated by Google)
机器人算法通常取决于各种参数，其选择会显着影响机器人的性能。尽管可以从机器人的动态模型获得参数的初始猜测，但通常在真实系统上手动调整参数以实现最佳性能。优化算法（如贝叶斯优化）已用于使此过程自动化。但是，这些方法可能会在优化过程中评估不安全参数，导致安全关键系统故障。最近，开发了一种名为SafeOpt的安全贝叶斯优化算法，该算法保证了系统的性能不会低于临界值;即基于性能函数来定义安全性。然而，机器人技术往往不希望耦合性能和安全性。例如，高增益控制器可能会实现低平均跟踪误差（性能），但可能会超调并违反输入限制。在本文中，我们提出了一种通用算法，允许将多个安全约束与目标分开。给定一组初始安全参数，该算法使性能最大化，但只评估满足所有约束条件下安全性高的参数的概率。为此，它通过利用先前的高斯过程的规律假设仔细探索参数空间。此外，我们还展示了如何使用上下文变量将知识安全地转移到新的情况和任务。我们提供理论分析，并证明所提出的算法能够在四旋翼飞行器实验中快速，自动和安全地优化调谐参数。

##### URL
[http://arxiv.org/abs/1602.04450](http://arxiv.org/abs/1602.04450)

##### PDF
[http://arxiv.org/pdf/1602.04450](http://arxiv.org/pdf/1602.04450)

