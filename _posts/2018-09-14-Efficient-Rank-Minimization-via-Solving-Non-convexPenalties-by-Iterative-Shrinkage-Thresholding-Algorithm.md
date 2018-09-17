---
layout: post
title: "Efficient Rank Minimization via Solving Non-convexPenalties by Iterative Shrinkage-Thresholding Algorithm"
date: 2018-09-14 07:58:03
categories: arXiv_CV
tags: arXiv_CV Regularization Attention RNN
author: Zaiyi Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Rank minimization (RM) is a wildly investigated task of finding solutions by exploiting low-rank structure of parameter matrices. Recently, solving RM problem by leveraging non-convex relaxations has received significant attention. It has been demonstrated by some theoretical and experimental work that non-convex relaxation, e.g. Truncated Nuclear Norm Regularization (TNNR) and Reweighted Nuclear Norm Regularization (RNNR), can provide a better approximation of original problems than convex relaxations. However, designing an efficient algorithm with theoretical guarantee remains a challenging problem. In this paper, we propose a simple but efficient proximal-type method, namely Iterative Shrinkage-Thresholding Algorithm(ISTA), with concrete analysis to solve rank minimization problems with both non-convex weighted and reweighted nuclear norm as low-rank regularizers. Theoretically, the proposed method could converge to the critical point under very mild assumptions with the rate in the order of $O(1/T)$. Moreover, the experimental results on both synthetic data and real world data sets show that proposed algorithm outperforms state-of-arts in both efficiency and accuracy.

##### Abstract (translated by Google)
秩最小化（RM）是通过利用参数矩阵的低秩结构来寻找解决方案的广泛研究的任务。最近，通过利用非凸松弛来解决RM问题已经受到了极大的关注。一些理论和实验工作已经证明非凸松弛，例如，截断核准则正则化（TNNR）和再加权核规范正则化（RNNR）可以提供比凸松弛更好的原始问题近似。然而，设计具有理论保证的有效算法仍然是一个具有挑战性的问在本文中，我们提出了一种简单但有效的近端类型方法，即迭代收缩 - 阈值算法（ISTA），通过具体分析来解决非凸加权和重加权核范数作为低秩正则化的秩最小化问题。从理论上讲，所提出的方法可以在非常温和的假设下收敛到临界点，其速率大约为$ O（1 / T）$。此外，合成数据和现实世界数据集的实验结果表明，所提出的算法在效率和准确性方面都优于现有技术。

##### URL
[http://arxiv.org/abs/1809.05292](http://arxiv.org/abs/1809.05292)

##### PDF
[http://arxiv.org/pdf/1809.05292](http://arxiv.org/pdf/1809.05292)

