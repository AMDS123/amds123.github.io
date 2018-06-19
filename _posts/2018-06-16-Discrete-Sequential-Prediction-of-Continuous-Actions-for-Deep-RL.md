---
layout: post
title: "Discrete Sequential Prediction of Continuous Actions for Deep RL"
date: 2018-06-16 03:11:46
categories: arXiv_AI
tags: arXiv_AI Optimization Prediction
author: Luke Metz, Julian Ibarz, Navdeep Jaitly, James Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
It has long been assumed that high dimensional continuous control problems cannot be solved effectively by discretizing individual dimensions of the action space due to the exponentially large number of bins over which policies would have to be learned. In this paper, we draw inspiration from the recent success of sequence-to-sequence models for structured prediction problems to develop policies over discretized spaces. Central to this method is the realization that complex functions over high dimensional spaces can be modeled by neural networks that predict one dimension at a time. Specifically, we show how Q-values and policies over continuous spaces can be modeled using a next step prediction model over discretized dimensions. With this parameterization, it is possible to both leverage the compositional structure of action spaces during learning, as well as compute maxima over action spaces (approximately). On a simple example task we demonstrate empirically that our method can perform global search, which effectively gets around the local optimization issues that plague DDPG. We apply the technique to off-policy (Q-learning) methods and show that our method can achieve the state-of-the-art for off-policy methods on several continuous control tasks.

##### Abstract (translated by Google)
长期以来一直认为，高维连续控制问题不能通过离散化动作空间的各个维度来有效地解决，因为需要学习政策的指数大量的分箱。在本文中，我们从结构预测问题的序列到序列模型的最近成功中获得灵感，以开发离散化空间的策略。这种方法的核心是认识到高维空间上的复杂函数可以用一次预测一个维度的神经网络建模。具体而言，我们展示了连续空间上的Q值和策略如何使用离散化维度上的下一步预测模型进行建模。通过这种参数化，既可以在学习期间利用动作空间的组成结构，也可以在动作空间（近似）上计算最大值。在一个简单的示例任务中，我们凭经验证明我们的方法可以执行全局搜索，这有效地解决了困扰DDPG的本地优化问题。我们将该技术应用于关闭策略（Q-learning）方法，并表明我们的方法可以实现针对多个连续控制任务的关闭策略方法的最新技术。

##### URL
[http://arxiv.org/abs/1705.05035](http://arxiv.org/abs/1705.05035)

##### PDF
[http://arxiv.org/pdf/1705.05035](http://arxiv.org/pdf/1705.05035)

