---
layout: post
title: "Reactive Reinforcement Learning in Asynchronous Environments"
date: 2018-02-16 21:55:01
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Relation
author: Jaden B. Travnik, Kory W. Mathewson, Richard S. Sutton, Patrick M. Pilarski
mathjax: true
---

* content
{:toc}

##### Abstract
The relationship between a reinforcement learning (RL) agent and an asynchronous environment is often ignored. Frequently used models of the interaction between an agent and its environment, such as Markov Decision Processes (MDP) or Semi-Markov Decision Processes (SMDP), do not capture the fact that, in an asynchronous environment, the state of the environment may change during computation performed by the agent. In an asynchronous environment, minimizing reaction time---the time it takes for an agent to react to an observation---also minimizes the time in which the state of the environment may change following observation. In many environments, the reaction time of an agent directly impacts task performance by permitting the environment to transition into either an undesirable terminal state or a state where performing the chosen action is inappropriate. We propose a class of reactive reinforcement learning algorithms that address this problem of asynchronous environments by immediately acting after observing new state information. We compare a reactive SARSA learning algorithm with the conventional SARSA learning algorithm on two asynchronous robotic tasks (emergency stopping and impact prevention), and show that the reactive RL algorithm reduces the reaction time of the agent by approximately the duration of the algorithm's learning update. This new class of reactive algorithms may facilitate safer control and faster decision making without any change to standard learning guarantees.

##### Abstract (translated by Google)
强化学习（RL）代理和异步环境之间的关系常常被忽略。代理与其环境之间交互的经常使用的模型（如马尔可夫决策过程（MDP）或半马尔可夫决策过程（SMDP））没有捕获这样一个事实，即在异步环境中，环境状态可能会发生变化在代理执行计算期间。在异步环境中，最小化反应时间---代理对观察作出反应所用的时间---也可以最大限度地减少观察后环境状态可能发生变化的时间。在许多环境中，代理人的反应时间通过允许环境转变为不理想的终端状态或执行所选择的行为不恰当的状态而直接影响任务执行。我们提出了一类反应性强化学习算法，通过在观察新的状态信息后立即采取行动来解决异步环境的问题。我们将反应性SARSA学习算法与传统SARSA学习算法在两个异步机器人任务（紧急停止和影响预防）之间进行比较，并且显示反应式RL算法大约缩短了算法的学习更新持续时间。这种新型的反应式算法可以促进更安全的控制和更快的决策制定，而不会对标准学习保证做任何改变。

##### URL
[http://arxiv.org/abs/1802.06139](http://arxiv.org/abs/1802.06139)

##### PDF
[http://arxiv.org/pdf/1802.06139](http://arxiv.org/pdf/1802.06139)

