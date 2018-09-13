---
layout: post
title: "Temporal Pattern Attention for Multivariate Time Series Forecasting"
date: 2018-09-12 00:40:40
categories: arXiv_CL
tags: arXiv_CL Review Attention RNN Prediction
author: Shun-Yao Shih, Fan-Keng Sun, Hung-yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Forecasting multivariate time series data, such as prediction of electricity consumption, solar power production, and polyphonic piano pieces, has numerous valuable applications. However, complex and non-linear interdependencies between time steps and series complicate the task. To obtain accurate prediction, it is crucial to model long-term dependency in time series data, which can be achieved to some good extent by recurrent neural network (RNN) with attention mechanism. Typical attention mechanism reviews the information at each previous time step and selects the relevant information to help generate the outputs, but it fails to capture the temporal patterns across multiple time steps. In this paper, we propose to use a set of filters to extract time-invariant temporal patterns, which is similar to transforming time series data into its "frequency domain". Then we proposed a novel attention mechanism to select relevant time series, and use its "frequency domain" information for forecasting. We applied the proposed model on several real-world tasks and achieved the state-of-the-art performance in all of them with only one exception. We also show that to some degree the learned filters play the role of bases in discrete Fourier transform.

##### Abstract (translated by Google)
预测多变量时间序列数据，例如电力消耗预测，太阳能发电和复调钢琴件，具有许多有价值的应用。然而，时间步骤和序列之间的复杂和非线性相互依赖性使任务复杂化。为了获得准确的预测，对时间序列数据中的长期依赖性建模至关重要，这可以通过具有注意机制的递归神经网络（RNN）在一定程度上实现。典型的注意机制在每个先前时间步骤检查信息并选择相关信息以帮助生成输出，但是它无法捕获跨多个时间步骤的时间模式。在本文中，我们建议使用一组滤波器来提取时不变的时间模式，这类似于将时间序列数据转换为其“频域”。然后我们提出了一种新的注意机制来选择相关的时间序列，并使用其“频域”信息进行预测。我们将所提出的模型应用于几个现实世界的任务，并在所有这些任务中实现了最先进的性能，只有一个例外。我们还表明，在某种程度上，学习过滤器在离散傅里叶变换中起着基础的作用。

##### URL
[http://arxiv.org/abs/1809.04206](http://arxiv.org/abs/1809.04206)

##### PDF
[http://arxiv.org/pdf/1809.04206](http://arxiv.org/pdf/1809.04206)

