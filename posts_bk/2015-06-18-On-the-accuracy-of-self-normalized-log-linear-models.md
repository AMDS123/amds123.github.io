---
layout: post
title: "On the accuracy of self-normalized log-linear models"
date: 2015-06-18 15:22:50
categories: arXiv_CL
tags: arXiv_CL Regularization Attention Prediction
author: Jacob Andreas, Maxim Rabinovich, Dan Klein, Michael I. Jordan
mathjax: true
---

* content
{:toc}

##### Abstract
Calculation of the log-normalizer is a major computational obstacle in applications of log-linear models with large output spaces. The problem of fast normalizer computation has therefore attracted significant attention in the theoretical and applied machine learning literature. In this paper, we analyze a recently proposed technique known as "self-normalization", which introduces a regularization term in training to penalize log normalizers for deviating from zero. This makes it possible to use unnormalized model scores as approximate probabilities. Empirical evidence suggests that self-normalization is extremely effective, but a theoretical understanding of why it should work, and how generally it can be applied, is largely lacking. We prove generalization bounds on the estimated variance of normalizers and upper bounds on the loss in accuracy due to self-normalization, describe classes of input distributions that self-normalize easily, and construct explicit examples of high-variance input distributions. Our theoretical results make predictions about the difficulty of fitting self-normalized models to several classes of distributions, and we conclude with empirical validation of these predictions.

##### Abstract (translated by Google)
对数标准化器的计算是具有大输出空间的对数线性模型的应用中的主要计算障碍。快速归一化器计算的问题因此在理论和应用的机器学习文献中引起了显着的关注。在本文中，我们分析了最近提出的一种称为“自我归一化”的技术，该技术在训练中引入了一个正则化术语来惩罚对数标准偏差从零开始。这使得有可能使用非标准化的模型分数作为近似概率。经验证据表明，自我规范化是非常有效的，但理论上理解为什么它应该起作用，以及它的适用程度如何，这在很大程度上是缺乏的。我们证明归一化的估计方差和归一化导致的准确度损失的上界的泛化界限，描述易于自我规范化的输入分布类别，构造高方差输入分布的明确例子。我们的理论结果预测了将自我归一化模型拟合到几类分布的难度，并且我们通过对这些预测的经验验证得出结论。

##### URL
[https://arxiv.org/abs/1506.04147](https://arxiv.org/abs/1506.04147)

##### PDF
[https://arxiv.org/pdf/1506.04147](https://arxiv.org/pdf/1506.04147)

