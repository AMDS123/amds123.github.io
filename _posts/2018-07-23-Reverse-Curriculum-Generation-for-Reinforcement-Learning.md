---
layout: post
title: "Reverse Curriculum Generation for Reinforcement Learning"
date: 2018-07-23 10:10:17
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Reinforcement_Learning
author: Carlos Florensa, David Held, Markus Wulfmeier, Michael Zhang, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Many relevant tasks require an agent to reach a certain state, or to manipulate objects into a desired configuration. For example, we might want a robot to align and assemble a gear onto an axle or insert and turn a key in a lock. These goal-oriented tasks present a considerable challenge for reinforcement learning, since their natural reward function is sparse and prohibitive amounts of exploration are required to reach the goal and receive some learning signal. Past approaches tackle these problems by exploiting expert demonstrations or by manually designing a task-specific reward shaping function to guide the learning agent. Instead, we propose a method to learn these tasks without requiring any prior knowledge other than obtaining a single state in which the task is achieved. The robot is trained in reverse, gradually learning to reach the goal from a set of start states increasingly far from the goal. Our method automatically generates a curriculum of start states that adapts to the agent's performance, leading to efficient training on goal-oriented tasks. We demonstrate our approach on difficult simulated navigation and fine-grained manipulation problems, not solvable by state-of-the-art reinforcement learning methods.

##### Abstract (translated by Google)
许多相关任务要求代理达到某个状态，或将对象操作为所需的配置。例如，我们可能希望机器人将齿轮对准并组装到轴或插入件上并将钥匙锁定在锁中。这些面向目标的任务对强化学习提出了相当大的挑战，因为它们的自然奖励功能很少，并且需要过多的探索才能达到目标并接收一些学习信号。过去的方法通过利用专家演示或通过手动设计任务特定的奖励整形功能来指导学习代理来解决这些问题。相反，我们提出了一种方法来学习这些任务，而不需要任何先验知识，除了获得实现任务的单一状态。机器人被反向训练，逐渐学习从远离目标的一组起始状态到达目标。我们的方法自动生成适应代理性能的开始状态课程，从而对面向目标的任务进行有效的培训。我们展示了我们在困难的模拟导航和细粒度操作问题上的方法，而不是通过最先进的强化学习方法解决。

##### URL
[http://arxiv.org/abs/1707.05300](http://arxiv.org/abs/1707.05300)

##### PDF
[http://arxiv.org/pdf/1707.05300](http://arxiv.org/pdf/1707.05300)

