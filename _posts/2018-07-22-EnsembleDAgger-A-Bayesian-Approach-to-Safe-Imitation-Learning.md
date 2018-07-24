---
layout: post
title: "EnsembleDAgger: A Bayesian Approach to Safe Imitation Learning"
date: 2018-07-22 20:52:56
categories: arXiv_AI
tags: arXiv_AI
author: Kunal Menda, Katherine Driggs-Campbell, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
While imitation learning is often used in robotics, this approach often suffers from data mismatch and compounding errors. DAgger is an iterative algorithm that addresses these issues by aggregating training data from both the expert and novice policies, but does not consider the impact of safety. We present a probabilistic extension to DAgger, which attempts to quantify the confidence of the novice policy as a proxy for safety. Our method, EnsembleDAgger, approximates a GP using an ensemble of neural networks. Using the variance as a measure of confidence, we compute a decision rule that captures how much we doubt the novice, thus determining when it is safe to allow the novice to act. With this approach, we aim to maximize the novice's share of actions, while constraining the probability of failure. We demonstrate improved safety and learning performance compared to other DAgger variants and classic imitation learning on an inverted pendulum and in the MuJoCo HalfCheetah environment.

##### Abstract (translated by Google)
虽然模仿学习经常用于机器人技术，但这种方法通常会受到数据不匹配和复合错误的影响。 DAgger是一种迭代算法，通过汇总来自专家和新手政策的培训数据来解决这些问题，但不考虑安全的影响。我们提出了DAgger的概率扩展，它试图量化新手政策作为安全代理的信心。我们的方法EnsembleDAgger使用神经网络集合近似GP。使用方差作为置信度的度量，我们计算一个决策规则，捕获我们对新手的怀疑程度，从而确定允许新手行动的安全性。通过这种方法，我们的目标是最大化新手的行动份额，同时限制失败的可能性。与其他DAgger变体和倒立摆以及MuJoCo HalfCheetah环境中的经典模仿学习相比，我们展示了更高的安全性和学习性能。

##### URL
[http://arxiv.org/abs/1807.08364](http://arxiv.org/abs/1807.08364)

##### PDF
[http://arxiv.org/pdf/1807.08364](http://arxiv.org/pdf/1807.08364)

