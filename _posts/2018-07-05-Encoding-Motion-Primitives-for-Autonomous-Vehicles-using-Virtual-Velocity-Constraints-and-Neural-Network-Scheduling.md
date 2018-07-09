---
layout: post
title: "Encoding Motion Primitives for Autonomous Vehicles using Virtual Velocity Constraints and Neural Network Scheduling"
date: 2018-07-05 21:44:39
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Mogens Graf Plessen
mathjax: true
---

* content
{:toc}

##### Abstract
Within the context of trajectory planning for autonomous vehicles this paper proposes methods for efficient encoding of motion primitives in neural networks on top of model-based and gradient-free reinforcement learning. It is distinguished between 5 core aspects: system model, network architecture, training algorithm, training tasks selection and hardware/software implementation. For the system model, a kinematic (3-states-2-controls) and a dynamic (16-states-2-controls) vehicle model are compared. For the network architecture, 3 feedforward structures are compared including weighted skip connections. For the training algorithm, virtual velocity constraints and network scheduling are proposed. For the training tasks, different feature vector selections are discussed. For the implementation, aspects of gradient-free learning using 1 GPU and the handling of perturbation noise therefore are discussed. The effects of proposed methods are illustrated in experiments encoding up to 14625 motion primitives. The capabilities of tiny neural networks with as few as 10 scalar parameters when scheduled on vehicle velocity are emphasized.

##### Abstract (translated by Google)
在自动驾驶汽车轨迹规划的背景下，本文提出了在基于模型和无梯度强化学习的基础上有效编码神经网络中运动图元的方法。它区分了5个核心方面：系统模型，网络架构，训练算法，训练任务选择和硬件/软件实现。对于系统模型，比较运动学（3状态2-控制）和动态（16状态2-控制）车辆模型。对于网络架构，比较了3个前馈结构，包括加权跳过连接。针对训练算法，提出了虚拟速度约束和网络调度。对于训练任务，讨论了不同的特征向量选择。为了实现，讨论了使用1 GPU的无梯度学习和处理扰动噪声的方面。在编码多达14625个运动基元的实验中说明了所提出方法的效果。强调了在车辆速度上调度时具有少至10个标量参数的微小神经网络的能力。

##### URL
[http://arxiv.org/abs/1807.02187](http://arxiv.org/abs/1807.02187)

##### PDF
[http://arxiv.org/pdf/1807.02187](http://arxiv.org/pdf/1807.02187)

