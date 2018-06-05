---
layout: post
title: "Efficient Entropy for Policy Gradient with Multidimensional Action Space"
date: 2018-06-02 06:25:19
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning RNN
author: Yiming Zhang, Quan Ho Vuong, Kenny Song, Xiao-Yue Gong, Keith W. Ross
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep reinforcement learning has been shown to be adept at solving sequential decision processes with high-dimensional state spaces such as in the Atari games. Many reinforcement learning problems, however, involve high-dimensional discrete action spaces as well as high-dimensional state spaces. This paper considers entropy bonus, which is used to encourage exploration in policy gradient. In the case of high-dimensional action spaces, calculating the entropy and its gradient requires enumerating all the actions in the action space and running forward and backpropagation for each action, which may be computationally infeasible. We develop several novel unbiased estimators for the entropy bonus and its gradient. We apply these estimators to several models for the parameterized policies, including Independent Sampling, CommNet, Autoregressive with Modified MDP, and Autoregressive with LSTM. Finally, we test our algorithms on two environments: a multi-hunter multi-rabbit grid game and a multi-agent multi-arm bandit problem. The results show that our entropy estimators substantially improve performance with marginal additional computational cost.

##### Abstract (translated by Google)
近年来，深度强化学习已被证明擅长解决具有高维状态空间的顺序决策过程，如Atari游戏。然而，许多强化学习问题涉及高维离散作用空间以及高维状态空间。本文考虑了用于鼓励政策梯度探索的熵奖励。在高维动作空间的情况下，计算熵及其梯度需要列举动作空间中的所有动作，并对每个动作进行前向和后向传播，这在计算上可能是不可行的。我们为熵加及其梯度开发了几种新颖的无偏估计量。我们将这些估计器应用于参数化策略的多个模型，包括独立采样，CommNet，具有修改MDP的自回归和具有LSTM的自回归。最后，我们在两种环境下测试我们的算法：多猎人多兔子网格游戏和多代理多臂土匪问题。结果表明，我们的熵估计器在边际附加计算成本的情况下大大提高了性能。

##### URL
[http://arxiv.org/abs/1806.00589](http://arxiv.org/abs/1806.00589)

##### PDF
[http://arxiv.org/pdf/1806.00589](http://arxiv.org/pdf/1806.00589)

