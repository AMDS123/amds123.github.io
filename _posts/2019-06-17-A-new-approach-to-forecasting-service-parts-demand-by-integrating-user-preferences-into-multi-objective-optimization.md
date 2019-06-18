---
layout: post
title: "A new approach to forecasting service parts demand by integrating user preferences into multi-objective optimization"
date: 2019-06-17 02:00:09
categories: arXiv_AI
tags: arXiv_AI Optimization RNN Gradient_Descent
author: Wenli Ouyang
mathjax: true
---

* content
{:toc}

##### Abstract
Service supply chain management is to prepare spare parts for failed products under warranty. Their goal is to reach agreed service level at the minimum cost. We convert this business problem into a preference based multi-objective optimization problem, where two quality criteria must be simultaneously optimized. One criterion is accuracy of demand forecast and the other is service level. Here we propose a general framework supporting solving preference-based multi-objective optimization problems (MOPs) by multi-gradient descent algorithm (MGDA), which is well suited for training deep neural network. The proposed framework is able to treat agreed service level as a constrained criterion that must be met and generate a Pareto-optimal solution with highest forecasting accuracy. The neural networks used here are two Encoder-Decoder LSTM modes: one is used for pre-training phase to learn distributed representation of former generations' service parts consumption data, and the other is used for supervised learning phase to generate forecast quantities of current generations' service parts. Evaluated under the service parts consumption data in Lenovo Group Ltd, the proposed method clearly outperform baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06816](http://arxiv.org/abs/1906.06816)

##### PDF
[http://arxiv.org/pdf/1906.06816](http://arxiv.org/pdf/1906.06816)

