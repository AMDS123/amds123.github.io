---
layout: post
title: "Solving Imperfect-Information Games via Discounted Regret Minimization"
date: 2018-09-11 17:11:17
categories: arXiv_AI
tags: arXiv_AI
author: Noam Brown, Tuomas Sandholm
mathjax: true
---

* content
{:toc}

##### Abstract
Counterfactual regret minimization (CFR) is a family of iterative algorithms that are the most popular and, in practice, fastest approach to approximately solving large imperfect-information games. In this paper we introduce novel CFR variants that 1) discount regrets from earlier iterations in various ways (in some cases differently for positive and negative regrets), 2) reweight iterations in various ways to obtain the output strategies, 3) use a non-standard regret minimizer and/or 4) leverage "optimistic regret matching". They lead to dramatically improved performance in many settings. For one, we introduce a variant that outperforms CFR+, the prior state-of-the-art algorithm, in every game tested, including large-scale realistic settings. CFR+ is a formidable benchmark: no other algorithm has been able to outperform it. Finally, we show that, unlike CFR+, many of the important new variants are compatible with modern imperfect-information-game pruning techniques and one is also compatible with sampling in the game tree.

##### Abstract (translated by Google)
反事实遗憾最小化（CFR）是一系列迭代算法，是最受欢迎的，实际上是近似解决大型不完美信息游戏的最快方法。在本文中，我们介绍了新的CFR变体，1）折扣从早期迭代以各种方式遗憾（在某些情况下对正面和负面遗憾不同），2）以各种方式重新加权迭代以获得输出策略，3）使用非标准后悔最小化和/或4）利用“乐观后悔匹配”。它们可以在许多环境中显着提高性能。首先，我们在每个测试的游戏中引入一个优于CFR +的变体，这是先前最先进的算法，包括大规模的真实设置。 CFR +是一个强大的基准：没有其他算法能够超越它。最后，我们表明，与CFR +不同，许多重要的新变种与现代不完美信息游戏修剪技术兼容，并且还与游戏树中的采样兼容。

##### URL
[http://arxiv.org/abs/1809.04040](http://arxiv.org/abs/1809.04040)

##### PDF
[http://arxiv.org/pdf/1809.04040](http://arxiv.org/pdf/1809.04040)

