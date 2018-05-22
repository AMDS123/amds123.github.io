---
layout: post
title: "Safe Policy Learning from Observations"
date: 2018-05-20 17:47:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Elad Sarafian, Aviv Tamar, Sarit Kraus
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of learning a policy by observing numerous non-expert agents. Our goal is to extract a policy that, with high-confidence, acts better than the average agents' performance. Such a setting is important for real-world problems where expert data is scarce but non-expert data can easily be obtained, e.g. by crowdsourcing. Our approach is to pose this problem as safe policy improvement in Reinforcement Learning. First, we evaluate an average behavior policy and approximate its value function. Then, we develop a stochastic policy improvement algorithm, termed Rerouted Behavior Improvement (RBI), that safely improves the average behavior. The primary advantages of RBI over current safe learning methods are its stability in the presence of value estimation errors and the elimination of a policy search process. We demonstrate these advantages in a Taxi grid-world domain and in four games from the Atari learning environment.

##### Abstract (translated by Google)
在本文中，我们通过观察众多非专家代理来考虑学习政策的问题。我们的目标是提取一个高信度的政策，比一般代理商的表现更好。这样的设置对于专家数据稀少但可以容易地获得非专业数据的现实世界问题是重要的，例如，通过众包。我们的方法是将这个问题视为强化学习中的安全政策改进。首先，我们评估一个平均行为策略并估计其价值函数。然后，我们开发了一种称为重组行为改进（RBI）的随机策略改进算法，可以安全地改进平均行为。 RBI相对于目前的安全学习方法的主要优点是其在存在价值估计错误的情况下的稳定性以及取消政策搜索过程。我们在出租车网格世界领域和Atari学习环境的四场比赛中证明了这些优势。

##### URL
[https://arxiv.org/abs/1805.07805](https://arxiv.org/abs/1805.07805)

##### PDF
[https://arxiv.org/pdf/1805.07805](https://arxiv.org/pdf/1805.07805)

