---
layout: post
title: "Estimating Heterogeneous Consumer Preferences for Restaurants and Travel Time Using Mobile Location Data"
date: 2018-01-22 23:55:42
categories: arXiv_AI
tags: arXiv_AI Inference Prediction Gradient_Descent
author: Susan Athey, David Blei, Robert Donnelly, Francisco Ruiz, Tobias Schmidt
mathjax: true
---

* content
{:toc}

##### Abstract
This paper analyzes consumer choices over lunchtime restaurants using data from a sample of several thousand anonymous mobile phone users in the San Francisco Bay Area. The data is used to identify users' approximate typical morning location, as well as their choices of lunchtime restaurants. We build a model where restaurants have latent characteristics (whose distribution may depend on restaurant observables, such as star ratings, food category, and price range), each user has preferences for these latent characteristics, and these preferences are heterogeneous across users. Similarly, each item has latent characteristics that describe users' willingness to travel to the restaurant, and each user has individual-specific preferences for those latent characteristics. Thus, both users' willingness to travel and their base utility for each restaurant vary across user-restaurant pairs. We use a Bayesian approach to estimation. To make the estimation computationally feasible, we rely on variational inference to approximate the posterior distribution, as well as stochastic gradient descent as a computational approach. Our model performs better than more standard competing models such as multinomial logit and nested logit models, in part due to the personalization of the estimates. We analyze how consumers re-allocate their demand after a restaurant closes to nearby restaurants versus more distant restaurants with similar characteristics, and we compare our predictions to actual outcomes. Finally, we show how the model can be used to analyze counterfactual questions such as what type of restaurant would attract the most consumers in a given location.

##### Abstract (translated by Google)
本文通过使用旧金山湾区数千名匿名手机用户的样本数据分析了消费者对午餐餐厅的选择。这些数据是用来识别用户的大致典型的早晨位置，以及他们的午餐餐厅的选择。我们建立了一个餐厅具有潜在特征（其分布可能取决于餐馆可观察性，如星级评定，食品类别和价格范围）的模型，每个用户对这些潜在特征具有偏好，并且这些偏好在用户之间是异构的。类似地，每个项目具有描述用户去餐馆的意愿的潜在特征，并且每个用户具有针对这些潜在特征的个人特定偏好。因此，不论用户餐厅对，两个用户的旅行意愿和他们对于每个餐厅的基本效用都是不同的。我们使用贝叶斯方法来估计。为了使估计在计算上可行，我们依靠变分推理来近似后验分布以及随机梯度下降作为计算方法。我们的模型比多标准竞争模型（比如多项logit模型和嵌套logit模型）表现更好，部分原因是估算的个性化。我们分析消费者在餐厅关闭后，如何重新分配他们的需求与附近的餐馆相比，具有相似特征的更远的餐厅，我们将我们的预测与实际结果进行比较。最后，我们展示了该模型如何被用来分析反事实问题，比如什么类型的餐馆会吸引给定地点的大多数消费者。

##### URL
[http://arxiv.org/abs/1801.07826](http://arxiv.org/abs/1801.07826)

##### PDF
[http://arxiv.org/pdf/1801.07826](http://arxiv.org/pdf/1801.07826)

