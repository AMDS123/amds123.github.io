---
layout: post
title: "Hybrid Gradient Boosting Trees and Neural Networks for Forecasting Operating Room Data"
date: 2018-01-24 02:11:40
categories: arXiv_AI
tags: arXiv_AI Represenation_Learning RNN Prediction Memory_Networks
author: Hugh Chen, Scott Lundberg, Su-In Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Time series data constitutes a distinct and growing problem in machine learning. As the corpus of time series data grows larger, deep models that simultaneously learn features and classify with these features can be intractable or suboptimal. In this paper, we present feature learning via long short term memory (LSTM) networks and prediction via gradient boosting trees (XGB). Focusing on the consequential setting of electronic health record data, we predict the occurrence of hypoxemia five minutes into the future based on past features. We make two observations: 1) long short term memory networks are effective at capturing long term dependencies based on a single feature and 2) gradient boosting trees are capable of tractably combining a large number of features including static features like height and weight. With these observations in mind, we generate features by performing "supervised" representation learning with LSTM networks. Augmenting the original XGB model with these features gives significantly better performance than either individual method.

##### Abstract (translated by Google)
时间序列数据在机器学习中构成了一个明显且日益增长的问题随着时间序列数据的语料越来越大，同时学习特征和使用这些特征进行分类的深层模型可能是棘手的或者是不理想的。在本文中，我们通过长期短期记忆（LSTM）网络展示特征学习，并通过梯度提升树（XGB）进行预测。关注电子健康记录数据的相应设置，根据以往的特点，预测未来5分钟内发生低氧血症的情况。我们做了两个观察：1）长期的短期记忆网络可以有效捕获基于单一特征的长期依赖性; 2）梯度增强树能够合理地组合大量的特征，包括高度和重量等静态特征。考虑到这些意见，我们通过使用LSTM网络执行“监督”表示学习来生成特征。使用这些特性增强原有的XGB模型比单独的方法具有更好的性能。

##### URL
[http://arxiv.org/abs/1801.07384](http://arxiv.org/abs/1801.07384)

##### PDF
[http://arxiv.org/pdf/1801.07384](http://arxiv.org/pdf/1801.07384)

