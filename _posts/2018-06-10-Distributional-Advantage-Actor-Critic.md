---
layout: post
title: "Distributional Advantage Actor-Critic"
date: 2018-06-10 06:17:53
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Shangda Li, Selina Bing, Steven Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In traditional reinforcement learning, an agent maximizes the reward collected during its interaction with the environment by approximating the optimal policy through the estimation of value functions. Typically, given a state s and action a, the corresponding value is the expected discounted sum of rewards. The optimal action is then chosen to be the action a with the largest value estimated by value function. However, recent developments have shown both theoretical and experimental evidence of superior performance when value function is replaced with value distribution in context of deep Q learning [1]. In this paper, we develop a new algorithm that combines advantage actor-critic with value distribution estimated by quantile regression. We evaluated this new algorithm, termed Distributional Advantage Actor-Critic (DA2C or QR-A2C) on a variety of tasks, and observed it to achieve at least as good as baseline algorithms, and outperforming baseline in some tasks with smaller variance and increased stability.

##### Abstract (translated by Google)
在传统的强化学习中，主体通过估计价值函数来近似最优策略，从而最大化在与环境交互期间收集的回报。通常情况下，给定状态和行动a，相应的值就是期望的奖励折扣总和。然后选择最佳动作为具有通过值函数估计的最大值的动作a。然而，最近的发展表明，当价值函数被深度Q学习背景下的价值分配所取代时，理论和实验证明了优越的性能[1]。在本文中，我们开发了一种新的算法，将优势行为者评论与通过分位数回归估计的价值分布相结合。我们评估了这种新算法，在各种任务中称为分布式优势角色 - 评论者（DA2C或QR-A2C），并观察它达到至少与基线算法一样好，并且在一些任务中表现优于基线，方差较小，稳定性增加。

##### URL
[http://arxiv.org/abs/1806.06914](http://arxiv.org/abs/1806.06914)

##### PDF
[http://arxiv.org/pdf/1806.06914](http://arxiv.org/pdf/1806.06914)

