---
layout: post
title: "Deep Multi-View Learning with Stochastic Decorrelation Loss"
date: 2017-07-30 20:53:54
categories: arXiv_CV
tags: arXiv_CV Embedding Represenation_Learning Relation Recognition
author: Xiaobin Chang, Tao Xiang, Timothy M. Hospedales
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view learning aims to learn an embedding space where multiple views are either maximally correlated for cross-view recognition, or decorrelated for latent factor disentanglement. A key challenge for deep multi-view representation learning is scalability. To correlate or decorrelate multi-view signals, the covariance of the whole training set should be computed which does not fit well with the mini-batch based training strategy, and moreover (de)correlation should be done in a way that is free of SVD-based computation in order to scale to contemporary layer sizes. In this work, a unified approach is proposed for efficient and scalable deep multi-view learning. Specifically, a mini-batch based Stochastic Decorrelation Loss (SDL) is proposed which can be applied to any network layer to provide soft decorrelation of the layer's activations. This reveals the connection between deep multi-view learning models such as Deep Canonical Correlation Analysis (DCCA) and Factorisation Autoencoder (FAE), and allows them to be easily implemented. We further show that SDL is superior to other decorrelation losses in terms of efficacy and scalability.

##### Abstract (translated by Google)
多视点学习的目的是要学习一个嵌入空间，其中多个视图或者是交叉视图识别的最大相关性，或者是与潜在因子解缠相关的解相关性。深度多视图表示学习的关键挑战是可伸缩性。为了使多视图信号相关或解相关，应当计算整个训练集的协方差，其不适合基于小批量的训练策略，而且（去）相关应该以没有SVD的方式进行为基础的计算，以缩放到当代图层大小。在这项工作中，提出了一个统一的方法来实现高效，可扩展的深度多视角学习。具体而言，提出了一种基于小批量的随机相关损失（SDL），其可以应用于任何网络层以提供层的激活的软解相关。这揭示了Deep Canonical Correlation Analysis（DCCA）和Factorisation Autoencoder（FAE）等深度多视图学习模型之间的联系，并且使它们易于实现。我们进一步表明SDL在功效和可扩展性方面优于其他解相关损失。

##### URL
[https://arxiv.org/abs/1707.09669](https://arxiv.org/abs/1707.09669)

##### PDF
[https://arxiv.org/pdf/1707.09669](https://arxiv.org/pdf/1707.09669)

