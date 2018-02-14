---
layout: post
title: "Quantifying Uncertainty in Discrete-Continuous and Skewed Data with Bayesian Deep Learning"
date: 2018-02-13 17:07:13
categories: arXiv_AI
tags: arXiv_AI Super_Resolution Knowledge Deep_Learning Prediction
author: Thomas Vandal, Evan Kodra, Jennifer Dy, Sangram Ganguly, Ramakrishna Nemani, Auroop R. Ganguly
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning (DL) methods have been transforming computer vision with innovative adaptations to other domains including climate change. For DL to pervade Science and Engineering (S\&amp;E) applications where risk management is a core component, well-characterized uncertainty estimates must accompany predictions. However, S\&amp;E observations and model-simulations often follow heavily skewed distributions and are not well modeled with DL approaches, since they usually optimize a Gaussian, or Euclidean, likelihood loss. Recent developments in Bayesian Deep Learning (BDL), which attempts to capture uncertainties from noisy observations, aleatoric, and from unknown model parameters, epistemic, provide us a foundation. Here we present a discrete-continuous BDL model with Gaussian and lognormal likelihoods for uncertainty quantification (UQ). We demonstrate the approach by developing UQ estimates on "DeepSD", a super-resolution based DL model for Statistical Downscaling (SD) in climate applied to precipitation, which follows an extremely skewed distribution. We find that the discrete-continuous models outperform a basic Gaussian distribution in terms of predictive accuracy and uncertainty calibration. Furthermore, we find that the lognormal distribution, which can handle skewed distributions, produces quality uncertainty estimates at the extremes. Such results may be important across S\&amp;E, as well as other domains such as finance and economics, where extremes are often of significant interest. Furthermore, to our knowledge, this is the first UQ model in SD where both aleatoric and epistemic uncertainties are characterized.

##### Abstract (translated by Google)
深度学习（DL）方法一直在改变计算机视觉，并对包括气候变化在内的其他领域进行创新改造。对于DL贯穿以风险管理为核心组成部分的科学与工程（S＆amp; E）应用而言，充分表征的不确定性估计必须伴随预测。然而，S＆amp; E观测和模型模拟通常遵循严重偏斜的分布，并且不能很好地用DL方法建模，因为它们通常优化高斯或欧几里德可能性损失。贝叶斯深度学习（BDL）最近的发展，试图捕捉嘈杂的观察，任意的和来自未知模型参数的不确定性，认识性，为我们提供了基础。在这里我们提出了一个离散连续的BDL模型，其中包含高斯和对数正态分布的不确定性量化（UQ）。我们通过开发对“DeepSD”的UQ估计的方法，“DeepSD”是一种应用于降水的气候统计降尺度（SD）的超分辨率DL模型，该模型遵循极其偏态的分布。我们发现离散连续模型在预测精度和不确定度校准方面优于基本的高斯分布。此外，我们发现对数正态分布可以处理偏态分布，从而产生极端情况下的质量不确定性估计。这样的结果在S＆E以及其他领域如金融和经济领域可能非常重要，在这些领域中，极端情况往往具有重要意义。此外，据我们所知，这是SD中第一个UQ模型，其中包括任意性和认知不确定性。

##### URL
[http://arxiv.org/abs/1802.04742](http://arxiv.org/abs/1802.04742)

##### PDF
[http://arxiv.org/pdf/1802.04742](http://arxiv.org/pdf/1802.04742)

