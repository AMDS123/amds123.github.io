---
layout: post
title: "STEAP: simultaneous trajectory estimation and planning"
date: 2018-07-27 03:49:45
categories: arXiv_RO
tags: arXiv_RO Inference
author: Mustafa Mukadam, Jing Dong, Frank Dellaert, Byron Boots
mathjax: true
---

* content
{:toc}

##### Abstract
We present a unified probabilistic framework for simultaneous trajectory estimation and planning (STEAP). Estimation and planning problems are usually considered separately, however, within our framework we show that solving them simultaneously can be more accurate and efficient. The key idea is to compute the full continuous-time trajectory from start to goal at each time-step. While the robot traverses the trajectory, the history portion of the trajectory signifies the solution to the estimation problem, and the future portion of the trajectory signifies a solution to the planning problem. Building on recent probabilistic inference approaches to continuous-time localization and mapping and continuous-time motion planning, we solve the joint problem by iteratively recomputing the maximum a posteriori trajectory conditioned on all available sensor data and cost information. Our approach can contend with high-degree-of-freedom (DOF) trajectory spaces, uncertainty due to limited sensing capabilities, model inaccuracy, the stochastic effect of executing actions, and can find a solution in real-time. We evaluate our framework empirically in both simulation and on a mobile manipulator.

##### Abstract (translated by Google)
我们提出了一个统一的概率框架，用于同步轨迹估计和规划（STEAP）。估算和规划问题通常是单独考虑的，但是，在我们的框架内，我们表明同时解决它们可以更加准确和有效。关键思想是计算每个时间步骤从开始到目标的完整连续时间轨迹。当机器人遍历轨迹时，轨迹的历史部分表示估计问题的解决方案，并且轨迹的未来部分表示对规划问题的解决方案。基于最近的连续时间定位和映射以及连续时间运动规划的概率推理方法，我们通过迭代地重新计算以所有可用传感器数据和成本信息为条件的最大后验轨迹来解决联合问题。我们的方法可以应对高自由度（DOF）轨迹空间，由于有限的感知能力导致的不确定性，模型不准确性，执行动作的随机效应，以及可以实时找到解决方案。我们在模拟和移动机械手上根据经验评估我们的框架。

##### URL
[https://arxiv.org/abs/1807.10425](https://arxiv.org/abs/1807.10425)

##### PDF
[https://arxiv.org/pdf/1807.10425](https://arxiv.org/pdf/1807.10425)

