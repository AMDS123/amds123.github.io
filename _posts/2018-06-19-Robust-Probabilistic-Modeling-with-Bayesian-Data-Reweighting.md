---
layout: post
title: "Robust Probabilistic Modeling with Bayesian Data Reweighting"
date: 2018-06-19 16:44:54
categories: arXiv_AI
tags: arXiv_AI Inference Prediction
author: Yixin Wang, Alp Kucukelbir, David M. Blei
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic models analyze data by relying on a set of assumptions. Data that exhibit deviations from these assumptions can undermine inference and prediction quality. Robust models offer protection against mismatch between a model's assumptions and reality. We propose a way to systematically detect and mitigate mismatch of a large class of probabilistic models. The idea is to raise the likelihood of each observation to a weight and then to infer both the latent variables and the weights from data. Inferring the weights allows a model to identify observations that match its assumptions and down-weight others. This enables robust inference and improves predictive accuracy. We study four different forms of mismatch with reality, ranging from missing latent groups to structure misspecification. A Poisson factorization analysis of the Movielens 1M dataset shows the benefits of this approach in a practical scenario.

##### Abstract (translated by Google)
概率模型依靠一组假设来分析数据。显示偏离这些假设的数据可能会影响推断和预测质量。强大的模型可以防止模型假设与现实之间的不匹配。我们提出了一种系统检测和减轻大量概率模型失配的方法。这个想法是将每次观察的可能性提高到一个权重，然后从数据中推断潜在变量和权重。通过推算权重，模型可以确定与其假设相符的观察结果并减小其他的观测值。这可以实现强大的推理并提高预测准确性。我们研究了四种不同形式的与现实的不一致，从失踪潜在群体到结构错误指定。 Movielens 1M数据集的泊松因子分析显示了这种方法在实际情景中的好处。

##### URL
[http://arxiv.org/abs/1606.03860](http://arxiv.org/abs/1606.03860)

##### PDF
[http://arxiv.org/pdf/1606.03860](http://arxiv.org/pdf/1606.03860)

