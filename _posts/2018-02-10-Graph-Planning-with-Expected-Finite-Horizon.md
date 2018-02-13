---
layout: post
title: "Graph Planning with Expected Finite Horizon"
date: 2018-02-10 19:12:03
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Krishnendu Chatterjee, Laurent Doyen
mathjax: true
---

* content
{:toc}

##### Abstract
Graph planning gives rise to fundamental algorithmic questions such as shortest path, traveling salesman problem, etc. A classical problem in discrete planning is to consider a weighted graph and construct a path that maximizes the sum of weights for a given time horizon $T$. However, in many scenarios, the time horizon is not fixed, but the stopping time is chosen according to some distribution such that the expected stopping time is $T$. If the stopping time distribution is not known, then to ensure robustness, the distribution is chosen by an adversary, to represent the worst-case scenario. 
 A stationary plan for every vertex always chooses the same outgoing edge. For fixed horizon or fixed stopping-time distribution, stationary plans are not sufficient for optimality. Quite surprisingly we show that when an adversary chooses the stopping-time distribution with expected stopping time $T$, then stationary plans are sufficient. While computing optimal stationary plans for fixed horizon is NP-complete, we show that computing optimal stationary plans under adversarial stopping-time distribution can be achieved in polynomial time. Consequently, our polynomial-time algorithm for adversarial stopping time also computes an optimal plan among all possible plans.

##### Abstract (translated by Google)
图计划会产生基本的算法问题，例如最短路径，旅行推销员问题等。离散计划中的一个经典问题是考虑加权图并构造一条路径，使给定时间范围$ T $的权重总和最大化。但是，在很多情况下，时间范围并不是固定的，而是根据某种分布来选择停止时间，以使得预期停止时间为$ T $。如果停止时间分布未知，则为了确保鲁棒性，分布由对手选择以表示最坏情况。
 每个顶点的静态平面图总是选择相同的出边。对于固定的时间范围或固定的停止时间分配，静态计划不足以达到最佳效果。非常令人惊讶的是，当一个对手选择了停止时间分布和预期停止时间$ T $时，那么静态计划就足够了。虽然计算固定时间的最优平稳计划是NP完全的，但我们表明计算在敌对停止时间分布下的最优平稳计划可以在多项式时间内实现。因此，我们用于敌对停止时间的多项式时间算法也计算了所有可能计划中的最佳计划。

##### URL
[http://arxiv.org/abs/1802.03642](http://arxiv.org/abs/1802.03642)

##### PDF
[http://arxiv.org/pdf/1802.03642](http://arxiv.org/pdf/1802.03642)

