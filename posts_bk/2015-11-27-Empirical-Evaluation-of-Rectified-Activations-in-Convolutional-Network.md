---
layout: post
title: "Empirical Evaluation of Rectified Activations in Convolutional Network"
date: 2015-11-27 06:58:14
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Bing Xu, Naiyan Wang, Tianqi Chen, Mu Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we investigate the performance of different types of rectified activation functions in convolutional neural network: standard rectified linear unit (ReLU), leaky rectified linear unit (Leaky ReLU), parametric rectified linear unit (PReLU) and a new randomized leaky rectified linear units (RReLU). We evaluate these activation function on standard image classification task. Our experiments suggest that incorporating a non-zero slope for negative part in rectified activation units could consistently improve the results. Thus our findings are negative on the common belief that sparsity is the key of good performance in ReLU. Moreover, on small scale dataset, using deterministic negative slope or learning it are both prone to overfitting. They are not as effective as using their randomized counterpart. By using RReLU, we achieved 75.68\% accuracy on CIFAR-100 test set without multiple test or ensemble.

##### Abstract (translated by Google)
在本文中，我们研究了卷积神经网络中不同类型整流激活函数的性能：标准整流线性单元（ReLU），泄漏整流线性单元（Leaky ReLU），参数整流线性单元（PReLU）和新的随机泄漏整流线性单位（RRELU）。我们评估这些激活功能在标准图像分类任务。我们的实验表明，在整流激活单元中加入一个非零斜率的负值可以持续改善结果。因此，我们的发现是负面的，认为稀疏性是ReLU良好表现的关键。而且，在小规模数据集上，使用确定性负斜率或学习它们都容易过拟合。他们不如使用他们的随机对手有效。通过使用RReLU，我们在没有多重测试或集成的CIFAR-100测试集上达到了75.68％的精度。

##### URL
[https://arxiv.org/abs/1505.00853](https://arxiv.org/abs/1505.00853)

##### PDF
[https://arxiv.org/pdf/1505.00853](https://arxiv.org/pdf/1505.00853)

