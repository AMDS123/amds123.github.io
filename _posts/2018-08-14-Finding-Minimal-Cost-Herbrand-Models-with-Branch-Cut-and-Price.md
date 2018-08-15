---
layout: post
title: "Finding Minimal Cost Herbrand Models with Branch-Cut-and-Price"
date: 2018-08-14 15:45:01
categories: arXiv_AI
tags: arXiv_AI
author: James Cussens
mathjax: true
---

* content
{:toc}

##### Abstract
Given (1) a set of clauses $T$ in some first-order language $\cal L$ and (2) a cost function $c : B_{{\cal L}} \rightarrow \mathbb{R}_{+}$, mapping each ground atom in the Herbrand base $B_{{\cal L}}$ to a non-negative real, then the problem of finding a minimal cost Herbrand model is to either find a Herbrand model $\cal I$ of $T$ which is guaranteed to minimise the sum of the costs of true ground atoms, or establish that there is no Herbrand model for $T$. A branch-cut-and-price integer programming (IP) approach to solving this problem is presented. Since the number of ground instantiations of clauses and the size of the Herbrand base are both infinite in general, we add the corresponding IP constraints and IP variables `on the fly' via `cutting' and `pricing' respectively. In the special case of a finite Herbrand base we show that adding all IP variables and constraints from the outset can be advantageous, showing that a challenging Markov logic network MAP problem can be solved in this way if encoded appropriately.

##### Abstract (translated by Google)
给定（1）一些条款$ T $，在一些一阶语言$ \ cal L $和（2）一个成本函数$ c：B _ {{\ cal L}} \ rightarrow \ mathbb {R} _ {+ } $，将Herbrand基础$ B _ {{\ cal L}} $中的每个地面原子映射到非负实数，然后找到最小成本Herbrand模型的问题是找到Herbrand模型$ \ cal I $保证最小化真实原子原子成本的$ T $，或确定$ T $没有Herbrand模型。提出了一种解决该问题的分支切割和价格整数规划（IP）方法。由于子句的地面实例的数量和Herbrand基数的大小一般都是无限的，我们分别通过“cut”和“pricing”来“添加”相应的IP约束和IP变量。在有限Herbrand基数的特殊情况下，我们表明从一开始就添加所有IP变量和约束可能是有利的，这表明如果适当编码，可以以这种方式解决具有挑战性的马尔可夫逻辑网络MAP问题。

##### URL
[http://arxiv.org/abs/1808.04758](http://arxiv.org/abs/1808.04758)

##### PDF
[http://arxiv.org/pdf/1808.04758](http://arxiv.org/pdf/1808.04758)

