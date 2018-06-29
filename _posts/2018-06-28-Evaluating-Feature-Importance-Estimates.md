---
layout: post
title: "Evaluating Feature Importance Estimates"
date: 2018-06-28 03:46:57
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Sara Hooker, Dumitru Erhan, Pieter-Jan Kindermans, Been Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the influence of a given feature to a model prediction is challenging. We introduce ROAR, RemOve And Retrain, a benchmark to evaluate the accuracy of interpretability methods that estimate input feature importance in deep neural networks. We remove a fraction of input features deemed to be most important according to each estimator and measure the change to the model accuracy upon retraining. The most accurate estimator will identify inputs as important whose removal causes the most damage to model performance relative to all other estimators. This evaluation produces thought-provoking results -- we find that several estimators are less accurate than a random assignment of feature importance. However, averaging a set of squared noisy estimators (a variant of a technique proposed by Smilkov et al. (2017)), leads to significant gains in accuracy for each method considered and far outperforms such a random guess.

##### Abstract (translated by Google)
估计给定特征对模型预测的影响是具有挑战性的。我们引入了ROAR，RemOve和Retrain，这是一个评估深度神经网络中输入特征重要性的可解释性方法的准确性的基准。根据每个估算器，我们删除一部分视为最重要的输入特征，并在再训练时测量模型精度的变化。最准确的估算器将识别输入为重要的，其去除对所有其他估算器的模型性能造成最大的损害。这种评估产生了令人深思的结果 - 我们发现几个估计器不如随机分配特征重要性那么准确。然而，平均一组平方噪声估计量（Smilkov等（2017）提出的一种技术的变体）导致每种方法的准确度显着提高，远远超过这种随机猜测。

##### URL
[http://arxiv.org/abs/1806.10758](http://arxiv.org/abs/1806.10758)

##### PDF
[http://arxiv.org/pdf/1806.10758](http://arxiv.org/pdf/1806.10758)

