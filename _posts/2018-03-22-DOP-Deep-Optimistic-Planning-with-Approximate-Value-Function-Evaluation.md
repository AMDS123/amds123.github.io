---
layout: post
title: "DOP: Deep Optimistic Planning with Approximate Value Function Evaluation"
date: 2018-03-22 14:59:16
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Francesco Riccio, Roberto Capobianco, Daniele Nardi
mathjax: true
---

* content
{:toc}

##### Abstract
Research on reinforcement learning has demonstrated promising results in manifold applications and domains. Still, efficiently learning effective robot behaviors is very difficult, due to unstructured scenarios, high uncertainties, and large state dimensionality (e.g. multi-agent systems or hyper-redundant robots). To alleviate this problem, we present DOP, a deep model-based reinforcement learning algorithm, which exploits action values to both (1) guide the exploration of the state space and (2) plan effective policies. Specifically, we exploit deep neural networks to learn Q-functions that are used to attack the curse of dimensionality during a Monte-Carlo tree search. Our algorithm, in fact, constructs upper confidence bounds on the learned value function to select actions optimistically. We implement and evaluate DOP on different scenarios: (1) a cooperative navigation problem, (2) a fetching task for a 7-DOF KUKA robot, and (3) a human-robot handover with a humanoid robot (both in simulation and real). The obtained results show the effectiveness of DOP in the chosen applications, where action values drive the exploration and reduce the computational demand of the planning process while achieving good performance.

##### Abstract (translated by Google)
关于强化学习的研究已经在多种应用和领域中表现出有希望的结果由于非结构化场景，高不确定性和大状态维度（例如多代理系统或超冗余机器人），仍然要有效地学习有效的机器人行为非常困难。为了缓解这个问题，我们提出了一种基于深度模型的强化学习算法DOP，该算法利用动作值来（1）指导状态空间的探索和（2）计划有效的策略。具体而言，我们利用深度神经网络来学习在Monte-Carlo树搜索期间用于攻击维度诅咒的Q函数。实际上，我们的算法构造了学习值函数的上置信区间以乐观地选择动作。我们在不同的场景下实现和评估DOP：（1）协作导航问题;（2）七自由度库卡机器人的取物任务;（3）人机器人交接，包括仿人机器人）。获得的结果显示DOP在选定应用程序中的有效性，其中行动值驱动勘探并减少规划过程的计算需求，同时实现良好的性能。

##### URL
[https://arxiv.org/abs/1803.08501](https://arxiv.org/abs/1803.08501)

##### PDF
[https://arxiv.org/pdf/1803.08501](https://arxiv.org/pdf/1803.08501)

