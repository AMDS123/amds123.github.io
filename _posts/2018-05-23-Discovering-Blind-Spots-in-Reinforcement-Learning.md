---
layout: post
title: "Discovering Blind Spots in Reinforcement Learning"
date: 2018-05-23 05:30:17
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ramya Ramakrishnan, Ece Kamar, Debadeepta Dey, Julie Shah, Eric Horvitz
mathjax: true
---

* content
{:toc}

##### Abstract
Agents trained in simulation may make errors in the real world due to mismatches between training and execution environments. These mistakes can be dangerous and difficult to discover because the agent cannot predict them a priori. We propose using oracle feedback to learn a predictive model of these blind spots to reduce costly errors in real-world applications. We focus on blind spots in reinforcement learning (RL) that occur due to incomplete state representation: The agent does not have the appropriate features to represent the true state of the world and thus cannot distinguish among numerous states. We formalize the problem of discovering blind spots in RL as a noisy supervised learning problem with class imbalance. We learn models to predict blind spots in unseen regions of the state space by combining techniques for label aggregation, calibration, and supervised learning. The models take into consideration noise emerging from different forms of oracle feedback, including demonstrations and corrections. We evaluate our approach on two domains and show that it achieves higher predictive performance than baseline methods, and that the learned model can be used to selectively query an oracle at execution time to prevent errors. We also empirically analyze the biases of various feedback types and how they influence the discovery of blind spots.

##### Abstract (translated by Google)
由于训练和执行环境之间的不匹配，在模拟中训练的代理可能会在现实世界中造成错误。这些错误可能是危险的，很难发现，因为代理人无法预测它们。我们建议使用oracle反馈来学习这些盲点的预测模型，以减少实际应用程序中的代价高昂的错误。我们关注强化学习（RL）中由于状态表示不完全而出现的盲点：代理没有合适的特征来表示世界的真实状态，因此无法区分众多状态。我们将发现RL中盲点的问题形式化为带有阶级失衡的嘈杂的监督学习问题。通过结合标签聚合，校准和监督学习技术，我们学习了预测状态空间未知区域盲点的模型。这些模型考虑了来自不同形式的oracle反馈的噪声，包括示范和更正。我们在两个域上评估我们的方法，并证明它比基准方法具有更高的预测性能，并且可以使用学习模型在执行时有选择地查询oracle以防止错误。我们还通过实证分析了各种反馈类型的偏差以及它们如何影响盲点的发现。

##### URL
[http://arxiv.org/abs/1805.08966](http://arxiv.org/abs/1805.08966)

##### PDF
[http://arxiv.org/pdf/1805.08966](http://arxiv.org/pdf/1805.08966)

