---
layout: post
title: "Mitigating Unwanted Biases with Adversarial Learning"
date: 2018-01-22 06:45:23
categories: arXiv_AI
tags: arXiv_AI Adversarial Classification Prediction
author: Brian Hu Zhang, Blake Lemoine, Margaret Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning is a tool for building models that accurately represent input training data. When undesired biases concerning demographic groups are in the training data, well-trained models will reflect those biases. We present a framework for mitigating such biases by including a variable for the group of interest and simultaneously learning a predictor and an adversary. The input to the network X, here text or census data, produces a prediction Y, such as an analogy completion or income bracket, while the adversary tries to model a protected variable Z, here gender or zip code. 
 The objective is to maximize the predictor's ability to predict Y while minimizing the adversary's ability to predict Z. Applied to analogy completion, this method results in accurate predictions that exhibit less evidence of stereotyping Z. When applied to a classification task using the UCI Adult (Census) Dataset, it results in a predictive model that does not lose much accuracy while achieving very close to equality of odds (Hardt, et al., 2016). The method is flexible and applicable to multiple definitions of fairness as well as a wide range of gradient-based learning models, including both regression and classification tasks.

##### Abstract (translated by Google)
机器学习是建立准确表示输入训练数据的模型的工具。当训练数据中有关人口群体的不良偏见时，训练有素的模型将反映这些偏见。我们提出了一个减轻这种偏见的框架，为这个群体加入一个变量，同时学习一个预测变量和一个对手。网络X（这里是文本或人口普查数据）的输入产生一个预测Y，比如类比完成或收入支架，而对手则试图模拟受保护的变量Z，这里是性别或邮政编码。
 目标是最大化预测者预测Y的能力，同时使对手预测Z的能力最小。应用于类比完成，这种方法导致准确的预测，表现出较少的刻板Z的证据。当应用于使用UCI的分类任务时，人口普查）数据集，它导致了一个预测模型，在达到非常接近平等的几率时，不会失去太多的准确性（Hardt，et al。，2016）。该方法是灵活的，适用于公平性的多重定义以及广泛的基于梯度的学习模型，包括回归和分类任务。

##### URL
[http://arxiv.org/abs/1801.07593](http://arxiv.org/abs/1801.07593)

##### PDF
[http://arxiv.org/pdf/1801.07593](http://arxiv.org/pdf/1801.07593)

