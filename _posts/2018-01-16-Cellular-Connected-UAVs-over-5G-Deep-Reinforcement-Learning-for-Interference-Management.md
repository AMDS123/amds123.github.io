---
layout: post
title: "Cellular-Connected UAVs over 5G: Deep Reinforcement Learning for Interference Management"
date: 2018-01-16 22:35:55
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ursula Challita, Walid Saad, Christian Bettstetter
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, an interference-aware path planning scheme for a network of cellular-connected unmanned aerial vehicles (UAVs) is proposed. In particular, each UAV aims at achieving a tradeoff between maximizing energy efficiency and minimizing both wireless latency and the interference level caused on the ground network along its path. The problem is cast as a dynamic game among UAVs. To solve this game, a deep reinforcement learning algorithm, based on echo state network (ESN) cells, is proposed. The introduced deep ESN architecture is trained to allow each UAV to map each observation of the network state to an action, with the goal of minimizing a sequence of time-dependent utility functions. Each UAV uses ESN to learn its optimal path, transmission power level, and cell association vector at different locations along its path. The proposed algorithm is shown to reach a subgame perfect Nash equilibrium (SPNE) upon convergence. Moreover, an upper and lower bound for the altitude of the UAVs is derived thus reducing the computational complexity of the proposed algorithm. Simulation results show that the proposed scheme achieves better wireless latency per UAV and rate per ground user (UE) while requiring a number of steps that is comparable to a heuristic baseline that considers moving via the shortest distance towards the corresponding destinations. The results also show that the optimal altitude of the UAVs varies based on the ground network density and the UE data rate requirements and plays a vital role in minimizing the interference level on the ground UEs as well as the wireless transmission delay of the UAV.

##### Abstract (translated by Google)
本文提出了一种蜂窝无线架空无人机网络干扰感知路径规划方案。特别是，每个无人机的目标是实现能效最大化和无线等待时间与地面网络沿途干扰水平的最小化。这个问题被当作无人机之间的动态游戏。为了解决这个问题，提出了一种基于回波状态网络（ESN）的深度强化学习算法。引入的深度ESN架构经过训练，允许每个无人机将每个观察的网络状态映射到一个动作，其目的是最小化一系列时间相关的效用函数。每个无人机使用ESN学习其路径上不同位置的最佳路径，发射功率电平和小区关联矢量。本文提出的算法在收敛后达到子博弈完美纳什均衡（SPNE）。此外，还导出了无人机高度的上下界，从而降低了算法的计算复杂度。仿真结果表明，所提出的方案实现了每个无人机和每个地面用户（UE）的更好的无线延迟，同时需要与考虑通过到相应目的地的最短距离移动的启发式基线相当的多个步骤。结果还表明，无人机的最优高度根据地面网络密度和用户设备数据速率的要求而变化，对于最小化地面UE的干扰水平以及无人机的无线传输时延起着至关重要的作用。

##### URL
[http://arxiv.org/abs/1801.05500](http://arxiv.org/abs/1801.05500)

##### PDF
[http://arxiv.org/pdf/1801.05500](http://arxiv.org/pdf/1801.05500)

