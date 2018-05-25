---
layout: post
title: "Meta-Gradient Reinforcement Learning"
date: 2018-05-24 17:45:11
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Zhongwen Xu, Hado van Hasselt, David Silver
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of reinforcement learning algorithms is to estimate and/or optimise the value function. However, unlike supervised learning, no teacher or oracle is available to provide the true value function. Instead, the majority of reinforcement learning algorithms estimate and/or optimise a proxy for the value function. This proxy is typically based on a sampled and bootstrapped approximation to the true value function, known as a return. The particular choice of return is one of the chief components determining the nature of the algorithm: the rate at which future rewards are discounted; when and how values should be bootstrapped; or even the nature of the rewards themselves. It is well-known that these decisions are crucial to the overall success of RL algorithms. We discuss a gradient-based meta-learning algorithm that is able to adapt the nature of the return, online, whilst interacting and learning from the environment. When applied to 57 games on the Atari 2600 environment over 200 million frames, our algorithm achieved a new state-of-the-art performance.

##### Abstract (translated by Google)
强化学习算法的目标是估计和/或优化值函数。然而，与监督式学习不同，没有教师或预言者可以提供真正的价值功能。相反，大多数强化学习算法估计和/或优化值函数的代理。该代理通常基于对真值函数的采样和自举近似，称为返回。回报的具体选择是决定算法性质的主要因素之一：未来奖励的折扣率;何时以及如何引导价值;甚至奖励本身的性质。众所周知，这些决定对RL算法的整体成功至关重要。我们讨论了一种基于渐变的元学习算法，它能够适应网上回归的性质，同时与环境进行交互和学习。我们的算法应用于超过2亿帧的Atari 2600环境中的57场比赛时，实现了一种新的最先进的性能。

##### URL
[http://arxiv.org/abs/1805.09801](http://arxiv.org/abs/1805.09801)

##### PDF
[http://arxiv.org/pdf/1805.09801](http://arxiv.org/pdf/1805.09801)

