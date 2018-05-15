---
layout: post
title: "Spatial Uncertainty Sampling for End-to-End Control"
date: 2018-05-13 06:19:14
categories: arXiv_RO
tags: arXiv_RO Inference Deep_Learning Relation
author: Alexander Amini, Ava Soleimany, Sertac Karaman, Daniela Rus
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end trained neural networks (NNs) are a compelling approach to autonomous vehicle control because of their ability to learn complex tasks without manual engineering of rule-based decisions. However, challenging road conditions, ambiguous navigation situations, and safety considerations require reliable uncertainty estimation for the eventual adoption of full-scale autonomous vehicles. Bayesian deep learning approaches provide a way to estimate uncertainty by approximating the posterior distribution of weights given a set of training data. Dropout training in deep NNs approximates Bayesian inference in a deep Gaussian process and can thus be used to estimate model uncertainty. In this paper, we propose a Bayesian NN for end-to-end control that estimates uncertainty by exploiting feature map correlation during training. This approach achieves improved model fits, as well as tighter uncertainty estimates, than traditional element-wise dropout. We evaluate our algorithms on a challenging dataset collected over many different road types, times of day, and weather conditions, and demonstrate how uncertainties can be used in conjunction with a human controller in a parallel autonomous setting.

##### Abstract (translated by Google)
端到端训练的神经网络（NN）是自主车辆控制的一种引人注目的方法，因为它能够学习复杂的任务而无需手动设计基于规则的决策。然而，具有挑战性的道路状况，模糊的导航情况和安全考虑因素需要对最终采用全面自动驾驶车辆进行可靠的不确定性评估。贝叶斯深度学习方法提供了一种通过逼近给定一组训练数据的权重的后验分布来估计不确定性的方法。深度神经网络中的丢失训练逼近了深度高斯过程中的贝叶斯推理，因此可用于估计模型不确定性。在本文中，我们提出了一种用于端到端控制的贝叶斯神经网络，通过在训练期间利用特征映射相关来估计不确定性。与传统的基于元素的丢失相比，这种方法实现了改进的模型拟合以及更严格的不确定性估计。我们根据多种不同道路类型，一天中的时间和天气情况收集的具有挑战性的数据集评估我们的算法，并演示在并行自主环境中如何将不确定性与人工控制器结合使用。

##### URL
[http://arxiv.org/abs/1805.04829](http://arxiv.org/abs/1805.04829)

##### PDF
[http://arxiv.org/pdf/1805.04829](http://arxiv.org/pdf/1805.04829)

