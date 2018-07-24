---
layout: post
title: "Learning to Play Pong using Policy Gradient Learning"
date: 2018-07-23 06:55:23
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Somnuk Phon-Amnuaisuk
mathjax: true
---

* content
{:toc}

##### Abstract
Activities in reinforcement learning (RL) revolve around learning the Markov decision process (MDP) model, in particular, the following parameters: state values, V; state-action values, Q; and policy, pi. These parameters are commonly implemented as an array. Scaling up the problem means scaling up the size of the array and this will quickly lead to a computational bottleneck. To get around this, the RL problem is commonly formulated to learn a specific task using hand-crafted input features to curb the size of the array. In this report, we discuss an alternative end-to-end Deep Reinforcement Learning (DRL) approach where the DRL attempts to learn general task representations which in our context refers to learning to play the Pong game from a sequence of screen snapshots without game-specific hand-crafted features. We apply artificial neural networks (ANN) to approximate a policy of the RL model. The policy network, via Policy Gradients (PG) method, learns to play the Pong game from a sequence of frames without any extra semantics apart from the pixel information and the score. In contrast to the traditional tabular RL approach where the contents in the array have clear interpretations such as V or Q, the interpretation of knowledge content from the weights of the policy network is more illusive. In this work, we experiment with various Deep ANN architectures i.e., Feed forward ANN (FFNN), Convolution ANN (CNN) and Asynchronous Advantage Actor-Critic (A3C). We also examine the activation of hidden nodes and the weights between the input and the hidden layers, before and after the DRL has successfully learnt to play the Pong game. Insights into the internal learning mechanisms and future research directions are then discussed.

##### Abstract (translated by Google)
强化学习（RL）中的活动围绕学习马尔可夫决策过程（MDP）模型，特别是以下参数：状态值，V;国家行动价值，Q;和政策，pi。这些参数通常实现为数组。扩大问题意味着扩大阵列的大小，这将很快导致计算瓶颈。为了解决这个问题，RL问题通常用于学习特定任务，使用手工制作的输入功能来控制阵列的大小。在本报告中，我们讨论了另一种端到端深度强化学习（DRL）方法，其中DRL尝试学习一般任务表示，在我们的上下文中指的是学习从一系列屏幕快照中播放Pong游戏而无需游戏 - 具体的手工制作功能。我们应用人工神经网络（ANN）来近似RL模型的策略。策略网络通过Policy Gradients（PG）方法学习从帧序列中播放Pong游戏，除了像素信息和分数之外没有任何额外的语义。与传统的表格RL方法相比，其中阵列中的内容具有明确的解释，例如V或Q，从策略网络的权重解释知识内容更加虚幻。在这项工作中，我们尝试了各种Deep ANN架构，即前馈ANN（FFNN），卷积ANN（CNN）和Asynchronous Advantage Actor-Critic（A3C）。在DRL成功学习玩Pong游戏之前和之后，我们还会检查隐藏节点的激活以及输入和隐藏层之间的权重。然后讨论内部学习机制和未来研究方向的见解。

##### URL
[http://arxiv.org/abs/1807.08452](http://arxiv.org/abs/1807.08452)

##### PDF
[http://arxiv.org/pdf/1807.08452](http://arxiv.org/pdf/1807.08452)

