---
layout: post
title: "A Minimax Tree Based Approach for Minimizing Detectability and Maximizing Visibility"
date: 2018-07-25 05:21:34
categories: arXiv_RO
tags: arXiv_RO Adversarial
author: Zhongshun Zhang, Yoonchang Sung, Lifeng Zhou, Jonathon M. Smereka, Joseph Lee, Pratap Tokekar
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce and study the problem of planning a trajectory for an agent to carry out a scouting mission while avoiding being detected by an adversarial guard. This introduces an adversarial version of classical visibility-based planning problems such as the Watchman Route Problem. The agent receives a positive reward for increasing its visibility and a negative penalty when it is detected by the guard. The objective is to find a finite-horizon path for the agent that balances the trade-off maximizing visibility and minimizing detectability. We model this problem as a sequential two-player zero-sum discrete game. A minimax tree search can give the optimal policy for the agent but requires an exponential-time computation and space. We propose several pruning techniques to reduce the computational cost while still preserving optimality guarantees. Simulation results show that the proposed strategy prunes approximately three orders of magnitude nodes as compared to the brute-force strategy.

##### Abstract (translated by Google)
我们介绍和研究规划一个代理人执行侦察任务的轨迹的问题，同时避免被对抗守卫检测到。这引入了基于经典可见性的规划问题的对抗版本，例如守望者路线问题。当警卫检测到时，代理人会获得积极的奖励以增加其可见性和负面惩罚。目标是找到代理的有限范围路径，以平衡权衡最大化可见性和最小化可检测性。我们将此问题建模为连续的双人零和离散游戏。最小极大树搜索可以为代理提供最优策略，但需要指数时计算和空间。我们提出了几种修剪技术来降低计算成本，同时仍保留最优保证。仿真结果表明，与蛮力策略相比，所提出的策略可以修剪大约三个数量级的节点。

##### URL
[http://arxiv.org/abs/1807.09437](http://arxiv.org/abs/1807.09437)

##### PDF
[http://arxiv.org/pdf/1807.09437](http://arxiv.org/pdf/1807.09437)

