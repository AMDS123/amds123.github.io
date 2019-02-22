---
layout: post
title: "AdaLinUCB: Opportunistic Learning for Contextual Bandits"
date: 2019-02-20 22:35:24
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Xueying Guo, Xiaoxiao Wang, Xin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose and study opportunistic contextual bandits - a special case of contextual bandits where the exploration cost varies under different environmental conditions, such as network load or return variation in recommendations. When the exploration cost is low, so is the actual regret of pulling a sub-optimal arm (e.g., trying a suboptimal recommendation). Therefore, intuitively, we could explore more when the exploration cost is relatively low and exploit more when the exploration cost is relatively high. Inspired by this intuition, for opportunistic contextual bandits with Linear payoffs, we propose an Adaptive Upper-Confidence-Bound algorithm (AdaLinUCB) to adaptively balance the exploration-exploitation trade-off for opportunistic learning. We prove that AdaLinUCB achieves O((log T)^2) problem-dependent regret upper bound, which has a smaller coefficient than that of the traditional LinUCB algorithm. Moreover, based on both synthetic and real-world dataset, we show that AdaLinUCB significantly outperforms other contextual bandit algorithms, under large exploration cost fluctuations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07802](http://arxiv.org/abs/1902.07802)

##### PDF
[http://arxiv.org/pdf/1902.07802](http://arxiv.org/pdf/1902.07802)

