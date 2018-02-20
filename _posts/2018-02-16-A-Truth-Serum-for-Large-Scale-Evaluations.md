---
layout: post
title: "A Truth Serum for Large-Scale Evaluations"
date: 2018-02-16 22:20:30
categories: arXiv_AI
tags: arXiv_AI Review
author: Vijay Kamble, David Marn, Nihar Shah, Abhay Parekh, Kannan Ramachandran
mathjax: true
---

* content
{:toc}

##### Abstract
A major challenge in obtaining large-scale evaluations, e.g., product or service reviews on online platforms, labeling images, grading in online courses, etc., is that of eliciting honest responses from agents in the absence of verifiability. We propose a new reward mechanism with strong incentive properties applicable in a wide variety of such settings. This mechanism has a simple and intuitive output agreement structure: an agent gets a reward only if her response for an evaluation matches that of her peer. But instead of the reward being the same across different answers, it is inversely proportional to a popularity index of each answer. This index is a second order population statistic that captures how frequently two agents performing the same evaluation agree on the particular answer. Rare agreements thus earn a higher reward than agreements that are relatively more common. 
 In the regime where there are a large number of evaluation tasks, we show that truthful behavior is a strict Bayes-Nash equilibrium of the game induced by the mechanism. Further, we show that the truthful equilibrium is approximately optimal in terms of expected payoffs to the agents across all symmetric equilibria, where the approximation error vanishes in the number of evaluation tasks. Moreover, under a mild condition on strategy space, we show that any symmetric equilibrium that gives a higher expected payoff than the truthful equilibrium must be close to being fully informative if the number of evaluations is large. These last two results are driven by a new notion of an agreement measure that is shown to be monotonic in information loss. This notion and its properties are of independent interest.

##### Abstract (translated by Google)
获得大规模评估（如在线平台上的产品或服务评论，标签图像，在线课程评分等）的主要挑战是在缺乏可验证性的情况下引发代理人的诚实回应。我们提出了一个新的奖励机制，具有强大的激励特性，适用于各种不同的环境。这种机制具有简单直观的输出协议结构：只有当她的评估答案与其同伴的评估相匹配时，代理才能获得奖励。但是，不同答案中的奖励是相同的，它与每个答案的人气指数成反比。该指数是一个二阶人口统计数据，可以反映出执行相同评估的两位代理人就特定答案达成一致的频率。因此，与罕见的协议相比，稀有协议的收益更高。
 在有大量评估任务的机制中，我们证明真实行为是机制引发的游戏的严格贝叶斯纳什均衡。此外，我们证明了真实均衡在所有对称均衡的代理期望收益方面是近似最优的，其中近似误差在评估任务的数量中消失。此外，在策略空间的温和条件下，我们表明，如果评估数量很大，那么任何对称均衡都会提供比真实均衡更高的期望收益，这必须接近完全信息化。最后两个结果是由一个新的协议措施概念驱动的，该协议措施在信息丢失方面显示出单调性。这个概念和它的属性是独立的利益。

##### URL
[http://arxiv.org/abs/1507.07045](http://arxiv.org/abs/1507.07045)

##### PDF
[http://arxiv.org/pdf/1507.07045](http://arxiv.org/pdf/1507.07045)

