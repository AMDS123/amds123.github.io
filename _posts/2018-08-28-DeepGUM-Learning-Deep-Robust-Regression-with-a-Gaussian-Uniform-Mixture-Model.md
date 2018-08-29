---
layout: post
title: "DeepGUM: Learning Deep Robust Regression with a Gaussian-Uniform Mixture Model"
date: 2018-08-28 10:32:43
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization Detection Gradient_Descent
author: St&#xe9;phane Lathuili&#xe8;re, Pablo Mesejo, Xavier Alameda-Pineda, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of how to robustly train a ConvNet for regression, or deep robust regression. Traditionally, deep regression employs the L2 loss function, known to be sensitive to outliers, i.e. samples that either lie at an abnormal distance away from the majority of the training samples, or that correspond to wrongly annotated targets. This means that, during back-propagation, outliers may bias the training process due to the high magnitude of their gradient. In this paper, we propose DeepGUM: a deep regression model that is robust to outliers thanks to the use of a Gaussian-uniform mixture model. We derive an optimization algorithm that alternates between the unsupervised detection of outliers using expectation-maximization, and the supervised training with cleaned samples using stochastic gradient descent. DeepGUM is able to adapt to a continuously evolving outlier distribution, avoiding to manually impose any threshold on the proportion of outliers in the training set. Extensive experimental evaluations on four different tasks (facial and fashion landmark detection, age and head pose estimation) lead us to conclude that our novel robust technique provides reliability in the presence of various types of noise and protection against a high percentage of outliers.

##### Abstract (translated by Google)
在本文中，我们解决了如何稳健地训练ConvNet进行回归或深度稳健回归的问题。传统上，深度回归采用L2损失函数，已知对异常值敏感，即，样本位于远离大多数训练样本的异常距离处，或者对应于错误注释的目标。这意味着，在反向传播期间，异常值可能由于其梯度的高幅度而偏向训练过程。在本文中，我们提出了DeepGUM：一种深度回归模型，由于使用了高斯均匀混合模型，它对异常值具有鲁棒性。我们推导出一种优化算法，该算法在使用期望最大化的无监督检测异常值和使用随机梯度下降的清洁样本的监督训练之间进行交替。 DeepGUM能够适应不断变化的异常值分布，避免手动对训练集中异常值的比例施加任何阈值。针对四种不同任务（面部和时尚地标检测，年龄和头部姿态估计）的广泛实验评估使我们得出结论，我们的新型鲁棒技术在存在各种类型的噪声的情况下提供可靠性并且针对高百分比的异常值提供保护。

##### URL
[http://arxiv.org/abs/1808.09211](http://arxiv.org/abs/1808.09211)

##### PDF
[http://arxiv.org/pdf/1808.09211](http://arxiv.org/pdf/1808.09211)

