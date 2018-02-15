---
layout: post
title: "Evolved Policy Gradients"
date: 2018-02-13 19:07:43
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Rein Houthooft, Richard Y. Chen, Phillip Isola, Bradly C. Stadie, Filip Wolski, Jonathan Ho, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a meta-learning approach for learning gradient-based reinforcement learning (RL) algorithms. The idea is to evolve a differentiable loss function, such that an agent, which optimizes its policy to minimize this loss, will achieve high rewards. The loss is parametrized via temporal convolutions over the agent's experience. Because this loss is highly flexible in its ability to take into account the agent's history, it enables fast task learning and eliminates the need for reward shaping at test time. Empirical results show that our evolved policy gradient algorithm achieves faster learning on several randomized environments compared to an off-the-shelf policy gradient method. Moreover, at test time, our learner optimizes only its learned loss function, and requires no explicit reward signal. In effect, the agent internalizes the reward structure, suggesting a direction toward agents that learn to solve new tasks simply from intrinsic motivation.

##### Abstract (translated by Google)
我们提出了一种用于学习基于梯度的强化学习（RL）算法的元学习方法。这个想法是发展一个可区分的损失函数，这样一个代理人，优化其政策，以尽量减少这种损失，将获得很高的回报。通过对代理人的经验进行时间卷积来对损失进行参数化。由于这种损失在考虑代理历史的能力方面非常灵活，因此可以快速进行任务学习，并且无需在测试时进行奖励整形。实证结果表明，与现成的策略梯度法相比，我们的演进策略梯度算法在几个随机环境中实现了更快的学习。而且，在测试时，我们的学习者只优化其学习的损失函数，并且不需要明确的奖励信号。实际上，代理人将奖励结构内在化，为代理人提供了一个方向，这些代理人通过内在动机学会解决新的任务。

##### URL
[http://arxiv.org/abs/1802.04821](http://arxiv.org/abs/1802.04821)

##### PDF
[http://arxiv.org/pdf/1802.04821](http://arxiv.org/pdf/1802.04821)

