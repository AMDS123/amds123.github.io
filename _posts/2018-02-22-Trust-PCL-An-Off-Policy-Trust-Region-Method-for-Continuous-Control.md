---
layout: post
title: "Trust-PCL: An Off-Policy Trust Region Method for Continuous Control"
date: 2018-02-22 21:28:57
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Ofir Nachum, Mohammad Norouzi, Kelvin Xu, Dale Schuurmans
mathjax: true
---

* content
{:toc}

##### Abstract
Trust region methods, such as TRPO, are often used to stabilize policy optimization algorithms in reinforcement learning (RL). While current trust region strategies are effective for continuous control, they typically require a prohibitively large amount of on-policy interaction with the environment. To address this problem, we propose an off-policy trust region method, Trust-PCL. The algorithm is the result of observing that the optimal policy and state values of a maximum reward objective with a relative-entropy regularizer satisfy a set of multi-step pathwise consistencies along any path. Thus, Trust-PCL is able to maintain optimization stability while exploiting off-policy data to improve sample efficiency. When evaluated on a number of continuous control tasks, Trust-PCL improves the solution quality and sample efficiency of TRPO.

##### Abstract (translated by Google)
诸如TRPO之类的信任区域方法通常用于稳定强化学习（RL）中的策略优化算法。虽然目前的信任区域策略对持续控制有效，但它们通常需要与环境进行大量的政策上互动。为了解决这个问题，我们提出了一种非信任域策略Trust-PCL。该算法是观察到利用相对熵正规化器的最大奖励目标的最优策略和状态值满足沿着任何路径的一组多步路径一致性的结果。因此，Trust-PCL能够保持优化稳定性，同时利用关闭策略数据来提高样本效率。当对许多连续控制任务进行评估时，Trust-PCL可以提高TRPO的解决方案质量和样本效率。

##### URL
[http://arxiv.org/abs/1707.01891](http://arxiv.org/abs/1707.01891)

##### PDF
[http://arxiv.org/pdf/1707.01891](http://arxiv.org/pdf/1707.01891)

