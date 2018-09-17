---
layout: post
title: "Defensive Dropout for Hardening Deep Neural Networks under Adversarial Attacks"
date: 2018-09-13 20:26:32
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Siyue Wang, Xiao Wang, Pu Zhao, Wujie Wen, David Kaeli, Peter Chin, Xue Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are known vulnerable to adversarial attacks. That is, adversarial examples, obtained by adding delicately crafted distortions onto original legal inputs, can mislead a DNN to classify them as any target labels. This work provides a solution to hardening DNNs under adversarial attacks through defensive dropout. Besides using dropout during training for the best test accuracy, we propose to use dropout also at test time to achieve strong defense effects. We consider the problem of building robust DNNs as an attacker-defender two-player game, where the attacker and the defender know each others' strategies and try to optimize their own strategies towards an equilibrium. Based on the observations of the effect of test dropout rate on test accuracy and attack success rate, we propose a defensive dropout algorithm to determine an optimal test dropout rate given the neural network model and the attacker's strategy for generating adversarial examples.We also investigate the mechanism behind the outstanding defense effects achieved by the proposed defensive dropout. Comparing with stochastic activation pruning (SAP), another defense method through introducing randomness into the DNN model, we find that our defensive dropout achieves much larger variances of the gradients, which is the key for the improved defense effects (much lower attack success rate). For example, our defensive dropout can reduce the attack success rate from 100% to 13.89% under the currently strongest attack i.e., C&amp;W attack on MNIST dataset.

##### Abstract (translated by Google)
已知深度神经网络（DNN）容易受到对抗性攻击。也就是说，通过在原始法律输入上添加精心制作的扭曲获得的对抗性示例可能会误导DNN将其归类为任何目标标签。这项工作提供了一种解决方案，通过防御性辍学来加强对抗性攻击下的DNN。除了在训练期间使用辍学以获得最佳测试精度外，我们还建议在测试时使用辍学来实现强大的防御效果。我们将构建强大的DNN的问题视为攻击者 - 后卫双人游戏，其中攻击者和防御者了解彼此的策略并尝试优化他们自己的策略以实现均衡。基于对测试辍学率对测试精度和攻击成功率的影响的观察，我们提出了一种防御性辍学算法，以确定最佳测试辍学率，给出神经网络模型和攻击者生成对抗性示例的策略。我们还研究了提出的防御辍学所带来的杰出防御效应背后的机制。与随机激活修剪（SAP）相比，通过将随机性引入DNN模型的另一种防御方法，我们发现我们的防御性辍学实现了更大的梯度变化，这是提高防御效果的关键（低得多的攻击成功率） 。例如，我们的防御性辍学可以在当前最强的攻击下将攻击成功率从100％降低到13.89％，即对MNIST数据集的C＆amp; W攻击。

##### URL
[http://arxiv.org/abs/1809.05165](http://arxiv.org/abs/1809.05165)

##### PDF
[http://arxiv.org/pdf/1809.05165](http://arxiv.org/pdf/1809.05165)

