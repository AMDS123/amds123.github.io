---
layout: post
title: "Contextual Bandits with Stochastic Experts"
date: 2018-02-23 21:03:49
categories: arXiv_AI
tags: arXiv_AI Classification
author: Rajat Sen, Karthikeyan Shanmugam, Sanjay Shakkottai
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of contextual bandits with stochastic experts, which is a variation of the traditional stochastic contextual bandit with experts problem. In our problem setting, we assume access to a class of stochastic experts, where each expert is a conditional distribution over the arms given a context. We propose upper-confidence bound (UCB) algorithms for this problem, which employ two different importance sampling based estimators for the mean reward for each expert. Both these estimators leverage information leakage among the experts, thus using samples collected under all the experts to estimate the mean reward of any given expert. This leads to instance dependent regret bounds of $\mathcal{O}\left(\lambda(\pmb{\mu})\mathcal{M}\log T/\Delta \right)$, where $\lambda(\pmb{\mu})$ is a term that depends on the mean rewards of the experts, $\Delta$ is the smallest gap between the mean reward of the optimal expert and the rest, and $\mathcal{M}$ quantifies the information leakage among the experts. We show that under some assumptions $\lambda(\pmb{\mu})$ is typically $\mathcal{O}(\log N)$. We implement our algorithm with stochastic experts generated from cost-sensitive classification oracles and show superior empirical performance on real-world datasets, when compared to other state of the art contextual bandit algorithms.

##### Abstract (translated by Google)
我们考虑带有随机专家的情境土匪问题，这是传统随机情境土匪与专家问题的变体。在我们的问题设置中，我们假设有一类随机专家，每个专家在给定上下文的情况下都是条件分布。我们针对这个问题提出了上置信区间（UCB）算法，该算法使用两个不同重要性抽样的估计量来计算每个专家的平均回报。这两个估计器都利用专家之间的信息泄漏，从而使用所有专家收集的样本来估计任何给定专家的平均回报。这会导致$ \ mathcal {O} \ left（\ lambda（\ pmb {\ mu}）\ mathcal {M} \ log T / \ Delta \ right）$的实例依赖后悔边界，其中$ \ lambda（\ pmb {\ mu}）$是一个取决于专家平均奖励的术语，$ \ Delta $是最优专家与其余专家的平均奖励之间的最小差距，$ \ mathcal {M} $量化信息专家之间的泄漏。我们证明，在一些假设下，$ \ lambda（\ pmb {\ mu}）$通常是$ \ mathcal {O}（\ log N）$。我们使用从成本敏感的分类规则生成的随机专家来实现我们的算法，并且与其他现有技术的上下文匪徒算法相比，在真实世界的数据集上显示出优越的经验性能。

##### URL
[http://arxiv.org/abs/1802.08737](http://arxiv.org/abs/1802.08737)

##### PDF
[http://arxiv.org/pdf/1802.08737](http://arxiv.org/pdf/1802.08737)

