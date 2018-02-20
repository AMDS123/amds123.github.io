---
layout: post
title: "Accelerated Primal-Dual Policy Optimization for Safe Reinforcement Learning"
date: 2018-02-19 01:25:26
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Qingkai Liang, Fanyu Que, Eytan Modiano
mathjax: true
---

* content
{:toc}

##### Abstract
Constrained Markov Decision Process (CMDP) is a natural framework for reinforcement learning tasks with safety constraints, where agents learn a policy that maximizes the long-term reward while satisfying the constraints on the long-term cost. A canonical approach for solving CMDPs is the primal-dual method which updates parameters in primal and dual spaces in turn. Existing methods for CMDPs only use on-policy data for dual updates, which results in sample inefficiency and slow convergence. In this paper, we propose a policy search method for CMDPs called Accelerated Primal-Dual Optimization (APDO), which incorporates an off-policy trained dual variable in the dual update procedure while updating the policy in primal space with on-policy likelihood ratio gradient. Experimental results on a simulated robot locomotion task show that APDO achieves better sample efficiency and faster convergence than state-of-the-art approaches for CMDPs.

##### Abstract (translated by Google)
约束马尔可夫决策过程（CMDP）是具有安全约束的强化学习任务的自然框架，其中主体学习一种在满足长期成本约束的同时最大化长期回报的策略。解决CMDP的规范方法是依次更新原始和双重空间参数的原始 - 对偶方法。现有的CMDP方法仅使用on-policy数据进行双重更新，导致样本无效率和收敛速度缓慢。在本文中，我们提出了一种称为加速原始 - 对偶优化（APDO）的策略搜索方法，该策略在双重更新过程中包含关闭策略训练的双变量，同时更新原策略空间中策略似然比梯度。模拟机器人运动任务的实验结果表明，APDO比CMD的最先进方法获得了更好的采样效率和更快的收敛速度。

##### URL
[http://arxiv.org/abs/1802.06480](http://arxiv.org/abs/1802.06480)

##### PDF
[http://arxiv.org/pdf/1802.06480](http://arxiv.org/pdf/1802.06480)

