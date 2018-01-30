---
layout: post
title: "Playing FPS Games with Deep Reinforcement Learning"
date: 2018-01-29 15:13:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Guillaume Lample, Devendra Singh Chaplot
mathjax: true
---

* content
{:toc}

##### Abstract
Advances in deep reinforcement learning have allowed autonomous agents to perform well on Atari games, often outperforming humans, using only raw pixels to make their decisions. However, most of these games take place in 2D environments that are fully observable to the agent. In this paper, we present the first architecture to tackle 3D environments in first-person shooter games, that involve partially observable states. Typically, deep reinforcement learning methods only utilize visual input for training. We present a method to augment these models to exploit game feature information such as the presence of enemies or items, during the training phase. Our model is trained to simultaneously learn these features along with minimizing a Q-learning objective, which is shown to dramatically improve the training speed and performance of our agent. Our architecture is also modularized to allow different models to be independently trained for different phases of the game. We show that the proposed architecture substantially outperforms built-in AI agents of the game as well as humans in deathmatch scenarios.

##### Abstract (translated by Google)
深度强化学习的进展使得自治代理能够在Atari游戏上表现良好，经常表现优于人类，只使用原始像素做出决定。然而，这些游戏大部分发生在代理人完全可以观察的2D环境中。在本文中，我们提出了第一个架构来处理第一人称射击游戏中的3D环境，涉及部分可观察状态。通常，深度强化学习方法只能利用视觉输入来训练。我们提出了一种方法来增强这些模型，以在训练阶段利用游戏特征信息，例如敌人或物品的存在。我们的模型经过训练，可以同时学习这些特征，同时最大限度地减少Q学习目标，显着提高了代理的训练速度和性能。我们的架构也被模块化，以允许不同模型在游戏的不同阶段被独立训练。我们表明，建议的体系结构大大优于游戏中的内置AI代理以及死亡场景中的人类。

##### URL
[http://arxiv.org/abs/1609.05521](http://arxiv.org/abs/1609.05521)

##### PDF
[http://arxiv.org/pdf/1609.05521](http://arxiv.org/pdf/1609.05521)

