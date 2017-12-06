---
layout: post
title: "Uncertainty Estimates for Efficient Neural Network-based Dialogue Policy Optimisation"
date: 2017-11-30 16:09:02
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Christopher Tegho, Paweł Budzianowski, Milica Gašić
mathjax: true
---

* content
{:toc}

##### Abstract
In statistical dialogue management, the dialogue manager learns a policy that maps a belief state to an action for the system to perform. Efficient exploration is key to successful policy optimisation. Current deep reinforcement learning methods are very promising but rely on epsilon-greedy exploration, thus subjecting the user to a random choice of action during learning. Alternative approaches such as Gaussian Process SARSA (GPSARSA) estimate uncertainties and are sample efficient, leading to better user experience, but on the expense of a greater computational complexity. This paper examines approaches to extract uncertainty estimates from deep Q-networks (DQN) in the context of dialogue management. We perform an extensive benchmark of deep Bayesian methods to extract uncertainty estimates, namely Bayes-By-Backprop, dropout, its concrete variation, bootstrapped ensemble and alpha-divergences, combining it with DQN algorithm.

##### Abstract (translated by Google)
在统计对话管理中，对话管理者学习将信念状态映射到系统执行动作的策略。高效的探索是成功策略优化的关键。目前的深度强化学习方法是非常有前途的，但依靠ε-贪婪的探索，从而使用户在学习过程中随机选择行动。诸如高斯过程SARSA（GPSARSA）的替代方法估计不确定性并且样本有效，导致更好的用户体验，但是以更大的计算复杂度为代价。本文研究了在对话管理的背景下从深度Q网络（DQN）中提取不确定性估计的方法。我们进行深度贝叶斯方法的广泛基准来提取不确定性估计，即Bayes-By-Backprop，辍学，具体变化，自举集合和α发散，将其与DQN算法相结合。

##### URL
[https://arxiv.org/abs/1711.11486](https://arxiv.org/abs/1711.11486)

