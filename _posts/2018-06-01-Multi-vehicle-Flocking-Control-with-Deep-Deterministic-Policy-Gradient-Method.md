---
layout: post
title: "Multi-vehicle Flocking Control with Deep Deterministic Policy Gradient Method"
date: 2018-06-01 05:11:46
categories: arXiv_RO
tags: arXiv_RO Tracking Reinforcement_Learning
author: Yang Lyu, Quan Pan, Jinwen Hu, Chunhui Zhao, Shuai Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Flocking control has been studied extensively along with the wide application of multi-vehicle systems. In this paper the Multi-vehicles System (MVS) flocking control with collision avoidance and communication preserving is considered based on the deep reinforcement learning framework. Specifically the deep deterministic policy gradient (DDPG) with centralized training and distributed execution process is implemented to obtain the flocking control policy. First, to avoid the dynamically changed observation of state, a three layers tensor based representation of the observation is used so that the state remains constant although the observation dimension is changing. A reward function is designed to guide the way-points tracking, collision avoidance and communication preserving. The reward function is augmented by introducing the local reward function of neighbors. Finally, a centralized training process which trains the shared policy based on common training set among all agents. The proposed method is tested under simulated scenarios with different setup.

##### Abstract (translated by Google)
随着多车辆系统的广泛应用，广泛研究了植绒控制。在本文中，基于深度强化学习框架考虑了具有避碰和通信保持的多车辆系统（MVS）植绒控制。具体而言，实施了具有集中训练和分布式执行过程的深度确定性策略梯度（DDPG）以获得植绒控制策略。首先，为了避免动态变化的状态观察，使用基于三层张量的观察表示，以便尽管观察维度在变化，但状态保持不变。奖励功能旨在指导方式 - 点跟踪，避免碰撞和保持通信。通过引入邻居的本地奖励功能来增加奖励功能。最后，一个集中的培训过程，根据所有代理人之间的共同培训集合来训练共享策略。所提出的方法在不同设置的模拟场景下进行测试。

##### URL
[http://arxiv.org/abs/1806.00196](http://arxiv.org/abs/1806.00196)

##### PDF
[http://arxiv.org/pdf/1806.00196](http://arxiv.org/pdf/1806.00196)

