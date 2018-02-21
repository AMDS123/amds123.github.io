---
layout: post
title: "Meta-Reinforcement Learning of Structured Exploration Strategies"
date: 2018-02-20 18:40:57
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Abhishek Gupta, Russell Mendonca, YuXuan Liu, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Exploration is a fundamental challenge in reinforcement learning (RL). Many of the current exploration methods for deep RL use task-agnostic objectives, such as information gain or bonuses based on state visitation. However, many practical applications of RL involve learning more than a single task, and prior tasks can be used to inform how exploration should be performed in new tasks. In this work, we explore how prior tasks can inform an agent about how to explore effectively in new situations. We introduce a novel gradient-based fast adaptation algorithm -- model agnostic exploration with structured noise (MAESN) -- to learn exploration strategies from prior experience. The prior experience is used both to initialize a policy and to acquire a latent exploration space that can inject structured stochasticity into a policy, producing exploration strategies that are informed by prior knowledge and are more effective than random action-space noise. We show that MAESN is more effective at learning exploration strategies when compared to prior meta-RL methods, RL without learned exploration strategies, and task-agnostic exploration methods. We evaluate our method on a variety of simulated tasks: locomotion with a wheeled robot, locomotion with a quadrupedal walker, and object manipulation.

##### Abstract (translated by Google)
探索是强化学习（RL）的基本挑战。许多目前深度RL的探索方法使用与任务无关的目标，例如信息获取或基于国家访问的奖金。然而，RL的许多实际应用涉及不止一项任务的学习，并且先前的任务可用于告知如何在新任务中执行探索。在这项工作中，我们将探索先前的任务如何能够告诉代理人如何在新情况下有效地进行探索。我们引入了一种新颖的基于梯度的快速自适应算法 - 结构噪声模型不可知探索（MAESN） - 从以前的经验中学习探索策略。先前的经验既用于初始化策略，也用于获取潜在的探索空间，可以将结构化随机性注入策略中，产生以先验知识为依据并且比随机行为空间噪声更有效的探索策略。我们证明MAESN在学习探索策略时比以前的meta-RL方法，没有学习探索策略的RL，以及与任务无关的探索方法更有效。我们在各种模拟任务中评估我们的方法：使用轮式机器人进行运动，使用四足步行机器人进行运动以及对象操纵。

##### URL
[http://arxiv.org/abs/1802.07245](http://arxiv.org/abs/1802.07245)

##### PDF
[http://arxiv.org/pdf/1802.07245](http://arxiv.org/pdf/1802.07245)

