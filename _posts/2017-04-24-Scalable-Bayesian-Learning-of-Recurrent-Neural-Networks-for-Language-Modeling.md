---
layout: post
title: "Scalable Bayesian Learning of Recurrent Neural Networks for Language Modeling"
date: 2017-04-24 15:32:49
categories: arXiv_CL
tags: arXiv_CL Optimization RNN Language_Model
author: Zhe Gan, Chunyuan Li, Changyou Chen, Yunchen Pu, Qinliang Su, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have shown promising performance for language modeling. However, traditional training of RNNs using back-propagation through time often suffers from overfitting. One reason for this is that stochastic optimization (used for large training sets) does not provide good estimates of model uncertainty. This paper leverages recent advances in stochastic gradient Markov Chain Monte Carlo (also appropriate for large training sets) to learn weight uncertainty in RNNs. It yields a principled Bayesian learning algorithm, adding gradient noise during training (enhancing exploration of the model-parameter space) and model averaging when testing. Extensive experiments on various RNN models and across a broad range of applications demonstrate the superiority of the proposed approach over stochastic optimization.

##### Abstract (translated by Google)
递归神经网络（RNN）在语言建模上表现出有希望的性能。然而，传统的使用时间反向传播的RNN训练经常遭受过度拟合。其中一个原因是，随机优化（用于大型训练集）不能提供模型不确定性的良好估计。本文利用随机梯度马尔可夫链蒙特卡罗（也适用于大型训练集）的最新进展来学习RNN中的权重不确定性。它产生一个有原则的贝叶斯学习算法，在训练期间增加梯度噪声（增强对模型参数空间的探索），并在测试时进行模型平均。对各种RNN模型和广泛的应用进行广泛的实验证明了所提出的方法优于随机优化的优越性。

##### URL
[https://arxiv.org/abs/1611.08034](https://arxiv.org/abs/1611.08034)

##### PDF
[https://arxiv.org/pdf/1611.08034](https://arxiv.org/pdf/1611.08034)

