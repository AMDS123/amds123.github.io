---
layout: post
title: "How to Combine Tree-Search Methods in Reinforcement Learning"
date: 2018-09-06 06:40:08
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yonathan Efroni, Gal Dalal, Bruno Scherrer, Shie Mannor
mathjax: true
---

* content
{:toc}

##### Abstract
Finite-horizon lookahead policies are abundantly used in Reinforcement Learning and demonstrate impressive empirical success. Usually, the lookahead policies are implemented with specific planning methods such as Monte Carlo Tree Search (e.g. in AlphaZero). Referring to the planning problem as tree search, a reasonable practice in these implementations is to back up the value only at the leaves while the information obtained at the root is not leveraged other than for updating the policy. Here, we question the potency of this approach.Namely, the latter procedure is non-contractive in general, and its convergence is not guaranteed. Our proposed enhancement is straightforward and simple: use the return from the optimal tree path to back up the values at the descendants of the root. This leads to a \gamma^h-contracting procedure, where \gamma is the discount factor and $h$ is the tree depth. To establish our results, we first introduce a notion called multiple-step greedy consistency. We then provide convergence rates for two algorithmic instantiations of the above enhancement in the presence of noise injected to both the tree search stage and value estimation stage.

##### Abstract (translated by Google)
有限地平线前瞻政策大量用于强化学习，并展示了令人印象深刻的经验成功。通常，先行策略是使用特定的计划方法实现的，例如蒙特卡罗树搜索（例如在AlphaZero中）。将规划问题称为树搜索，这些实现中的合理做法是仅在叶子处备份值，而在根目录下获取的信息不用于更新策略。在这里，我们质疑这种方法的效力。即，后一种方法通常是非收缩的，并且它的收敛性不能得到保证。我们提出的增强是简单明了的：使用最佳树路径的返回来备份根的后代的值。这导致了\ gamma ^ h-contracting过程，其中\ gamma是折扣因子，$ h $是树深度。为了建立我们的结果，我们首先介绍一种称为多步贪婪一致性的概念。然后，在存在注入树搜索阶段和值估计阶段的噪声的情况下，我们为上述增强的两个算法实例提供收敛速率。

##### URL
[http://arxiv.org/abs/1809.01843](http://arxiv.org/abs/1809.01843)

##### PDF
[http://arxiv.org/pdf/1809.01843](http://arxiv.org/pdf/1809.01843)

