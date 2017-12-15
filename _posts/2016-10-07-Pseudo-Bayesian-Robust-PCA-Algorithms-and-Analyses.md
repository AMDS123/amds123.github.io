---
layout: post
title: "Pseudo-Bayesian Robust PCA: Algorithms and Analyses"
date: 2016-10-07 16:08:25
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Optimization
author: Tae-Hyun Oh, Yasuyuki Matsushita, In So Kweon, David Wipf
mathjax: true
---

* content
{:toc}

##### Abstract
Commonly used in computer vision and other applications, robust PCA represents an algorithmic attempt to reduce the sensitivity of classical PCA to outliers. The basic idea is to learn a decomposition of some data matrix of interest into low rank and sparse components, the latter representing unwanted outliers. Although the resulting optimization problem is typically NP-hard, convex relaxations provide a computationally-expedient alternative with theoretical support. However, in practical regimes performance guarantees break down and a variety of non-convex alternatives, including Bayesian-inspired models, have been proposed to boost estimation quality. Unfortunately though, without additional a priori knowledge none of these methods can significantly expand the critical operational range such that exact principal subspace recovery is possible. Into this mix we propose a novel pseudo-Bayesian algorithm that explicitly compensates for design weaknesses in many existing non-convex approaches leading to state-of-the-art performance with a sound analytical foundation. Surprisingly, our algorithm can even outperform convex matrix completion despite the fact that the latter is provided with perfect knowledge of which entries are not corrupted.

##### Abstract (translated by Google)
通常用于计算机视觉和其他应用，稳健的PCA代表了一种算法，试图降低传统PCA对异常值的敏感性。其基本思想是学习一些感兴趣的数据矩阵分解为低阶和稀疏分量，后者代表不需要的离群值。尽管由此产生的优化问题通常是NP难题，凸松弛提供了一个计算上有利的选择与理论支持。然而，在实际制度中，性能保证被打破，并且已经提出了包括贝叶斯启发模型在内的各种非凸替代方案来提高估计质量。不幸的是，如果没有额外的先验知识，这些方法都不能显着地扩大关键的操作范围，使得精确的主要子空间恢复成为可能。在这个混合中，我们提出了一个新的伪贝叶斯算法，明确地补偿了许多现有的非凸方法中的设计弱点，从而以良好的分析基础导致了最先进的性能。令人惊讶的是，我们的算法甚至可以胜过凸矩阵完成，尽管后者提供了完美的知识，哪些条目没有损坏。

##### URL
[https://arxiv.org/abs/1512.02188](https://arxiv.org/abs/1512.02188)

##### PDF
[https://arxiv.org/pdf/1512.02188](https://arxiv.org/pdf/1512.02188)

