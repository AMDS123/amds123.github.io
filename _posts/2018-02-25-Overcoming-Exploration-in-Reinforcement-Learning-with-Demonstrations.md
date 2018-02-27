---
layout: post
title: "Overcoming Exploration in Reinforcement Learning with Demonstrations"
date: 2018-02-25 07:48:19
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Ashvin Nair, Bob McGrew, Marcin Andrychowicz, Wojciech Zaremba, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Exploration in environments with sparse rewards has been a persistent problem in reinforcement learning (RL). Many tasks are natural to specify with a sparse reward, and manually shaping a reward function can result in suboptimal performance. However, finding a non-zero reward is exponentially more difficult with increasing task horizon or action dimensionality. This puts many real-world tasks out of practical reach of RL methods. In this work, we use demonstrations to overcome the exploration problem and successfully learn to perform long-horizon, multi-step robotics tasks with continuous control such as stacking blocks with a robot arm. Our method, which builds on top of Deep Deterministic Policy Gradients and Hindsight Experience Replay, provides an order of magnitude of speedup over RL on simulated robotics tasks. It is simple to implement and makes only the additional assumption that we can collect a small set of demonstrations. Furthermore, our method is able to solve tasks not solvable by either RL or behavior cloning alone, and often ends up outperforming the demonstrator policy.

##### Abstract (translated by Google)
在奖励稀少的环境中进行探索一直是强化学习（RL）中的一个长期问题。许多任务很自然地用一个稀疏奖励来指定，而手动形成一个奖励函数可能会导致性能不理想。然而，随着任务范围或行动维度的增加，寻找非零奖励的难度将呈指数级增长。这使得许多现实世界的任务超出了RL方法的实际范围。在这项工作中，我们使用演示来克服探索问题，并成功地学习执行具有连续控制的长时间，多步骤的机器人任务，例如带有机器人手臂的积木。我们的方法建立在深度决定性策略梯度和事后体验回放的基础之上，在模拟机器人任务上提供了超过RL的加速量级。实施起来很简单，只做了一个额外的假设，我们可以收集一小组示范。此外，我们的方法能够解决无法通过RL或行为克隆单独解决的任务，并且往往最终超出示威者的政策。

##### URL
[http://arxiv.org/abs/1709.10089](http://arxiv.org/abs/1709.10089)

##### PDF
[http://arxiv.org/pdf/1709.10089](http://arxiv.org/pdf/1709.10089)

