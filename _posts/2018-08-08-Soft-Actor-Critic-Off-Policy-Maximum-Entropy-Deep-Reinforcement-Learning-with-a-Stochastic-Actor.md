---
layout: post
title: "Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor"
date: 2018-08-08 21:27:08
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tuomas Haarnoja, Aurick Zhou, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free deep reinforcement learning (RL) algorithms have been demonstrated on a range of challenging decision making and control tasks. However, these methods typically suffer from two major challenges: very high sample complexity and brittle convergence properties, which necessitate meticulous hyperparameter tuning. Both of these challenges severely limit the applicability of such methods to complex, real-world domains. In this paper, we propose soft actor-critic, an off-policy actor-critic deep RL algorithm based on the maximum entropy reinforcement learning framework. In this framework, the actor aims to maximize expected reward while also maximizing entropy. That is, to succeed at the task while acting as randomly as possible. Prior deep RL methods based on this framework have been formulated as Q-learning methods. By combining off-policy updates with a stable stochastic actor-critic formulation, our method achieves state-of-the-art performance on a range of continuous control benchmark tasks, outperforming prior on-policy and off-policy methods. Furthermore, we demonstrate that, in contrast to other off-policy algorithms, our approach is very stable, achieving very similar performance across different random seeds.

##### Abstract (translated by Google)
无模型深度强化学习（RL）算法已经在一系列具有挑战性的决策制定和控制任务中得到证明。然而，这些方法通常遭受两个主要挑战：非常高的样品复杂性和脆弱的收敛性质，这需要细致的超参数调整。这两个挑战都严重限制了这些方法对复杂的现实领域的适用性。在本文中，我们提出了基于最大熵强化学习框架的软扮演者 - 批评者，一种非政策性的行为者 - 批评者深度RL算法。在这个框架中，演员的目标是最大化期望的奖励，同时也最大化熵。也就是说，在尽可能随机行动的同时成功完成任务。基于该框架的先前深度RL方法已被公式化为Q学习方法。通过将非政策更新与稳定的随机行为者 - 评论者表述相结合，我们的方法在一系列连续控制基准任务上实现了最先进的性能，优于先前的政策和非政策方法。此外，我们证明，与其他非策略算法相比，我们的方法非常稳定，在不同的随机种子上实现了非常相似的性能。

##### URL
[http://arxiv.org/abs/1801.01290](http://arxiv.org/abs/1801.01290)

##### PDF
[http://arxiv.org/pdf/1801.01290](http://arxiv.org/pdf/1801.01290)

