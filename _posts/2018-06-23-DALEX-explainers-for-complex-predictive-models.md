---
layout: post
title: "DALEX: explainers for complex predictive models"
date: 2018-06-23 06:28:38
categories: arXiv_AI
tags: arXiv_AI Classification Prediction
author: Przemyslaw Biecek
mathjax: true
---

* content
{:toc}

##### Abstract
Predictive modeling is invaded by elastic, yet complex methods such as neural networks or ensembles (model stacking, boosting or bagging). Such methods are usually described by a large number of parameters or hyper parameters - a price that one needs to pay for elasticity. The very number of parameters makes models hard to understand. 
 This paper describes a consistent collection of explainers for predictive models, a.k.a. black boxes. Each explainer is a technique for exploration of a black box model. Presented approaches are model-agnostic, what means that they extract useful information from any predictive method despite its internal structure. Each explainer is linked with a specific aspect of a model. Some are useful in decomposing predictions, some serve better in understanding performance, while others are useful in understanding importance and conditional responses of a particular variable. 
 Every explainer presented in this paper works for a single model or for a collection of models. In the latter case, models can be compared against each other. Such comparison helps to find strengths and weaknesses of different approaches and gives additional possibilities for model validation. 
 Presented explainers are implemented in the DALEX package for R. They are based on a uniform standardized grammar of model exploration which may be easily extended. The current implementation supports the most popular frameworks for classification and regression.

##### Abstract (translated by Google)
预测建模受到弹性而复杂的方法的入侵，如神经网络或合奏（模型叠加，提升或装袋）。这种方法通常由大量参数或超参数来描述 - 这是一种需要为弹性付费的价格。很多参数使得模型难以理解。
 本文描述了一个用于预测模型的一致解释集合，又名黑盒子。每个解释器都是探索黑匣子模型的技术。提出的方法是模型不可知的，意味着它们从任何预测方法中提取有用的信息，尽管其内部结构。每个解释器都与模型的特定方面相关联。一些在分解预测中很有用，一些在理解性能方面更好，而另一些则有助于理解特定变量的重要性和条件响应。
 本文中介绍的每一位解释者都适用于单一模型或一组模型。在后一种情况下，模型可以相互比较。这种比较有助于发现不同方法的优点和缺点，并为模型验证提供了额外的可能性。
 提供的解释器在R的DALEX包中实现。它们基于统一的标准化模型探索语法，可以很容易地扩展。目前的实现支持最​​流行的分类和回归框架。

##### URL
[http://arxiv.org/abs/1806.08915](http://arxiv.org/abs/1806.08915)

##### PDF
[http://arxiv.org/pdf/1806.08915](http://arxiv.org/pdf/1806.08915)

