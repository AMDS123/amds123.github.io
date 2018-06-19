---
layout: post
title: "Reinforcement Learning in Rich-Observation MDPs using Spectral Methods"
date: 2018-06-18 01:03:33
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Kamyar Azizzadenesheli, Alessandro Lazaric, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) in Markov decision processes (MDPs) with large state spaces is a challenging problem. The performance of standard RL algorithms degrades drastically with the dimensionality of state space. However, in practice, these large MDPs typically incorporate a latent or hidden low-dimensional structure. In this paper, we study the setting of rich-observation Markov decision processes (ROMDP), where there are a small number of hidden states which possess an injective mapping to the observation states. In other words, every observation state is generated through a single hidden state, and this mapping is unknown a priori. We introduce a spectral decomposition method that consistently learns this mapping, and more importantly, achieves it with low regret. The estimated mapping is integrated into an optimistic RL algorithm (UCRL), which operates on the estimated hidden space. We derive finite-time regret bounds for our algorithm with a weak dependence on the dimensionality of the observed space. In fact, our algorithm asymptotically achieves the same average regret as the oracle UCRL algorithm, which has the knowledge of the mapping from hidden to observed spaces. Thus, we derive an efficient spectral RL algorithm for ROMDPs.

##### Abstract (translated by Google)
具有大状态空间的马尔可夫决策过程（MDPs）中的强化学习（RL）是一个具有挑战性的问题。标准RL算法的性能随着状态空间的维度而急剧下降。但是，实际上，这些大型MDP通常包含潜在或隐藏的低维结构。在本文中，我们研究了富观测马尔可夫决策过程（ROMDP）的设置，其中有少量隐藏状态具有对观察状态的内射映射。换句话说，每个观察状态都是通过一个隐藏状态生成的，并且这个映射是先验未知的。我们引入了一种频谱分解方法，可以持续地学习这种映射，更重要的是，以低后悔的方式实现它。估计的映射被整合到乐观的RL算法（UCRL）中，该算法对估计的隐藏空间进行操作。我们推导出我们算法的有限时间后悔边界，对观测空间的维数依赖性很弱。实际上，我们的算法渐近地实现了与oracle UCRL算法相同的平均遗憾，该算法具有从隐藏映射到观察空间的映射知识。因此，我们为ROMDP推导了一种有效的频谱RL算法。

##### URL
[http://arxiv.org/abs/1611.03907](http://arxiv.org/abs/1611.03907)

##### PDF
[http://arxiv.org/pdf/1611.03907](http://arxiv.org/pdf/1611.03907)

