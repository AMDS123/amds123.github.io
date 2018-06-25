---
layout: post
title: "On Learning Intrinsic Rewards for Policy Gradient Methods"
date: 2018-06-22 17:50:24
categories: arXiv_AI
tags: arXiv_AI
author: Zeyu Zheng, Junhyuk Oh, Satinder Singh
mathjax: true
---

* content
{:toc}

##### Abstract
In many sequential decision making tasks, it is challenging to design reward functions that help an RL agent efficiently learn behavior that is considered good by the agent designer. A number of different formulations of the reward-design problem, or close variants thereof, have been proposed in the literature. In this paper we build on the Optimal Rewards Framework of Singh et.al. that defines the optimal intrinsic reward function as one that when used by an RL agent achieves behavior that optimizes the task-specifying or extrinsic reward function. Previous work in this framework has shown how good intrinsic reward functions can be learned for lookahead search based planning agents. Whether it is possible to learn intrinsic reward functions for learning agents remains an open problem. In this paper we derive a novel algorithm for learning intrinsic rewards for policy-gradient based learning agents. We compare the performance of an augmented agent that uses our algorithm to provide additive intrinsic rewards to an A2C-based policy learner (for Atari games) and a PPO-based policy learner (for Mujoco domains) with a baseline agent that uses the same policy learners but with only extrinsic rewards. Our results show improved performance on most but not all of the domains.

##### Abstract (translated by Google)
在很多顺序决策任务中，设计奖励函数是非常具有挑战性的，这有助于RL代理有效地学习代理设计者认为良好的行为。在文献中已经提出了奖励设计问题的许多不同的表达方式或其近似的变体。在本文中，我们构建了Singh et.al的最佳奖励框架。将最优内在奖励函数定义为当由RL代理使用时实现优化任务指定或外在奖励函数的行为。这个框架中的以前的工作已经表明了基于先行搜索的计划代理可以学习到多好的内在奖励函数。是否有可能为学习代理学习内在奖励功能仍然是一个悬而未决的问题。在本文中，我们推导出一种新的基于策略梯度学习代理学习内在奖励的算法。我们比较了使用我们算法的增强型代理的性能，以便为基于A2C的策略学习者（针对Atari游戏）和基于PPO的策略学习者（针对Mujoco域）提供基础代理使用相同策略学习者，但只有外在奖励。我们的研究结果显示大多数领域的表现都有所提高，但并非全部领域。

##### URL
[http://arxiv.org/abs/1804.06459](http://arxiv.org/abs/1804.06459)

##### PDF
[http://arxiv.org/pdf/1804.06459](http://arxiv.org/pdf/1804.06459)

