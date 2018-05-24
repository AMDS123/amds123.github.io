---
layout: post
title: "Analysis of Thompson Sampling for Graphical Bandits Without the Graphs"
date: 2018-05-23 01:47:56
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Fang Liu, Zizhan Zheng, Ness Shroff
mathjax: true
---

* content
{:toc}

##### Abstract
We study multi-armed bandit problems with graph feedback, in which the decision maker is allowed to observe the neighboring actions of the chosen action, in a setting where the graph may vary over time and is never fully revealed to the decision maker. We show that when the feedback graphs are undirected, the original Thompson Sampling achieves the optimal (within logarithmic factors) regret $\tilde{O}\left(\sqrt{\beta_0(G)T}\right)$ over time horizon $T$, where $\beta_0(G)$ is the average independence number of the latent graphs. To the best of our knowledge, this is the first result showing that the original Thompson Sampling is optimal for graphical bandits in the undirected setting. A slightly weaker regret bound of Thompson Sampling in the directed setting is also presented. To fill this gap, we propose a variant of Thompson Sampling, that attains the optimal regret in the directed setting within a logarithmic factor. Both algorithms can be implemented efficiently and do not require the knowledge of the feedback graphs at any time.

##### Abstract (translated by Google)
我们研究带有图形反馈的多武装强盗问题，其中决策者被允许观察所选行动的邻近行为，其中图表可能随时间而变化并且决不会完全向决策者透露。我们证明，当反馈图是无向的时，原始的汤普森抽样实现了最优（在对数因子内）后悔$ \ tilde {O} \ left（\ sqrt {\ beta_0（G）T} \ right）$在时间范围内$ T $，其中$ \ beta_0（G）$是潜在图的平均独立数。就我们所知，这是第一个结果，表明原始汤普森采样对于无向环境中的图形盗贼是最佳的。还介绍了Thompson Sampling在定向环境中稍微弱一点的遗憾。为了填补这个空白，我们提出了一个汤普森采样的变体，在对数因子内的定向设置中获得最佳遗憾。这两种算法都可以高效地实现，并且不需要随时了解反馈图。

##### URL
[http://arxiv.org/abs/1805.08930](http://arxiv.org/abs/1805.08930)

##### PDF
[http://arxiv.org/pdf/1805.08930](http://arxiv.org/pdf/1805.08930)

