---
layout: post
title: "Accelerating Neural Architecture Search using Performance Prediction"
date: 2017-11-08 16:09:35
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Optimization Classification Language_Model Prediction
author: Bowen Baker, Otkrist Gupta, Ramesh Raskar, Nikhil Naik
mathjax: true
---

* content
{:toc}

##### Abstract
Methods for neural network hyperparameter optimization and meta-modeling are computationally expensive due to the need to train a large number of model configurations. In this paper, we show that standard frequentist regression models can predict the final performance of partially trained model configurations using features based on network architectures, hyperparameters, and time-series validation performance data. We empirically show that our performance prediction models are much more effective than prominent Bayesian counterparts, are simpler to implement, and are faster to train. Our models can predict final performance in both visual classification and language modeling domains, are effective for predicting performance of drastically varying model architectures, and can even generalize between model classes. Using these prediction models, we also propose an early stopping method for hyperparameter optimization and meta-modeling, which obtains a speedup of a factor up to 6x in both hyperparameter optimization and meta-modeling. Finally, we empirically show that our early stopping method can be seamlessly incorporated into both reinforcement learning-based architecture selection algorithms and bandit based search methods. Through extensive experimentation, we empirically show our performance prediction models and early stopping algorithm are state-of-the-art in terms of prediction accuracy and speedup achieved while still identifying the optimal model configurations.

##### Abstract (translated by Google)
神经网络超参数优化和元建模的方法在计算上是昂贵的，因为需要训练大量的模型配置。在本文中，我们展示标准频率主义回归模型可以使用基于网络体系结构，超参数和时间序列验证性能数据的特征来预测部分训练的模型配置的最终性能。我们经验地表明，我们的性能预测模型比着名的贝叶斯算法效率更高，实施起来更简单，训练速度也更快。我们的模型可以预测视觉分类和语言建模领域的最终性能，对于预测急剧变化的模型体系结构的性能是有效的，甚至可以在模型类别之间进行概括。使用这些预测模型，我们还提出了一种超参数优化和元建模的早期停止方法，在超参数优化和元建模方面获得了高达6倍的加速因子。最后，我们凭经验证明，我们的早期停止方法可以无缝地结合到基于强化学习的架构选择算法和基于匪的搜索方法中。通过大量的实验，我们凭经验证明了我们的性能预测模型和早期停止算法在预测精度和加速性方面都是最先进的，同时仍然确定最优模型配置。

##### URL
[https://arxiv.org/abs/1705.10823](https://arxiv.org/abs/1705.10823)

##### PDF
[https://arxiv.org/pdf/1705.10823](https://arxiv.org/pdf/1705.10823)

