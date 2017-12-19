---
layout: post
title: "Learning Deep Neural Network Policies with Continuous Memory States"
date: 2015-09-23 04:59:46
categories: arXiv_CV
tags: arXiv_CV Salient Optimization
author: Marvin Zhang, Zoe McCarthy, Chelsea Finn, Sergey Levine, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Policy learning for partially observed control tasks requires policies that can remember salient information from past observations. In this paper, we present a method for learning policies with internal memory for high-dimensional, continuous systems, such as robotic manipulators. Our approach consists of augmenting the state and action space of the system with continuous-valued memory states that the policy can read from and write to. Learning general-purpose policies with this type of memory representation directly is difficult, because the policy must automatically figure out the most salient information to memorize at each time step. We show that, by decomposing this policy search problem into a trajectory optimization phase and a supervised learning phase through a method called guided policy search, we can acquire policies with effective memorization and recall strategies. Intuitively, the trajectory optimization phase chooses the values of the memory states that will make it easier for the policy to produce the right action in future states, while the supervised learning phase encourages the policy to use memorization actions to produce those memory states. We evaluate our method on tasks involving continuous control in manipulation and navigation settings, and show that our method can learn complex policies that successfully complete a range of tasks that require memory.

##### Abstract (translated by Google)
对于部分观察到的控制任务的策略学习需要能够记住过去观察中的重要信息的策略。在本文中，我们提出了一个方法学习内存的高维，连续的系统，如机器人操作系统的内存。我们的方法包括增加系统的状态和动作空间，使用策略可以读取和写入的连续值内存状态。直接学习使用这种类型的存储器表示的通用策略是困难的，因为策略必须自动计算出每个时间步骤要记住的最显着的信息。我们表明，通过一种叫做引导式策略搜索的方法，将这个策略搜索问题分解成一个轨迹优化阶段和一个监督学习阶段，我们可以通过有效的记忆和回忆策略获得策略。直觉上，轨迹优化阶段选择记忆状态的值，这将使政策更容易在未来状态下产生正确的行为，而监督学习阶段则鼓励政策使用记忆行为来产生这些记忆状态。我们评估我们的方法涉及操纵和导航设置中的连续控制的任务，并显示我们的方法可以学习复杂的策略，成功完成一系列需要记忆的任务。

##### URL
[https://arxiv.org/abs/1507.01273](https://arxiv.org/abs/1507.01273)

##### PDF
[https://arxiv.org/pdf/1507.01273](https://arxiv.org/pdf/1507.01273)

