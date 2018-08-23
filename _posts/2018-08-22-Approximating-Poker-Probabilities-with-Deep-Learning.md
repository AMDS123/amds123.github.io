---
layout: post
title: "Approximating Poker Probabilities with Deep Learning"
date: 2018-08-22 05:14:41
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Brandon Da Silva
mathjax: true
---

* content
{:toc}

##### Abstract
Many poker systems, whether created with heuristics or machine learning, rely on the probability of winning as a key input. However calculating the precise probability using combinatorics is an intractable problem, so instead we approximate it. Monte Carlo simulation is an effective technique that can be used to approximate the probability that a player will win and/or tie a hand. However, without the use of a memory-intensive lookup table or a supercomputer, it becomes infeasible to run millions of times when training an agent with self-play. To combat the space-time tradeoff, we use deep learning to approximate the probabilities obtained from the Monte Carlo simulation with high accuracy. The learned model proves to be a lightweight alternative to Monte Carlo simulation, which ultimately allows us to use the probabilities as inputs during self-play efficiently. The source code and stored neural network can be found at https://github.com/brandinho/Poker-Probability-Approximation.

##### Abstract (translated by Google)
许多扑克系统，无论是通过启发式还是机器学习创建的，都依赖于获胜的概率作为关键输入。然而，使用组合算法计算精确概率是一个棘手的问题，所以我们将其近似。蒙特卡罗模拟是一种有效的技术，可用于估计玩家赢得和/或打手的概率。但是，如果不使用内存密集型查找表或超级计算机，在训练具有自我播放功能的代理时运行数百万次变得不可行。为了对抗时空权衡，我们使用深度学习来高精度地逼近从蒙特卡罗模拟中获得的概率。学习的模型被证明是蒙特卡罗模拟的轻量级替代方案，最终允许我们在自我游戏期间有效地使用概率作为输入。源代码和存储的神经网络可以在https://github.com/brandinho/Poker-Probability-Approximation找到。

##### URL
[http://arxiv.org/abs/1808.07220](http://arxiv.org/abs/1808.07220)

##### PDF
[http://arxiv.org/pdf/1808.07220](http://arxiv.org/pdf/1808.07220)

