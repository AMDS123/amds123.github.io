---
layout: post
title: "Robust Covariate Shift Prediction with General Losses and Feature Views"
date: 2017-12-28 20:04:43
categories: arXiv_AI
tags: arXiv_AI Face Classification Prediction Relation
author: Anqi Liu, Brian D. Ziebart
mathjax: true
---

* content
{:toc}

##### Abstract
Covariate shift relaxes the widely-employed independent and identically distributed (IID) assumption by allowing different training and testing input distributions. Unfortunately, common methods for addressing covariate shift by trying to remove the bias between training and testing distributions using importance weighting often provide poor performance guarantees in theory and unreliable predictions with high variance in practice. Recently developed methods that construct a predictor that is inherently robust to the difficulties of learning under covariate shift are restricted to minimizing logloss and can be too conservative when faced with high-dimensional learning tasks. We address these limitations in two ways: by robustly minimizing various loss functions, including non-convex ones, under the testing distribution; and by separately shaping the influence of covariate shift according to different feature-based views of the relationship between input variables and example labels. These generalizations make robust covariate shift prediction applicable to more task scenarios. We demonstrate the benefits on classification under covariate shift tasks.

##### Abstract (translated by Google)
通过允许不同的训练和测试输入分布，协变量放宽了广泛采用的独立和相同分布（IID）假设。不幸的是，通过尝试使用重要性加权来消除训练和测试分布之间的偏差来解决协变量移动的常见方法通常在理论上提供较差的性能保证，并且在实践中具有高度差异的不可靠的预测。最近开发的方法构造了一个固有的对协变量变化下学习困难的鲁棒性的预测变量，这个方法受限于最小化logloss，当面对高维学习任务时可能过于保守。我们以两种方式解决这些限制：在测试分布下，通过强有力地最小化各种损失函数，包括非凸函数;并根据输入变量与实例标签之间关系的不同特征来分别形成协变量的影响。这些一般化使强大的协变量转换预测适用于更多的任务场景。我们证明协变量任务下分类的好处。

##### URL
[https://arxiv.org/abs/1712.10043](https://arxiv.org/abs/1712.10043)

##### PDF
[https://arxiv.org/pdf/1712.10043](https://arxiv.org/pdf/1712.10043)

