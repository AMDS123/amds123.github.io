---
layout: post
title: "Bayesian Neighbourhood Component Analysis"
date: 2016-04-08 13:35:03
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Dong Wang, Xiaoyang Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a good distance metric in feature space potentially improves the performance of the KNN classifier and is useful in many real-world applications. Many metric learning algorithms are however based on the point estimation of a quadratic optimization problem, which is time-consuming, susceptible to overfitting, and lack a natural mechanism to reason with parameter uncertainty, an important property useful especially when the training set is small and/or noisy. To deal with these issues, we present a novel Bayesian metric learning method, called Bayesian NCA, based on the well-known Neighbourhood Component Analysis method, in which the metric posterior is characterized by the local label consistency constraints of observations, encoded with a similarity graph instead of independent pairwise constraints. For efficient Bayesian optimization, we explore the variational lower bound over the log-likelihood of the original NCA objective. Experiments on several publicly available datasets demonstrate that the proposed method is able to learn robust metric measures from small size dataset and/or from challenging training set with labels contaminated by errors. The proposed method is also shown to outperform a previous pairwise constrained Bayesian metric learning method.

##### Abstract (translated by Google)
在特征空间中学习好的距离度量可能会提高KNN分类器的性能，并且在许多实际应用中非常有用。然而，许多度量学习算法是基于二次优化问题的点估计，其耗费时间，易于过度拟合，并且缺乏用参数不确定性推理的自然机制，这是一个重要的性质，特别是在训练集较小/或嘈杂。为了解决这些问题，我们基于众所周知的邻域分量分析方法，提出了一种新的贝叶斯度量学习方法，称为Bayesian NCA，其中度量后验以观察的局部标签一致性约束为特征，用相似性编码图而不是独立的成对约束。为了有效的贝叶斯优化，我们探索原始NCA目标的对数似然的变分下界。在几个公开可用的数据集上的实验表明，所提出的方法能够从小尺寸的数据集和/或来自具有误差的标签的具有挑战性的训练集中学习鲁棒的度量测量。所提出的方法也表现出优于先前的成对约束贝叶斯度量学习方法。

##### URL
[https://arxiv.org/abs/1604.02354](https://arxiv.org/abs/1604.02354)

##### PDF
[https://arxiv.org/pdf/1604.02354](https://arxiv.org/pdf/1604.02354)

