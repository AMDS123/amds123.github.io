---
layout: post
title: "Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor"
date: 2018-01-04 09:50:50
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tuomas Haarnoja, Aurick Zhou, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free deep reinforcement learning (RL) algorithms have been demonstrated on a range of challenging decision making and control tasks. However, these methods typically suffer from two major challenges: very high sample complexity and brittle convergence properties, which necessitate meticulous hyperparameter tuning. Both of these challenges severely limit the applicability of such methods to complex, real-world domains. In this paper, we propose soft actor-critic, an off-policy actor-critic deep RL algorithm based on the maximum entropy reinforcement learning framework. In this framework, the actor aims to maximize expected reward while also maximizing entropy - that is, succeed at the task while acting as randomly as possible. Prior deep RL methods based on this framework have been formulated as Q-learning methods. By combining off-policy updates with a stable stochastic actor-critic formulation, our method achieves state-of-the-art performance on a range of continuous control benchmark tasks, outperforming prior on-policy and off-policy methods. Furthermore, we demonstrate that, in contrast to other off-policy algorithms, our approach is very stable, achieving very similar performance across different random seeds.

##### Abstract (translated by Google)
无模型深度强化学习（RL）算法已经在一系列具有挑战性的决策和控制任务中得到了展示。然而，这些方法通常面临两大挑战：非常高的样本复杂性和脆弱的收敛特性，这需要细致的超参数调整。这些挑战都严重限制了这些方法适用于复杂的现实世界的领域。本文提出了一种基于最大熵强化学习框架的软评论者 - 一种不合理的演员 - 评论者深度RL算法。在这个框架中，行为者的目的是最大化期望的回报，同时也使熵最大化，也就是在尽可能随机的情况下成功完成任务。基于此框架的先前的深度RL方法已经被制定为Q学习方法。我们的方法通过将关闭策略更新与稳定的随机行动者 - 评论者表述相结合，在一系列连续控制基准任务上实现了最先进的性能，超越了之前的政策和非政策方法。此外，我们证明，与其他关闭策略算法相比，我们的方法非常稳定，在不同的随机种子中实现了非常相似的性能。

##### URL
[http://arxiv.org/abs/1801.01290](http://arxiv.org/abs/1801.01290)

##### PDF
[http://arxiv.org/pdf/1801.01290](http://arxiv.org/pdf/1801.01290)

