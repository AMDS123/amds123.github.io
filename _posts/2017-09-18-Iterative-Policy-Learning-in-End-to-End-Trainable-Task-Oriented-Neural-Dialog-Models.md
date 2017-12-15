---
layout: post
title: "Iterative Policy Learning in End-to-End Trainable Task-Oriented Neural Dialog Models"
date: 2017-09-18 19:45:51
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Optimization
author: Bing Liu, Ian Lane
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a deep reinforcement learning (RL) framework for iterative dialog policy optimization in end-to-end task-oriented dialog systems. Popular approaches in learning dialog policy with RL include letting a dialog agent to learn against a user simulator. Building a reliable user simulator, however, is not trivial, often as difficult as building a good dialog agent. We address this challenge by jointly optimizing the dialog agent and the user simulator with deep RL by simulating dialogs between the two agents. We first bootstrap a basic dialog agent and a basic user simulator by learning directly from dialog corpora with supervised training. We then improve them further by letting the two agents to conduct task-oriented dialogs and iteratively optimizing their policies with deep RL. Both the dialog agent and the user simulator are designed with neural network models that can be trained end-to-end. Our experiment results show that the proposed method leads to promising improvements on task success rate and total task reward comparing to supervised training and single-agent RL training baseline models.

##### Abstract (translated by Google)
在本文中，我们提出了一个深入的强化学习（RL）框架，用于面向端到端任务的对话系统中的迭代对话策略优化。与RL学习对话策略的流行方法包括让对话代理学习用户模拟器。然而，建立一个可靠的用户模拟器并不是微不足道的，通常和建立一个好的对话代理一样困难。我们通过模拟两个代理之间的对话来联合优化对话代理和具有深度RL的用户模拟器来解决这个挑战。我们首先引导一个基本的对话代理和一个基本的用户模拟器，通过对话语料库的直接学习和监督训练。然后，我们进一步改进它们，让两个代理商进行面向任务的对话，并用深度RL反复优化他们的政策。对话代理和用户模拟器都是用可以进行端到端培训的神经网络模型来设计的。实验结果表明，与监督训练和单Agent RL训练基线模型相比，该方法在任务成功率和总任务奖励方面取得了较好的效果。

##### URL
[https://arxiv.org/abs/1709.06136](https://arxiv.org/abs/1709.06136)

##### PDF
[https://arxiv.org/pdf/1709.06136](https://arxiv.org/pdf/1709.06136)

