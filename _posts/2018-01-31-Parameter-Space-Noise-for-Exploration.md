---
layout: post
title: "Parameter Space Noise for Exploration"
date: 2018-01-31 09:05:10
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Matthias Plappert, Rein Houthooft, Prafulla Dhariwal, Szymon Sidor, Richard Y. Chen, Xi Chen, Tamim Asfour, Pieter Abbeel, Marcin Andrychowicz
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) methods generally engage in exploratory behavior through noise injection in the action space. An alternative is to add noise directly to the agent's parameters, which can lead to more consistent exploration and a richer set of behaviors. Methods such as evolutionary strategies use parameter perturbations, but discard all temporal structure in the process and require significantly more samples. Combining parameter noise with traditional RL methods allows to combine the best of both worlds. We demonstrate that both off- and on-policy methods benefit from this approach through experimental comparison of DQN, DDPG, and TRPO on high-dimensional discrete action environments as well as continuous control tasks. Our results show that RL with parameter noise learns more efficiently than traditional RL with action space noise and evolutionary strategies individually.

##### Abstract (translated by Google)
深度强化学习（RL）方法通常通过在动作空间中的噪声注入来进行探索行为。另一种方法是将噪音直接添加到代理的参数中，这可以导致更一致的探索和更丰富的行为。进化策略等方法使用参数扰动，但丢弃过程中的所有时间结构，并且需要更多的样本。将参数噪声与传统的RL方法相结合，可以结合两全其美。我们证明，通过DQN，DDPG和TRPO在高维离散行动环境以及持续控制任务上的实验比较，离线和在线策略方法都从这种方法中获益。我们的研究结果表明，具有参数噪声的RL比单独的行为空间噪声和进化策略更有效地学习传统的RL。

##### URL
[http://arxiv.org/abs/1706.01905](http://arxiv.org/abs/1706.01905)

##### PDF
[http://arxiv.org/pdf/1706.01905](http://arxiv.org/pdf/1706.01905)

