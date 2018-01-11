---
layout: post
title: "Robust Propensity Score Computation Method based on Machine Learning with Label-corrupted Data"
date: 2018-01-09 20:35:31
categories: arXiv_AI
tags: arXiv_AI
author: Chen Wang, Suzhen Wang, Fuyan Shi, Zaixiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In biostatistics, propensity score is a common approach to analyze the imbalance of covariate and process confounding covariates to eliminate differences between groups. While there are an abundant amount of methods to compute propensity score, a common issue of them is the corrupted labels in the dataset. For example, the data collected from the patients could contain samples that are treated mistakenly, and the computing methods could incorporate them as a misleading information. In this paper, we propose a Machine Learning-based method to handle the problem. Specifically, we utilize the fact that the majority of sample should be labeled with the correct instance and design an approach to first cluster the data with spectral clustering and then sample a new dataset with a distribution processed from the clustering results. The propensity score is computed by Xgboost, and a mathematical justification of our method is provided in this paper. The experimental results illustrate that xgboost propensity scores computing with the data processed by our method could outperform the same method with original data, and the advantages of our method increases as we add some artificial corruptions to the dataset. Meanwhile, the implementation of xgboost to compute propensity score for multiple treatments is also a pioneering work in the area.

##### Abstract (translated by Google)
在生物统计学中，倾向评分是分析协变量和过程混杂协变量的不平衡以消除组间差异的常用方法。虽然有大量的方法来计算倾向得分，但它们的一个常见问题是数据集中的损坏的标签。例如，从患者收集的数据可能包含错误处理的样本，计算方法可能会将其纳入误导性信息。在本文中，我们提出了一种基于机器学习的方法来处理这个问题。具体而言，我们利用这样一个事实，即大多数样本应该标记正确的实例，并设计一种方法，首先用谱聚类对数据进行聚类，然后对从聚类结果处理后的分布进行采样。倾向得分由Xgboost计算，本文给出了我们方法的数学证明。实验结果表明，用我们的方法处理的数据的xgboost倾向分数计算可以优于同样的方法与原始数据，我们的方法的优点随着我们添加一些人为破坏数据集。同时，用xgboost来计算多次处理的倾向得分也是该领域的开创性工作。

##### URL
[https://arxiv.org/abs/1801.03132](https://arxiv.org/abs/1801.03132)

##### PDF
[https://arxiv.org/pdf/1801.03132](https://arxiv.org/pdf/1801.03132)

