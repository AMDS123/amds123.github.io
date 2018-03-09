---
layout: post
title: "TreeQN and ATreeC: Differentiable Tree-Structured Models for Deep Reinforcement Learning"
date: 2018-03-08 17:30:48
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Gregory Farquhar, Tim Rockt&#xe4;schel, Maximilian Igl, Shimon Whiteson
mathjax: true
---

* content
{:toc}

##### Abstract
Combining deep model-free reinforcement learning with on-line planning is a promising approach to building on the successes of deep RL. On-line planning with look-ahead trees has proven successful in environments where transition models are known a priori. However, in complex environments where transition models need to be learned from data, the deficiencies of learned models have limited their utility for planning. To address these challenges, we propose TreeQN, a differentiable, recursive, tree-structured model that serves as a drop-in replacement for any value function network in deep RL with discrete actions. TreeQN dynamically constructs a tree by recursively applying a transition model in a learned abstract state space and then aggregating predicted rewards and state-values using a tree backup to estimate Q-values. We also propose ATreeC, an actor-critic variant that augments TreeQN with a softmax layer to form a stochastic policy network. Both approaches are trained end-to-end, such that the learned model is optimised for its actual use in the tree. We show that TreeQN and ATreeC outperform n-step DQN and A2C on a box-pushing task, as well as n-step DQN and value prediction networks (Oh et al. 2017) on multiple Atari games. Furthermore, we present ablation studies that demonstrate the effect of different auxiliary losses on learning transition models.

##### Abstract (translated by Google)
将深度无模型强化学习与在线计划相结合是建立在深度RL的成功基础上的有前途的方法。在预先知道转换模型的环境中，使用预见树进行在线规划已被证明是成功的。但是，在需要从数据中学习转换模型的复杂环境中，学习模型的缺陷限制了它们的计划效用。为了解决这些挑战，我们提出TreeQN，一种可微分的递归树型结构模型，可用作深层RL中任何有离散作用的有价值函数网络的直接替换。 TreeQN通过在学习的抽象状态空间中递归地应用转换模型，然后使用树备份来聚合预测的奖励和状态值以估计Q值来动态地构建树。我们还提出了ATreeC，这是一个演员评论者变体，它用一个softmax层增强TreeQN以形成一个随机策略网络。这两种方法都是端对端训练，这样学习的模型就会在树中实际使用时进行优化。我们证明TreeQN和AtreeC在多推理任务上的表现优于n步DQN和A2C，以及在多个Atari游戏上的n步DQN和价值预测网络（Oh et al。2017）。此外，我们目前的消融研究表明不同的辅助损失对学习转换模型的影响。

##### URL
[http://arxiv.org/abs/1710.11417](http://arxiv.org/abs/1710.11417)

##### PDF
[http://arxiv.org/pdf/1710.11417](http://arxiv.org/pdf/1710.11417)

