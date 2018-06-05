---
layout: post
title: "Automatic Goal Generation for Reinforcement Learning Agents"
date: 2018-06-04 07:43:29
categories: arXiv_AI
tags: arXiv_AI Adversarial Sparse Knowledge Reinforcement_Learning
author: David Held, Xinyang Geng, Carlos Florensa, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning is a powerful technique to train an agent to perform a task. However, an agent that is trained using reinforcement learning is only capable of achieving the single task that is specified via its reward function. Such an approach does not scale well to settings in which an agent needs to perform a diverse set of tasks, such as navigating to varying positions in a room or moving objects to varying locations. Instead, we propose a method that allows an agent to automatically discover the range of tasks that it is capable of performing. We use a generator network to propose tasks for the agent to try to achieve, specified as goal states. The generator network is optimized using adversarial training to produce tasks that are always at the appropriate level of difficulty for the agent. Our method thus automatically produces a curriculum of tasks for the agent to learn. We show that, by using this framework, an agent can efficiently and automatically learn to perform a wide set of tasks without requiring any prior knowledge of its environment. Our method can also learn to achieve tasks with sparse rewards, which traditionally pose significant challenges.

##### Abstract (translated by Google)
强化学习是训练代理人执行任务的强大技术。但是，使用强化学习进行训练的代理只能实现通过奖励功能指定的单一任务。这种方法不能很好地适应于代理需要执行各种任务的设置，例如导航到房间中的不同位置或将对象移动到不同位置。相反，我们提出了一种允许代理自动发现其能够执行的任务范围的方法。我们使用生成器网络为代理人提出要尝试实现的任务，并将其指定为目标状态。生成器网络使用对抗训练进行优化，以产生始终处于适合代理程度难度的任务。因此，我们的方法自动生成一个代理人学习任务的课程表。我们证明，通过使用这个框架，代理可以高效地自动学习执行一系列广泛的任务，而无需事先了解其环境。我们的方法也可以通过稀疏奖励来学习完成任务，这通常会带来重大挑战。

##### URL
[http://arxiv.org/abs/1705.06366](http://arxiv.org/abs/1705.06366)

##### PDF
[http://arxiv.org/pdf/1705.06366](http://arxiv.org/pdf/1705.06366)

