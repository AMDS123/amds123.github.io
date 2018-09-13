---
layout: post
title: "Safe Exploration in Markov Decision Processes with Time-Variant Safety using Spatio-Temporal Gaussian Process"
date: 2018-09-12 02:43:19
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Akifumi Wachi, Hiroshi Kajino, Asim Munawar
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world applications (e.g., planetary exploration, robot navigation), an autonomous agent must be able to explore a space with guaranteed safety. Most safe exploration algorithms in the field of reinforcement learning and robotics have been based on the assumption that the safety features are a priori known and time-invariant. This paper presents a learning algorithm called ST-SafeMDP for exploring Markov decision processes (MDPs) that is based on the assumption that the safety features are a priori unknown and time-variant. In this setting, the agent explores MDPs while constraining the probability of entering unsafe states defined by a safety function being below a threshold. The unknown and time-variant safety values are modeled using a spatio-temporal Gaussian process. However, there remains an issue that an agent may have no viable action in a shrinking true safe space. To address this issue, we formulate a problem maximizing the cumulative number of safe states in the worst case scenario with respect to future observations. The effectiveness of this approach was demonstrated in two simulation settings, including one using real lunar terrain data.

##### Abstract (translated by Google)
在许多现实世界的应用中（例如，行星探测，机器人导航），自主代理必须能够在保证安全的情况下探索空间。在强化学习和机器人领域中最安全的探索算法基于这样的假设：安全特征是先验已知的并且是时不变的。本文提出了一种名为ST-SafeMDP的学习算法，用于探索马尔可夫决策过程（MDP），该算法基于安全特征是先验未知和时变的假设。在此设置中，代理会探索MDP，同时限制进入由安全功能定义的不安全状态的概率低于阈值。使用时空高斯过程对未知和时变安全值进行建模。然而，仍存在一个问题，即代理人可能在缩小的真正安全空间中没有可行的行动。为了解决这个问题，我们制定了一个问题，在最坏的情况下，针对未来的观察，最大化安全状态的累积数量。这种方法的有效性在两个模拟设置中得到证明，其中一个使用真实的月球地形数据。

##### URL
[http://arxiv.org/abs/1809.04232](http://arxiv.org/abs/1809.04232)

##### PDF
[http://arxiv.org/pdf/1809.04232](http://arxiv.org/pdf/1809.04232)

