---
layout: post
title: "Adaptive PCA for Time-Varying Data"
date: 2017-09-12 15:55:44
categories: arXiv_CV
tags: arXiv_CV Relation
author: Salaheddin Alakkari, John Dingliana
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an online adaptive PCA algorithm that is able to compute the full dimensional eigenspace per new time-step of sequential data. The algorithm is based on a one-step update rule that considers all second order correlations between previous samples and the new time-step. Our algorithm has O(n) complexity per new time-step in its deterministic mode and O(1) complexity per new time-step in its stochastic mode. We test our algorithm on a number of time-varying datasets of different physical phenomena. Explained variance curves indicate that our technique provides an excellent approximation to the original eigenspace computed using standard PCA in batch mode. In addition, our experiments show that the stochastic mode, despite its much lower computational complexity, converges to the same eigenspace computed using the deterministic mode.

##### Abstract (translated by Google)
在本文中，我们提出了一个在线自适应PCA算法，能够计算每个新时间步长的完整维空间特征空间。该算法基于一步更新规则，该规则考虑先前样本与新时间步长之间的所有二阶相关性。我们的算法在确定性模式下每个新时间步具有O（n）复杂度，而在其随机模式下每个新时间步具有O（1）复杂度。我们在一些不同物理现象的时变数据集上测试我们的算法。解释方差曲线表明，我们的技术提供了一个很好的近似原始特征空间计算使用标准PCA批量模式。另外，我们的实验表明，尽管计算复杂度较低，随机模式收敛到使用确定性模式计算的相同特征空间。

##### URL
[https://arxiv.org/abs/1709.02373](https://arxiv.org/abs/1709.02373)

##### PDF
[https://arxiv.org/pdf/1709.02373](https://arxiv.org/pdf/1709.02373)

