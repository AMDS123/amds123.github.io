---
layout: post
title: "Fast L1-NMF for Multiple Parametric Model Estimation"
date: 2016-11-11 15:54:14
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Mariano Tepper, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce a comprehensive algorithmic pipeline for multiple parametric model estimation. The proposed approach analyzes the information produced by a random sampling algorithm (e.g., RANSAC) from a machine learning/optimization perspective, using a \textit{parameterless} biclustering algorithm based on L1 nonnegative matrix factorization (L1-NMF). The proposed framework exploits consistent patterns that naturally arise during the RANSAC execution, while explicitly avoiding spurious inconsistencies. Contrarily to the main trends in the literature, the proposed technique does not impose non-intersecting parametric models. A new accelerated algorithm to compute L1-NMFs allows to handle medium-sized problems faster while also extending the usability of the algorithm to much larger datasets. This accelerated algorithm has applications in any other context where an L1-NMF is needed, beyond the biclustering approach to parameter estimation here addressed. We accompany the algorithmic presentation with theoretical foundations and numerous and diverse examples.

##### Abstract (translated by Google)
在这项工作中，我们介绍了一个全面的算法流水线多参数模型估计。所提出的方法使用基于L1非负矩阵分解（L1-NMF）的\ textit {无参数}双聚类算法，从机器学习/优化的角度分析随机采样算法（例如，RANSAC）产生的信息。提出的框架利用RANSAC执行过程中自然产生的一致模式，同时明确避免虚假的不一致。与文献中的主要趋势相反，所提出的技术不施加非相交参数模型。计算L1-NMF的新加速算法可以更快地处理中型问题，同时还可以将算法的可用性扩展到更大的数据集。这种加速算法在需要L1-NMF的任何其他环境中都有应用，除了这里提到的参数估计的双聚类方法之外。我们配合算法演示与理论基础和众多不同的例子。

##### URL
[https://arxiv.org/abs/1610.05712](https://arxiv.org/abs/1610.05712)

##### PDF
[https://arxiv.org/pdf/1610.05712](https://arxiv.org/pdf/1610.05712)

