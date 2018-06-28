---
layout: post
title: "Piecewise Approximations of Black Box Models for Model Interpretation"
date: 2018-06-27 02:10:56
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Kartik Ahuja, William R. Zame, Mihaela van der Schaar
mathjax: true
---

* content
{:toc}

##### Abstract
Machine Learning models have proved extremely successful for a wide variety of supervised learning problems, but the predictions of many of these models are difficult to interpret. A recent literature interprets the predictions of more general "black-box" machine learning models by approximating these models in terms of simpler models such as piecewise linear or piecewise constant models. Existing literature constructs these approximations in an ad-hoc manner. We provide a tractable dynamic programming algorithm that partitions the feature space into clusters in a principled way and then uses this partition to provide both piecewise constant and piecewise linear interpretations of an arbitrary "black-box" model. When loss is measured in terms of mean squared error, our approximation is optimal (under certain conditions); for more general loss functions, our interpretation is probably approximately optimal (in the sense of PAC learning). Experiments with real and synthetic data show that it continues to provide significant improvements (in terms of mean squared error) over competing approaches.

##### Abstract (translated by Google)
机器学习模型对于各种监督学习问题已经证明非常成功，但很多这些模型的预测很难解释。最近的一篇文献解释了对更一般的“黑盒子”机器学习模型的预测，通过将这些模型用分段线性或分段常数模型等简单模型进行近似。现有文献以临时方式构建这些近似值。我们提供了一个易于理解的动态规划算法，该算法将特征空间以原理方式划分为簇，然后使用此划分为任意“黑盒”模型提供分段常量和分段线性解释。当以均方误差来衡量损失时，我们的近似是最优的（在某些条件下）;对于更一般的损失函数，我们的解释可能是近似最优的（就PAC学习而言）。使用真实和合成数据进行的实验表明，与竞争方法相比，它继续提供重大改进（就均方误差而言）。

##### URL
[http://arxiv.org/abs/1806.10270](http://arxiv.org/abs/1806.10270)

##### PDF
[http://arxiv.org/pdf/1806.10270](http://arxiv.org/pdf/1806.10270)

