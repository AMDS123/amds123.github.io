---
layout: post
title: "Multinomial Logit Bandit with Linear Utility Functions"
date: 2018-05-08 12:23:54
categories: arXiv_AI
tags: arXiv_AI Face
author: Mingdong Ou, Nan Li, Shenghuo Zhu, Rong Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Multinomial logit bandit is a sequential subset selection problem which arises in many applications. In each round, the player selects a $K$-cardinality subset from $N$ candidate items, and receives a reward which is governed by a {\it multinomial logit} (MNL) choice model considering both item utility and substitution property among items. The player's objective is to dynamically learn the parameters of MNL model and maximize cumulative reward over a finite horizon $T$. This problem faces the exploration-exploitation dilemma, and the involved combinatorial nature makes it non-trivial. In recent years, there have developed some algorithms by exploiting specific characteristics of the MNL model, but all of them estimate the parameters of MNL model separately and incur a regret no better than $\tilde{O}\big(\sqrt{NT}\big)$ which is not preferred for large candidate set size $N$. In this paper, we consider the {\it linear utility} MNL choice model whose item utilities are represented as linear functions of $d$-dimension item features, and propose an algorithm, titled {\bf LUMB}, to exploit the underlying structure. It is proven that the proposed algorithm achieves $\tilde{O}\big(dK\sqrt{T}\big)$ regret which is free of candidate set size. Experiments show the superiority of the proposed algorithm.

##### Abstract (translated by Google)
多项logit强盗是一个在许多应用中出现的顺序子集选择问题。在每轮中，玩家从$ N $个候选物品中选择一个$ K $  -  cardinality子集，并且接收一个奖励，该奖励由一个{\ it多项式logit}（MNL）选择模型考虑项目效用和项目间的替代属性。玩家的目标是动态学习MNL模型的参数，并在有限范围$ T $内最大化累积奖励。这个问题面临勘探开发困境，涉及的组合性质使其不平凡。近年来，通过利用MNL模型的特定特性开发了一些算法，但它们都分别估计MNL模型的参数，并且产生的后悔不比$ \ tilde {O} \ big（\ sqrt {NT} \ big）$，这对于大型候选集大小$ N $不是首选。在本文中，我们考虑{\ it linear utility} MNL选择模型，其项目实用程序被表示为$ d $ -dimension项目特征的线性函数，并且提出了一个名为{\ bf LUMB}的算法来利用底层结构。证明了所提出的算法实现了无候选集大小的$ \ tilde {O} \ big（dK \ sqrt {T} \ big）$ regret。实验证明了该算法的优越性。

##### URL
[https://arxiv.org/abs/1805.02971](https://arxiv.org/abs/1805.02971)

##### PDF
[https://arxiv.org/pdf/1805.02971](https://arxiv.org/pdf/1805.02971)

