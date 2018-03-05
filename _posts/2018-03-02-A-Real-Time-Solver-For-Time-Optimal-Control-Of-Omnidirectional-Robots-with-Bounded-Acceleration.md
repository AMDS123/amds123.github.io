---
layout: post
title: "A Real-Time Solver For Time-Optimal Control Of Omnidirectional Robots with Bounded Acceleration"
date: 2018-03-02 05:17:05
categories: arXiv_RO
tags: arXiv_RO Optimization
author: David Balaban, Alex Fischer, Joydeep Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in the problem of time-optimal control of omnidirectional robots with bounded acceleration (TOC-ORBA). While there exist approximate solutions for such robots, and exact solutions with unbounded acceleration, exact solvers to the TOC-ORBA problem have remained elusive until now. In this paper, we present a real-time solver for true time-optimal control of omnidirectional robots with bounded acceleration. We first derive the general parameterized form of the solution to the TOC-ORBA problem by application of Pontryagin's maximum principle. We then frame the boundary value problem of TOC-ORBA as an optimization problem over the parametrized control space. To overcome local minima and poor initial guesses to the optimization problem, we introduce a two-stage optimal control solver (TSOCS): The first stage computes an upper bound to the total time for the TOC-ORBA problem and holds the time constant while optimizing the parameters of the trajectory to approach the boundary value conditions. The second stage uses the parameters found by the first stage, and relaxes the constraint on the total time to solve for the parameters of the complete TOC-ORBA problem. We further implement TSOCS as a closed loop controller to overcome actuation errors on real robots in real-time. We empirically demonstrate the effectiveness of TSOCS in simulation and on real robots, showing that 1) it runs in real time, generating solutions in less than 0.5ms on average; 2) it generates faster trajectories compared to an approximate solver; and 3) it is able to solve TOC-ORBA problems with non-zero final velocities that were previously unsolvable in real-time.

##### Abstract (translated by Google)
我们感兴趣的是具有有界加速度（TOC-ORBA）的全向机器人的时间最优控制问题。虽然存在这种机器人的近似解决方案，以及具有无限加速度的精确解，但直到现在，TOC-ORBA问题的确切求解器仍然难以捉摸。在本文中，我们提出了一个实时解算器，用于实现具有有界加速度的全向机器人的真正时间最优控制。我们首先通过应用Pontryagin最大原理推导TOC-ORBA问题解的一般参数化形式。然后，我们将TOC-ORBA的边界值问题定义为参数化控制空间上的优化问题。为了克服局部最小值和最优化问题的初步猜测，我们引入了一个两阶段最优控制求解器（TSOCS）：第一阶段计算TOC-ORBA问题总时间的上限，并在优化时保持时间常数轨迹的参数接近边界值条件。第二阶段使用第一阶段找到的参数，并放宽总时间约束来解决完整TOC-ORBA问题的参数。我们进一步实施TSOCS作为闭环控制器，以实时克服真实机器人的致动错误。我们凭经验论证了TSOCS在模拟和真实机器人方面的有效性，表明：1）它实时运行，平均生成时间小于0.5ms; 2）与近似解算器相比，它产生更快的轨迹; 3）它能够解决以前无法实时解决的非零最终速度的TOC-ORBA问题。

##### URL
[http://arxiv.org/abs/1707.04617](http://arxiv.org/abs/1707.04617)

##### PDF
[http://arxiv.org/pdf/1707.04617](http://arxiv.org/pdf/1707.04617)

