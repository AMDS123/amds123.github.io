---
layout: post
title: "Safe Policy Improvement with Baseline Bootstrapping"
date: 2017-12-19 13:43:41
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Romain Laroche, Paul Trichelair, Layla El Asri
mathjax: true
---

* content
{:toc}

##### Abstract
A common goal in Reinforcement Learning is to derive a good strategy given a limited batch of data. In this paper, we adopt the safe policy improvement (SPI) approach: we compute a target policy guaranteed to perform at least as well as a given baseline policy. Our SPI strategy, inspired by the knows-what-it-knows paradigms, consists in bootstrapping the target policy with the baseline policy when it does not know. We develop two computationally efficient bootstrapping algorithms, a value-based and a policy-based, both accompanied with theoretical SPI bounds. Three algorithm variants are proposed. We empirically show the literature algorithms limits on a small stochastic gridworld problem, and then demonstrate that our five algorithms not only improve the worst case scenarios, but also the mean performance.

##### Abstract (translated by Google)
强化学习的一个共同目标是在有限的一批数据的基础上推出一个好的策略。在本文中，我们采用安全政策改进（SPI）的方法：我们计算一个保证至少与给定的基准政策一样好的目标政策。我们的SPI策略受到了解知识范式的启发，其中包括在不知情的情况下用基准政策引导目标政策。我们开发了两个计算效率高的自举算法，基于价值和基于策略，都伴随着理论上的SPI界限。提出了三种算法变体。我们实验证明文献算法对一个小的随机网格问题的限制，然后证明我们的五种算法不仅改善了最坏的情况，而且改善了平均性能。

##### URL
[http://arxiv.org/abs/1712.06924](http://arxiv.org/abs/1712.06924)

##### PDF
[http://arxiv.org/pdf/1712.06924](http://arxiv.org/pdf/1712.06924)

