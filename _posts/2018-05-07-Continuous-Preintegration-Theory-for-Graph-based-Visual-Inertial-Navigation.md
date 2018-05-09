---
layout: post
title: "Continuous Preintegration Theory for Graph-based Visual-Inertial Navigation"
date: 2018-05-07 23:08:15
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Kevin Eckenhoff, Patrick Geneva, Guoquan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a new continuous preintegration theory for graph-based sensor fusion with an inertial measurement unit (IMU) and a camera (or other aiding sensors). Rather than using discrete sampling of the measurement dynamics as in current methods, we analytically derive the closed-form solutions to the preintegration equations, yielding improved accuracy in state estimation. We advocate two new different inertial models for preintegration: (i) the model that assumes piecewise constant measurements, and (ii) the model that assumes piecewise constant local true acceleration. We show through extensive Monte-Carlo simulations the effect that the choice of preintegration model has on estimation performance. To validate the proposed preintegration theory, we develop both direct and indirect visual-inertial navigation systems (VINS) that leverage our preintegration. In the first, within a tightly-coupled, sliding-window optimization framework, we jointly estimate the features in the window and the IMU states while performing marginalization to bound the computational cost. In the second, we loosely couple the IMU preintegration with a direct image alignment that estimates relative camera motion by minimizing the photometric errors (i.e., raw image intensity difference), allowing for efficient and informative loop closures. Both systems are extensively tested in real-world experiments and are shown to offer competitive performance to state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一个新的连续的惯性测量单元（IMU）和相机（或其他辅助传感器）基于图形的传感器融合的连续预先积分理论。我们不是像现有方法那样使用离散的测量动态采样，而是通过解析导出预合成方程的封闭形式解，从而提高状态估计的准确性。我们主张两种新的不同惯性模型用于预整合：（i）假设分段恒定测量的模型，以及（ii）假设分段恒定局部真实加速度的模型。我们通过广泛的蒙特卡罗模拟展示了预估模型的选择对估计性能的影响。为了验证所提出的预整合理论，我们开发了直接和间接视觉 - 惯性导航系统（VINS），这些系统利用了我们的预先整合。首先，在紧密耦合的滑动窗口优化框架内，我们联合估计窗口中的特征和IMU状态，同时执行边缘化来限制计算成本。第二，我们将IMU预整合与直接图像对齐松散耦合，直接图像对齐通过最小化光度误差（即原始图像强度差异）来估计相对的相机运动，从而允许有效且信息丰富的环路闭合。这两个系统都在真实世界的实验中进行了广泛的测试，并被证明可以为最先进的方法提供具有竞争力的性能。

##### URL
[http://arxiv.org/abs/1805.02774](http://arxiv.org/abs/1805.02774)

##### PDF
[http://arxiv.org/pdf/1805.02774](http://arxiv.org/pdf/1805.02774)

