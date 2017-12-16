---
layout: post
title: "Detecting Adversarial Attacks on Neural Network Policies with Visual Foresight"
date: 2017-10-02 17:56:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Reinforcement_Learning Prediction
author: Yen-Chen Lin, Ming-Yu Liu, Min Sun, Jia-Bin Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has shown promising results in learning control policies for complex sequential decision-making tasks. However, these neural network-based policies are known to be vulnerable to adversarial examples. This vulnerability poses a potentially serious threat to safety-critical systems such as autonomous vehicles. In this paper, we propose a defense mechanism to defend reinforcement learning agents from adversarial attacks by leveraging an action-conditioned frame prediction module. Our core idea is that the adversarial examples targeting at a neural network-based policy are not effective for the frame prediction model. By comparing the action distribution produced by a policy from processing the current observed frame to the action distribution produced by the same policy from processing the predicted frame from the action-conditioned frame prediction module, we can detect the presence of adversarial examples. Beyond detecting the presence of adversarial examples, our method allows the agent to continue performing the task using the predicted frame when the agent is under attack. We evaluate the performance of our algorithm using five games in Atari 2600. Our results demonstrate that the proposed defense mechanism achieves favorable performance against baseline algorithms in detecting adversarial examples and in earning rewards when the agents are under attack.

##### Abstract (translated by Google)
深度强化学习在复杂的顺序决策任务的学习控制策略方面表现出有希望的结果。然而，这些基于神经网络的政策已知容易受到敌对的例子。这个漏洞对诸如自动驾驶汽车等安全关键系统构成潜在的严重威胁。在本文中，我们提出了一个防御机制，通过利用行为条件框架预测模块来防御强化学习代理对抗攻击。我们的核心思想是针对基于神经网络策略的敌对案例对于帧预测模型是无效的。通过比较处理当前观察帧的策略产生的动作分布与处理来自动作条件帧预测模块的预测帧的同一策略产生的动作分布，我们可以检测敌对示例的存在。除了检测对抗性的例子之外，我们的方法允许代理在代理受到攻击时使用预测帧继续执行任务。我们使用Atari 2600中的五个游戏来评估我们的算法的性能。我们的结果表明，所提出的防御机制在基线算法中检测敌对的例子并且在代理受到攻击时获得奖励的情况下实现了有利的性能。

##### URL
[https://arxiv.org/abs/1710.00814](https://arxiv.org/abs/1710.00814)

##### PDF
[https://arxiv.org/pdf/1710.00814](https://arxiv.org/pdf/1710.00814)

