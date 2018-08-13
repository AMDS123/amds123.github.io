---
layout: post
title: "Dropout is a special case of the stochastic delta rule: faster and more accurate deep learning"
date: 2018-08-10 15:06:05
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction
author: Noah Frazier-Logue, Stephen Jos&#xe9; Hanson
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-layer neural networks have lead to remarkable performance on many kinds of benchmark tasks in text, speech and image processing. Nonlinear parameter estimation in hierarchical models is known to be subject to overfitting. One approach to this overfitting and related problems (local minima, colinearity, feature discovery etc.) is called dropout (Srivastava, et al 2014, Baldi et al 2016). This method removes hidden units with a Bernoulli random variable with probability $p$ over updates. In this paper we will show that Dropout is a special case of a more general model published originally in 1990 called the stochastic delta rule ( SDR, Hanson, 1990). SDR parameterizes each weight in the network as a random variable with mean $\mu_{w_{ij}}$ and standard deviation $\sigma_{w_{ij}}$. These random variables are sampled on each forward activation, consequently creating an exponential number of potential networks with shared weights. Both parameters are updated according to prediction error, thus implementing weight noise injections that reflect a local history of prediction error and efficient model averaging. SDR therefore implements a local gradient-dependent simulated annealing per weight converging to a bayes optimal network. Tests on standard benchmarks (CIFAR) using a modified version of DenseNet shows the SDR outperforms standard dropout in error by over 50% and in loss by over 50%. Furthermore, the SDR implementation converges on a solution much faster, reaching a training error of 5 in just 15 epochs with DenseNet-40 compared to standard DenseNet-40's 94 epochs.

##### Abstract (translated by Google)
多层神经网络在文本，语音和图像处理等多种基准任务中表现出色。已知分层模型中的非线性参数估计会过度拟合。这种过度拟合和相关问题（局部最小值，共线性，特征发现等）的一种方法称为丢失（Srivastava，et al 2014，Baldi et al 2016）。此方法使用Bernoulli随机变量删除隐藏单元，其中更新概率为$ p $。在本文中，我们将展示Dropout是最初在1990年发布的更为通用模型的特例，称为随机delta规则（SDR，Hanson，1990）。 SDR将网络中的每个权重参数化为随机变量，平均值为$ \ mu_ {w_ {ij}} $和标准差$ \ sigma_ {w_ {ij}} $。在每次前向激活时对这些随机变量进行采样，从而创建具有共享权重的指数数量的潜在网络。根据预测误差更新两个参数，从而实现反映预测误差的局部历史和有效模型平均的权重噪声注入。因此，SDR实现了每个权重的局部梯度相关模拟退火，其收敛到贝叶斯最优网络。使用DenseNet的修改版本对标准基准测试（CIFAR）进行的测试表明，SDR的误差超过标准压差超过50％，损失超过50％。此外，SDR实施更快地收敛于解决方案，与标准DenseNet-40的94个时期相比，使用DenseNet-40在15个时期内达到5的训练误差。

##### URL
[http://arxiv.org/abs/1808.03578](http://arxiv.org/abs/1808.03578)

##### PDF
[http://arxiv.org/pdf/1808.03578](http://arxiv.org/pdf/1808.03578)

