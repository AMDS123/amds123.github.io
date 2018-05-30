---
layout: post
title: "Observe and Look Further: Achieving Consistent Performance on Atari"
date: 2018-05-29 17:19:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tobias Pohlen, Bilal Piot, Todd Hester, Mohammad Gheshlaghi Azar, Dan Horgan, David Budden, Gabriel Barth-Maron, Hado van Hasselt, John Quan, Mel Ve&#x10d;er&#xed;k, Matteo Hessel, R&#xe9;mi Munos, Olivier Pietquin
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant advances in the field of deep Reinforcement Learning (RL), today's algorithms still fail to learn human-level policies consistently over a set of diverse tasks such as Atari 2600 games. We identify three key challenges that any algorithm needs to master in order to perform well on all games: processing diverse reward distributions, reasoning over long time horizons, and exploring efficiently. In this paper, we propose an algorithm that addresses each of these challenges and is able to learn human-level policies on nearly all Atari games. A new transformed Bellman operator allows our algorithm to process rewards of varying densities and scales; an auxiliary temporal consistency loss allows us to train stably using a discount factor of $\gamma = 0.999$ (instead of $\gamma = 0.99$) extending the effective planning horizon by an order of magnitude; and we ease the exploration problem by using human demonstrations that guide the agent towards rewarding states. When tested on a set of 42 Atari games, our algorithm exceeds the performance of an average human on 40 games using a common set of hyper parameters. Furthermore, it is the first deep RL algorithm to solve the first level of Montezuma's Revenge.

##### Abstract (translated by Google)
尽管在深度强化学习（RL）领域取得了重大进展，但今天的算法仍然无法在诸如Atari 2600游戏等一系列不同的任务中始终如一地学习人类级别的策略。我们确定了任何算法为了在所有游戏中表现良好而需要掌握的三个关键挑战：处理各种奖励分配，推理长时间视野以及高效探索。在本文中，我们提出了一种解决这些挑战的算法，并且能够在几乎所有Atari游戏上学习人类级别的策略。一个新的转换Bellman算子允许我们的算法处理不同密度和尺度的奖励;辅助时间一致性损失允许我们使用折扣因子$ \ gamma = 0.999 $（而不是$ \ gamma = 0.99 $）将有效计划范围延长一个数量级来稳定训练;我们通过使用指导代理人实现奖励状态的人类示威来缓解探索问题。当在一组42个Atari游戏上进行测试时，我们的算法使用一组通用的超参数超过40个游戏中的普通人的性能。此外，它是第一个解决蒙特祖马复仇第一级的深度RL算法。

##### URL
[http://arxiv.org/abs/1805.11593](http://arxiv.org/abs/1805.11593)

##### PDF
[http://arxiv.org/pdf/1805.11593](http://arxiv.org/pdf/1805.11593)

