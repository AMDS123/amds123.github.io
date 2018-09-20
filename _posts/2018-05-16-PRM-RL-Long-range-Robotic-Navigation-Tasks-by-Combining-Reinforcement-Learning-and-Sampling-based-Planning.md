---
layout: post
title: "PRM-RL: Long-range Robotic Navigation Tasks by Combining Reinforcement Learning and Sampling-based Planning"
date: 2018-05-16 07:05:43
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Aleksandra Faust, Oscar Ramirez, Marek Fiser, Kenneth Oslund, Anthony Francis, James Davidson, Lydia Tapia
mathjax: true
---

* content
{:toc}

##### Abstract
We present PRM-RL, a hierarchical method for long-range navigation task completion that combines sampling based path planning with reinforcement learning (RL). The RL agents learn short-range, point-to-point navigation policies that capture robot dynamics and task constraints without knowledge of the large-scale topology. Next, the sampling-based planners provide roadmaps which connect robot configurations that can be successfully navigated by the RL agent. The same RL agents are used to control the robot under the direction of the planning, enabling long-range navigation. We use the Probabilistic Roadmaps (PRMs) for the sampling-based planner. The RL agents are constructed using feature-based and deep neural net policies in continuous state and action spaces. We evaluate PRM-RL, both in simulation and on-robot, on two navigation tasks with non-trivial robot dynamics: end-to-end differential drive indoor navigation in office environments, and aerial cargo delivery in urban environments with load displacement constraints. Our results show improvement in task completion over both RL agents on their own and traditional sampling-based planners. In the indoor navigation task, PRM-RL successfully completes up to 215 m long trajectories under noisy sensor conditions, and the aerial cargo delivery completes flights over 1000 m without violating the task constraints in an environment 63 million times larger than used in training.

##### Abstract (translated by Google)
我们提出PRM-RL，一种用于远程导航任务完成的分层方法，它将基于采样的路径规划与强化学习（RL）相结合。 RL代理学习短距离，点对点导航策略，捕获机器人动态和任务约束，而无需了解大规模拓扑。接下来，基于采样的规划器提供路线图，其连接可由RL代理成功导航的机器人配置。相同的RL代理用于在规划的指导下控制机器人，从而实现远程导航。我们将概率路线图（PRM）用于基于抽样的规划器。 RL代理是在连续状态和动作空间中使用基于特征和深度神经网络策略构建的。我们在模拟和机器人上评估两种导航任务中的PRM-RL，其中包括非平凡的机器人动力学：办公环境中的端到端差分驱动室内导航，以及负载位移约束的城市环境中的空中货物交付。我们的结果表明，RL代理商和传统的基于抽样的规划人员的任务完成都有所改善。在室内导航任务中，PRM-RL在嘈杂的传感器条件下成功完成了长达215米的航迹，并且航空货物交付完成了超过1000米的飞行，而不会在比训练中使用的环境大6300万的环境中违反任务限制。

##### URL
[http://arxiv.org/abs/1710.03937](http://arxiv.org/abs/1710.03937)

##### PDF
[http://arxiv.org/pdf/1710.03937](http://arxiv.org/pdf/1710.03937)

