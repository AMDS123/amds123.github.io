---
layout: post
title: "Visualizing the Feature Importance for Black Box Models"
date: 2018-07-07 14:30:25
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Giuseppe Casalicchio, Christoph Molnar, Bernd Bischl
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, a large amount of model-agnostic methods to improve the transparency, trustability and interpretability of machine learning models have been developed. We introduce local feature importance as a local version of a recent model-agnostic global feature importance method. Based on local feature importance, we propose two visual tools: partial importance (PI) and individual conditional importance (ICI) plots which visualize how changes in a feature affect the model performance on average, as well as for individual observations. Our proposed methods are related to partial dependence (PD) and individual conditional expectation (ICE) plots, but visualize the expected (conditional) feature importance instead of the expected (conditional) prediction. Furthermore, we show that averaging ICI curves across observations yields a PI curve, and integrating the PI curve with respect to the distribution of the considered feature results in the global feature importance. Another contribution of our paper is the Shapley feature importance, which fairly distributes the overall performance of a model among the features according to the marginal contributions and which can be used to compare the feature importance across different models.

##### Abstract (translated by Google)
近年来，已经开发了大量用于提高机器学习模型的透明度，可信度和可解释性的模型不可知方法。我们引入了本地特征重要性作为最近的模型不可知全局特征重要性方法的本地版本。基于局部特征重要性，我们提出了两个可视化工具：部分重要性（PI）和个体条件重要性（ICI）图，它们可视化特征的变化如何平均影响模型性能，以及个体观察。我们提出的方法涉及部分依赖（PD）和个体条件期望（ICE）图，但可视化预期（条件）特征重要性而不是预期（条件）预测。此外，我们表明，在观测值上平均ICI曲线会产生PI曲线，并且将PI曲线与所考虑特征的分布相结合会导致全局特征重要性。本文的另一个贡献是Shapley特征重要性，它根据边际贡献公平地分配模型的整体性能，并可用于比较不同模型的特征重要性。

##### URL
[http://arxiv.org/abs/1804.06620](http://arxiv.org/abs/1804.06620)

##### PDF
[http://arxiv.org/pdf/1804.06620](http://arxiv.org/pdf/1804.06620)

