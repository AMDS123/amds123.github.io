---
layout: post
title: "PAMPC: Perception-Aware Model Predictive Control for Quadrotors"
date: 2018-07-10 12:14:26
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Davide Falanga, Philipp Foehn, Peng Lu, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first perception-aware model predictive control framework for quadrotors that unifies control and planning with respect to action and perception objectives. Our framework leverages numerical optimization to compute trajectories that satisfy the system dynamics and require control inputs within the limits of the platform. Simultaneously, it optimizes perception objectives for robust and reliable sens- ing by maximizing the visibility of a point of interest and minimizing its velocity in the image plane. Considering both perception and action objectives for motion planning and control is challenging due to the possible conflicts arising from their respective requirements. For example, for a quadrotor to track a reference trajectory, it needs to rotate to align its thrust with the direction of the desired acceleration. However, the perception objective might require to minimize such rotation to maximize the visibility of a point of interest. A model-based optimization framework, able to consider both perception and action objectives and couple them through the system dynamics, is therefore necessary. Our perception-aware model predictive control framework works in a receding-horizon fashion by iteratively solving a non-linear optimization problem. It is capable of running in real-time, fully onboard our lightweight, small-scale quadrotor using a low-power ARM computer, to- gether with a visual-inertial odometry pipeline. We validate our approach in experiments demonstrating (I) the contradiction between perception and action objectives, and (II) improved behavior in extremely challenging lighting conditions.

##### Abstract (translated by Google)
我们提出了第一个用于四旋翼飞行器的感知模型预测控制框架，该框架将动作和感知目标的控制和规划统一起来。我们的框架利用数值优化来计算满足系统动态的轨迹，并要求在平台范围内的控制输入。同时，它通过最大化感兴趣点的可见性并最小化其在图像平面中的速度来优化感知目标以获得稳健可靠的感觉。考虑到运动规划和控制的感知和行动目标，由于各自的要求可能产生冲突，因此具有挑战性。例如，对于跟踪参考轨迹的四旋翼飞行器，需要旋转以使其推力与期望加速度的方向对齐。然而，感知目标可能需要最小化这种旋转以最大化感兴趣点的可见性。因此，基于模型的优化框架能够同时考虑感知和行动目标并通过系统动力学将它们耦合在一起。我们的感知感知模型预测控制框架通过迭代求解非线性优化问题以渐进的方式工作。它能够使用低功率ARM计算机实时运行我们的轻型小型四旋翼飞行器，并配有视觉惯性测距管道。我们在实验中验证了我们的方法，证明了（I）感知和行动目标之间的矛盾，以及（II）在极具挑战性的照明条件下改善了行为。

##### URL
[http://arxiv.org/abs/1804.04811](http://arxiv.org/abs/1804.04811)

##### PDF
[http://arxiv.org/pdf/1804.04811](http://arxiv.org/pdf/1804.04811)

