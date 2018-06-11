---
layout: post
title: "The Uncertainty Bellman Equation and Exploration"
date: 2018-06-08 11:47:43
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Brendan O&#x27;Donoghue, Ian Osband, Remi Munos, Volodymyr Mnih
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the exploration/exploitation problem in reinforcement learning. For exploitation, it is well known that the Bellman equation connects the value at any time-step to the expected value at subsequent time-steps. In this paper we consider a similar \textit{uncertainty} Bellman equation (UBE), which connects the uncertainty at any time-step to the expected uncertainties at subsequent time-steps, thereby extending the potential exploratory benefit of a policy beyond individual time-steps. We prove that the unique fixed point of the UBE yields an upper bound on the variance of the posterior distribution of the Q-values induced by any policy. This bound can be much tighter than traditional count-based bonuses that compound standard deviation rather than variance. Importantly, and unlike several existing approaches to optimism, this method scales naturally to large systems with complex generalization. Substituting our UBE-exploration strategy for $\epsilon$-greedy improves DQN performance on 51 out of 57 games in the Atari suite.

##### Abstract (translated by Google)
我们考虑强化学习中的探索/开发问题。为了开发，众所周知，Bellman公式将任何时间步的值与后续时间步的预期值相连接。在本文中，我们考虑一个类似的\ textit {不确定性}贝尔曼方程（UBE），它将任何时间步长的不确定性与后续时间步长的预期不确定性联系起来，脚步。我们证明了UBE的唯一不动点产生了任何政策引发的Q值后验分布方差的上限。这个界限可以比传统的基于计数的奖金更加紧密，这个奖金是标准差而不是方差。重要的是，与现有的几种乐观方法不同，这种方法自然地适用于具有复杂泛化的大型系统。将我们的UBE探索策略替换为$ \ epsilon $ -greedy，可以提高Atari套件中57个游戏中51个的DQN性能。

##### URL
[http://arxiv.org/abs/1709.05380](http://arxiv.org/abs/1709.05380)

##### PDF
[http://arxiv.org/pdf/1709.05380](http://arxiv.org/pdf/1709.05380)

