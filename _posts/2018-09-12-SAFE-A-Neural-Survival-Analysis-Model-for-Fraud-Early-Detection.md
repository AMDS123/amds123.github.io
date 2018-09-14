---
layout: post
title: "SAFE: A Neural Survival Analysis Model for Fraud Early Detection"
date: 2018-09-12 21:28:26
categories: arXiv_AI
tags: arXiv_AI RNN Classification Prediction Detection
author: Panpan Zheng, Shuhan Yuan, Xintao Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Many online platforms have deployed anti-fraud systems to detect and prevent fraudster activities. However, there is usually a gap between the time that a user commits a fraudulent action and the time that the user is suspended by the platform. How to detect fraudsters in time is a challenging problem. Most of the existing approaches adopt classifiers to predict fraudsters given their activity sequences along time. The main drawback of classification models is that the prediction results between consecutive timestamps are often inconsistent. In this paper, we propose a survival analysis based fraud early detection model, SAFE, that maps dynamic user activities to survival probabilities that are guaranteed to be monotonically decreasing along time. SAFE adopts recurrent neural network (RNN) to handle user activity sequences and directly outputs hazard values at each timestamp, and then, survival probability derived from hazard values is deployed to achieve consistent predictions. Because we only observe in the training data the user suspended time instead of the fraudulent activity time, we revise the loss function of the regular survival model to achieve fraud early detection. Experimental results on two real world datasets demonstrate that SAFE outperforms both the survival analysis model and recurrent neural network model alone as well as state-of-the-art fraud early detection approaches.

##### Abstract (translated by Google)
许多在线平台已部署反欺诈系统来检测和防止欺诈活动。但是，用户提交欺诈行为的时间与用户被平台暂停的时间之间通常存在差距。如何及时发现欺诈者是一个具有挑战性的问题。大多数现有方法采用分类器来预测欺诈者随时间推移的活动顺序。分类模型的主要缺点是连续时间戳之间的预测结果通常是不一致的。在本文中，我们提出了一种基于生存分析的欺诈早期检测模型SAFE，它将动态用户活动映射到保证随时间单调递减的生存概率。 SAFE采用递归神经网络（RNN）处理用户活动序列，并在每个时间戳直接输出危险值，然后，部署从危险值导出的生存概率，以实现一致的预测。因为我们只在训练数据中观察用户暂停时间而不是欺诈活动时间，我们修改了常规生存模型的损失函数以实现欺诈早期检测。两个真实世界数据集的实验结果表明，SAFE优于单独的生存分析模型和复现神经网络模型以及最先进的欺诈早期检测方法。

##### URL
[http://arxiv.org/abs/1809.04683](http://arxiv.org/abs/1809.04683)

##### PDF
[http://arxiv.org/pdf/1809.04683](http://arxiv.org/pdf/1809.04683)

