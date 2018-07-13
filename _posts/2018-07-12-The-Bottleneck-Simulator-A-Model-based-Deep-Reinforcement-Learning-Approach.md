---
layout: post
title: "The Bottleneck Simulator: A Model-based Deep Reinforcement Learning Approach"
date: 2018-07-12 16:59:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Iulian Vlad Serban, Chinnadhurai Sankar, Michael Pieper, Joelle Pineau, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has recently shown many impressive successes. However, one major obstacle towards applying such methods to real-world problems is their lack of data-efficiency. To this end, we propose the Bottleneck Simulator: a model-based reinforcement learning method which combines a learned, factorized transition model of the environment with rollout simulations to learn an effective policy from few examples. The learned transition model employs an abstract, discrete (bottleneck) state, which increases sample efficiency by reducing the number of model parameters and by exploiting structural properties of the environment. We provide a mathematical analysis of the Bottleneck Simulator in terms of fixed points of the learned policy, which reveals how performance is affected by four distinct sources of error: an error related to the abstract space structure, an error related to the transition model estimation variance, an error related to the transition model estimation bias, and an error related to the transition model class bias. Finally, we evaluate the Bottleneck Simulator on two natural language processing tasks: a text adventure game and a real-world, complex dialogue response selection task. On both tasks, the Bottleneck Simulator yields excellent performance beating competing approaches.

##### Abstract (translated by Google)
深层强化学习最近取得了许多令人印象深刻的成功。然而，将这些方法应用于现实问题的一个主要障碍是缺乏数据效率。为此，我们提出了瓶颈模拟器：一种基于模型的强化学习方法，它将学习的，分解的环境转换模型与推出模拟相结合，从少数示例中学习有效的策略。学习的转换模型采用抽象的，离散的（瓶颈）状态，通过减少模型参数的数量和利用环境的结构特性来提高样本效率。我们根据学习策略的固定点提供了瓶颈模拟器的数学分析，揭示了四种不同的误差源如何影响性能：与抽象空间结构相关的误差，与过渡模型估计方差相关的误差，与转移模型估计偏差有关的误差，以及与转变模型类偏差有关的误差。最后，我们在两个自然语言处理任务上评估瓶颈模拟器：文本冒险游戏和现实世界的复杂对话响应选择任务。在这两项任务中，瓶颈模拟器在竞争方法方面表现出色。

##### URL
[http://arxiv.org/abs/1807.04723](http://arxiv.org/abs/1807.04723)

##### PDF
[http://arxiv.org/pdf/1807.04723](http://arxiv.org/pdf/1807.04723)

