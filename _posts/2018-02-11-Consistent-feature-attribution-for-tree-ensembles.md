---
layout: post
title: "Consistent feature attribution for tree ensembles"
date: 2018-02-11 21:44:49
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Scott M. Lundberg, Su-In Lee
mathjax: true
---

* content
{:toc}

##### Abstract
It is critical in many applications to understand what features are important for a model, and why individual predictions were made. For tree ensemble methods these questions are usually answered by attributing importance values to input features, either globally or for a single prediction. Here we show that current feature attribution methods are inconsistent, which means changing the model to rely more on a given feature can actually decrease the importance assigned to that feature. To address this problem we develop fast exact solutions for SHAP (SHapley Additive exPlanation) values, which were recently shown to be the unique additive feature attribution method based on conditional expectations that is both consistent and locally accurate. We integrate these improvements into the latest version of XGBoost, demonstrate the inconsistencies of current methods, and show how using SHAP values results in significantly improved supervised clustering performance. Feature importance values are a key part of understanding widely used models such as gradient boosting trees and random forests, so improvements to them have broad practical implications.

##### Abstract (translated by Google)
在许多应用中，了解哪些特征对模型非常重要，以及为什么进行个别预测是至关重要的。对于树集合方法，这些问题通常通过将输入要素的重要性值归因于全局或单个预测来回答。这里我们展示当前的特征归属方法是不一致的，这意味着改变模型以更多地依赖给定的特征实际上可以减少分配给该特征的重要性。为了解决这个问题，我们为SHAP（SHapley Additive exPlanation）值开发了快速精确解，这些解决方案最近被证明是基于条件期望的独特的加法特征归因方法，它既是一致的又是局部准确的。我们将这些改进集成到最新版本的XGBoost中，演示当前方法的不一致性，并展示如何使用SHAP值显着提高受监督的集群性能。特征重要性值是理解广泛使用的模型（如梯度提升树和随机森林）的关键部分，因此它们的改进具有广泛的实际意义。

##### URL
[http://arxiv.org/abs/1706.06060](http://arxiv.org/abs/1706.06060)

##### PDF
[http://arxiv.org/pdf/1706.06060](http://arxiv.org/pdf/1706.06060)

