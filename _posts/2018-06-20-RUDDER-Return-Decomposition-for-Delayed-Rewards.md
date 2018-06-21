---
layout: post
title: "RUDDER: Return Decomposition for Delayed Rewards"
date: 2018-06-20 17:34:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Jose A. Arjona-Medina, Michael Gillhofer, Michael Widrich, Thomas Unterthiner, Sepp Hochreiter
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel reinforcement learning approach for finite Markov decision processes (MDPs) with delayed rewards. In this work, biases of temporal difference (TD) estimates are proved to be corrected only exponentially slowly in the number of delay steps. Furthermore, variances of Monte Carlo (MC) estimates are proved to increase the variance of other estimates, the number of which can exponentially grow in the number of delay steps. We introduce RUDDER, a return decomposition method, which creates a new MDP with same optimal policies as the original MDP but with redistributed rewards that have largely reduced delays. If the return decomposition is optimal, then the new MDP does not have delayed rewards and TD estimates are unbiased. In this case, the rewards track Q-values so that the future expected reward is always zero. We experimentally confirm our theoretical results on bias and variance of TD and MC estimates. On artificial tasks with different lengths of reward delays, we show that RUDDER is exponentially faster than TD, MC, and MC Tree Search (MCTS). RUDDER outperforms rainbow, A3C, DDQN, Distributional DQN, Dueling DDQN, Noisy DQN, and Prioritized DDQN on the delayed reward Atari game Venture in only a fraction of the learning time. RUDDER considerably improves the state-of-the-art on the delayed reward Atari game Bowling in much less learning time. Source code is available at https://github.com/ml-jku/baselines-rudder, with demonstration videos at https://goo.gl/EQerZV.

##### Abstract (translated by Google)
我们提出了一种新的强化学习方法，用于有延迟奖励的有限马尔可夫决策过程（MDPs）。在这项工作中，时间差（TD）估计的偏差被证明在延迟步骤的数量中仅被指数缓慢地校正。此外，蒙特卡洛（MC）估计的方差被证明可以增加其他估计的方差，其中的数量可以延迟步骤的数量呈指数增长。我们引入RUDDER，一种返回分解方法，它创建一个与原始MDP具有相同最优策略的新MDP，但具有大大减少延迟的重新分配奖励。如果回报分解是最优的，那么新的MDP没有延迟奖励，并且TD估计没有偏差。在这种情况下，奖励跟踪Q值，以便将来的预期回报始终为零。我们通过实验证实了我们对TD和MC估计的偏差和方差的理论结果。在具有不同长度的奖励延迟的人工任务中，我们显示RUDDER比TD，MC和MC树搜索（MCTS）指数地更快。只有一小部分学习时间，RUDDER的表现优于彩虹，A3C，DDQN，分布式DQN，决斗DDQN，噪声DQN和优先DDQN，延迟奖励Atari游戏风险投资。 RUDDER极大地提高了延迟奖励Atari游戏保龄球的最新技术水平，而且学习时间更少。源代码可在https://github.com/ml-jku/baselines-rudder获得，演示视频请https://goo.gl/EQerZV。

##### URL
[http://arxiv.org/abs/1806.07857](http://arxiv.org/abs/1806.07857)

##### PDF
[http://arxiv.org/pdf/1806.07857](http://arxiv.org/pdf/1806.07857)

