---
layout: post
title: "Variance Reduction in Monte Carlo Counterfactual Regret Minimization for Extensive Form Games using Baselines"
date: 2018-09-09 23:03:54
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Martin Schmid, Neil Burch, Marc Lanctot, Matej Moravcik, Rudolf Kadlec, Michael Bowling
mathjax: true
---

* content
{:toc}

##### Abstract
Learning strategies for imperfect information games from samples of interaction is a challenging problem. A common method for this setting, Monte Carlo Counterfactual Regret Minimization (MCCFR), can have slow long-term convergence rates due to high variance. In this paper, we introduce a variance reduction technique (VR-MCCFR) that applies to any sampling variant of MCCFR. Using this technique, per-iteration estimated values and updates are reformulated as a function of sampled values and state-action baselines, similar to their use in policy gradient reinforcement learning. The new formulation allows estimates to be bootstrapped from other estimates within the same episode, propagating the benefits of baselines along the sampled trajectory; the estimates remain unbiased even when bootstrapping from other estimates. Finally, we show that given a perfect baseline, the variance of the value estimates can be reduced to zero. Experimental evaluation shows that VR-MCCFR brings an order of magnitude speedup, while the empirical variance decreases by three orders of magnitude. The decreased variance allows for the first time CFR+ to be used with sampling, increasing the speedup to two orders of magnitude.

##### Abstract (translated by Google)
从交互样本中学习不完美信息游戏的策略是一个具有挑战性的问题。这种设置的常用方法蒙特卡罗反事实后遗症最小化（MCCFR）由于高方差而可能具有缓慢的长期收敛速度。在本文中，我们引入了适用于MCCFR的任何采样变体的方差减少技术（VR-MCCFR）。使用这种技术，每次迭代估计值和更新被重新制定为采样值和状态 - 行动基线的函数，类似于它们在政策梯度强化学习中的使用。新的公式允许从同一集中的其他估计值中引导估计值，沿着采样轨迹传播基线的好处;即使从其他估算中引导，估计仍然是无偏见的。最后，我们证明给定一个完美的基线，值估计的方差可以减少到零。实验评估表明，VR-MCCFR带来了一个数量级的加速，而经验方差减少了三个数量级。减小的方差允许CFR +第一次与采样一起使用，从而将加速增加到两个数量级。

##### URL
[http://arxiv.org/abs/1809.03057](http://arxiv.org/abs/1809.03057)

##### PDF
[http://arxiv.org/pdf/1809.03057](http://arxiv.org/pdf/1809.03057)

