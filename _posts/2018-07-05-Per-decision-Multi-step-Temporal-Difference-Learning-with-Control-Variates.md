---
layout: post
title: "Per-decision Multi-step Temporal Difference Learning with Control Variates"
date: 2018-07-05 02:34:40
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Kristopher De Asis, Richard S. Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-step temporal difference (TD) learning is an important approach in reinforcement learning, as it unifies one-step TD learning with Monte Carlo methods in a way where intermediate algorithms can outperform either extreme. They address a bias-variance trade off between reliance on current estimates, which could be poor, and incorporating longer sampled reward sequences into the updates. Especially in the off-policy setting, where the agent aims to learn about a policy different from the one generating its behaviour, the variance in the updates can cause learning to diverge as the number of sampled rewards used in the estimates increases. In this paper, we introduce per-decision control variates for multi-step TD algorithms, and compare them to existing methods. Our results show that including the control variates can greatly improve performance on both on and off-policy multi-step temporal difference learning tasks.

##### Abstract (translated by Google)
多步时间差（TD）学习是强化学习中的一种重要方法，因为它将一步法TD学习与蒙特卡罗方法结合起来，其中中间算法可以胜过任何极端。它们解决了依赖当前估计（可能很差）和将更长的抽样奖励序列纳入更新之间的偏差 - 方差权衡。特别是在非政策环境中，代理人旨在了解与产生其行为的政策不同的政策，随着估计中使用的抽样奖励数量的增加，更新中的差异可能导致学习分歧。在本文中，我们介绍了多步TD算法的每决策控制变量，并将它们与现有方法进行了比较。我们的结果表明，包含控制变量可以大大提高开启和关闭策略多步时间差异学习任务的性能。

##### URL
[http://arxiv.org/abs/1807.01830](http://arxiv.org/abs/1807.01830)

##### PDF
[http://arxiv.org/pdf/1807.01830](http://arxiv.org/pdf/1807.01830)

