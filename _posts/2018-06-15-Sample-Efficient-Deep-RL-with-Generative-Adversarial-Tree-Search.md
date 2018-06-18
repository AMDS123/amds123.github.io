---
layout: post
title: "Sample-Efficient Deep RL with Generative Adversarial Tree Search"
date: 2018-06-15 01:35:03
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Reinforcement_Learning
author: Kamyar Azizzadenesheli, Brandon Yang, Weitang Liu, Emma Brunskill, Zachary C Lipton, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Generative Adversarial Tree Search (GATS), a sample-efficient Deep Reinforcement Learning (DRL) algorithm. While Monte Carlo Tree Search (MCTS) is known to be effective for search and planning in RL, it is often sample-inefficient and therefore expensive to apply in practice. In this work, we develop a Generative Adversarial Network (GAN) architecture to model an environment's dynamics and a predictor model for the reward function. We exploit collected data from interaction with the environment to learn these models, which we then use for model-based planning. During planning, we deploy a finite depth MCTS, using the learned model for tree search and a learned Q-value for the leaves, to find the best action. We theoretically show that GATS improves the bias-variance trade-off in value-based DRL. Moreover, we show that the generative model learns the model dynamics using orders of magnitude fewer samples than the Q-learner. In non-stationary settings where the environment model changes, we find the generative model adapts significantly faster than the Q-learner to the new environment.

##### Abstract (translated by Google)
我们提出了生成对抗树搜索（GATS），一种高效的深度增强学习（DRL）算法。虽然已知蒙特卡罗树搜索（MCTS）对于RL中的搜索和规划是有效的，但它往往是样本低效的，因此在实践中应用昂贵。在这项工作中，我们开发了一个生成敌对网络（GAN）架构来模拟环境的动态和奖励函数的预测模型。我们利用与环境交互中收集的数据来学习这些模型，然后将其用于基于模型的计划。在规划过程中，我们部署了一个有限深度的MCTS，使用学习模型进行树搜索，并使用叶学习的Q值来找到最佳的行为。我们从理论上表明，GATS改善了基于价值的DRL中的偏差 - 方差权衡。此外，我们显示生成模型使用比Q-学习者少的数量级的样本来学习模型动力学。在环境模型发生变化的非平稳环境中，我们发现生成模型比Q学习者适应新环境的速度要快得多。

##### URL
[http://arxiv.org/abs/1806.05780](http://arxiv.org/abs/1806.05780)

##### PDF
[http://arxiv.org/pdf/1806.05780](http://arxiv.org/pdf/1806.05780)

