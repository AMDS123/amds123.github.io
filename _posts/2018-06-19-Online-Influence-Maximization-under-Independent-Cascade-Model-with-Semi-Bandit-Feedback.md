---
layout: post
title: "Online Influence Maximization under Independent Cascade Model with Semi-Bandit Feedback"
date: 2018-06-19 05:51:52
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Zheng Wen, Branislav Kveton, Michal Valko, Sharan Vaswani
mathjax: true
---

* content
{:toc}

##### Abstract
We study the online influence maximization problem in social networks under the independent cascade model. Specifically, we aim to learn the set of "best influencers" in a social network online while repeatedly interacting with it. We address the challenges of (i) combinatorial action space, since the number of feasible influencer sets grows exponentially with the maximum number of influencers, and (ii) limited feedback, since only the influenced portion of the network is observed. Under a stochastic semi-bandit feedback, we propose and analyze IMLinUCB, a computationally efficient UCB-based algorithm. Our bounds on the cumulative regret are polynomial in all quantities of interest, achieve near-optimal dependence on the number of interactions and reflect the topology of the network and the activation probabilities of its edges, thereby giving insights on the problem complexity. To the best of our knowledge, these are the first such results. Our experiments show that in several representative graph topologies, the regret of IMLinUCB scales as suggested by our upper bounds. IMLinUCB permits linear generalization and thus is both statistically and computationally suitable for large-scale problems. Our experiments also show that IMLinUCB with linear generalization can lead to low regret in real-world online influence maximization.

##### Abstract (translated by Google)
我们研究了独立级联模型下社交网络中的在线影响最大化问题。具体来说，我们的目标是在一个社交网络中在线学习一组“最佳影响者”，同时反复进行交互。我们解决了（i）组合行动空间的挑战，因为可行影响者集合的数量随着影响者的最大数量呈指数增长，并且（ii）有限的反馈，因为仅观察到网络的受影响部分。在随机半强盗反馈下，我们提出并分析IMLinUCB，一种计算效率高的基于UCB的算法。我们对累积遗憾的界限是所有感兴趣量的多项式，实现对交互次数的近乎最优的依赖，并反映网络的拓扑结构和边缘的激活概率，从而提供对问题复杂性的洞察。据我们所知，这是第一个这样的结果。我们的实验表明，在几个有代表性的图形拓扑结构中，IMLinUCB的遗憾程度如我们的上限所示。 IMLinUCB允许线性泛化，因此在统计和计算上都适用于大规模问题。我们的实验还表明，具有线性泛化的IMLinUCB可以导致实际在线影响最大化中的低后悔。

##### URL
[http://arxiv.org/abs/1605.06593](http://arxiv.org/abs/1605.06593)

##### PDF
[http://arxiv.org/pdf/1605.06593](http://arxiv.org/pdf/1605.06593)

