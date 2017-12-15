---
layout: post
title: "On the equivalence between Kolmogorov-Smirnov and ROC curve metrics for binary classification"
date: 2016-06-01 23:12:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification
author: Paulo J. L. Adeodato, Sílvio B. Melo
mathjax: true
---

* content
{:toc}

##### Abstract
Binary decisions are very common in artificial intelligence. Applying a threshold on the continuous score gives the human decider the power to control the operating point to separate the two classes. The classifier,s discriminating power is measured along the continuous range of the score by the Area Under the ROC curve (AUC_ROC) in most application fields. Only finances uses the poor single point metric maximum Kolmogorov-Smirnov (KS) distance. This paper proposes the Area Under the KS curve (AUC_KS) for performance assessment and proves AUC_ROC = 0.5 + AUC_KS, as a simpler way to calculate the AUC_ROC. That is even more important for ROC averaging in ensembles of classifiers or n fold cross-validation. The proof is geometrically inspired on rotating all KS curve to make it lie on the top of the ROC chance diagonal. On the practical side, the independent variable on the abscissa on the KS curve simplifies the calculation of the AUC_ROC. On the theoretical side, this research gives insights on probabilistic interpretations of classifiers assessment and integrates the existing body of knowledge of the information theoretical ROC approach with the proposed statistical approach based on the thoroughly known KS distribution.

##### Abstract (translated by Google)
二元决策在人工智能中非常普遍。对连续得分应用阈值使得人决定者能够控制操作点来分离两个类别。分类器的识别能力是在大多数应用领域中沿ROC曲线下面积（AUC_ROC）的得分的连续范围测量的。只有财务使用穷单点度量最大Kolmogorov-Smirnov（KS）距离。本文提出KS曲线下的面积（AUC_KS）进行性能评估，并证明AUC_ROC = 0.5 + AUC_KS，作为计算AUC_ROC的一种更简单的方法。这对于ROC在分类器集合或n倍交叉验证中的平均更为重要。证明是几何启发旋转所有KS曲线，使其位于ROC机会对角线的顶部。实际上，KS曲线上的横坐标上的独立变量简化了AUC_ROC的计算。在理论层面上，本研究对分类器评估的概率解释提供了深入的见解，并将信息理论ROC方法的知识体系与基于完全已知的KS分布的统计方法相结合。

##### URL
[https://arxiv.org/abs/1606.00496](https://arxiv.org/abs/1606.00496)

##### PDF
[https://arxiv.org/pdf/1606.00496](https://arxiv.org/pdf/1606.00496)

