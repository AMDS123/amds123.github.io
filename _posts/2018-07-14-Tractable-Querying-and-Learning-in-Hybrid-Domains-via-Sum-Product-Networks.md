---
layout: post
title: "Tractable Querying and Learning in Hybrid Domains via Sum-Product Networks"
date: 2018-07-14 23:25:16
categories: arXiv_AI
tags: arXiv_AI Face Inference
author: Andreas Bueff, Stefanie Speichert, Vaishak Belle
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic representations, such as Bayesian and Markov networks, are fundamental to much of statistical machine learning. Thus, learning probabilistic representations directly from data is a deep challenge, the main computational bottleneck being inference that is intractable. Tractable learning is a powerful new paradigm that attempts to learn distributions that support efficient probabilistic querying. By leveraging local structure, representations such as sum-product networks (SPNs) can capture high tree-width models with many hidden layers, essentially a deep architecture, while still admitting a range of probabilistic queries to be computable in time polynomial in the network size. The leaf nodes in SPNs, from which more intricate mixtures are formed, are tractable univariate distributions, and so the literature has focused on Bernoulli and Gaussian random variables. This is clearly a restriction for handling mixed discrete-continuous data, especially if the continuous features are generated from non-parametric and non-Gaussian distribution families. In this work, we present a framework that systematically integrates SPN structure learning with weighted model integration, a recently introduced computational abstraction for performing inference in hybrid domains, by means of piecewise polynomial approximations of density functions of arbitrary shape. Our framework is instantiated by exploiting the notion of propositional abstractions, thus minimally interfering with the SPN structure learning module, and supports a powerful query interface for conditioning on interval constraints. Our empirical results show that our approach is effective, and allows a study of the trade off between the granularity of the learned model and its predictive power.

##### Abstract (translated by Google)
概率表示，如贝叶斯网络和马尔可夫网络，是许多统计机器学习的基础。因此，直接从数据中学习概率表示是一个深刻的挑战，主要的计算瓶颈是难以理解的推理。可追踪学习是一种强有力的新范例，试图学习支持有效概率查询的分布。通过利用局部结构，诸如和积网络（SPN）之类的表示可以捕获具有许多隐藏层的高树宽度模型，基本上是深层体系结构，同时仍然允许一系列概率查询在网络大小的时间多项式中可计算。 SPN中的叶节点（其中形成更复杂的混合物）是易处理的单变量分布，因此文献集中于伯努利和高斯随机变量。这显然是处理混合离散连续数据的限制，特别是如果连续特征是从非参数和非高斯分布族生成的。在这项工作中，我们提出了一个框架，系统地将SPN结构学习与加权模型集成，最近引入的计算抽象，用于在混合域中执行推理，通过任意形状的密度函数的分段多项式近似。我们的框架通过利用命题抽象的概念进行实例化，从而最小程度地干扰SPN结构学习模块，并支持强大的查询接口来调节区间约束。我们的实证结果表明，我们的方法是有效的，并且允许研究学习模型的粒度与其预测能力之间的权衡。

##### URL
[http://arxiv.org/abs/1807.05464](http://arxiv.org/abs/1807.05464)

##### PDF
[http://arxiv.org/pdf/1807.05464](http://arxiv.org/pdf/1807.05464)

