---
layout: post
title: "Understanding Batch Normalization"
date: 2018-06-01 03:57:56
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning
author: Johan Bjorck, Carla Gomes, Bart Selman
mathjax: true
---

* content
{:toc}

##### Abstract
Batch normalization is a ubiquitous deep learning technique that normalizes activations in intermediate layers. It is associated with improved accuracy and faster learning, but despite its enormous success there is little consensus regarding why it works. We aim to rectify this and take an empirical approach to understanding batch normalization. Our primary observation is that the higher learning rates that batch normalization enables have a regularizing effect that dramatically improves generalization of normalized networks, which is both demonstrated empirically and motivated theoretically. We show how activations become large and how the convolutional channels become increasingly ill-behaved for layers deep in unnormalized networks, and how this results in larger input-independent gradients. Beyond just gradient scaling, we demonstrate how the learning rate in unnormalized networks is further limited by the magnitude of activations growing exponentially with network depth for large parameter updates, a problem batch normalization trivially avoids. Motivated by recent results in random matrix theory, we argue that ill-conditioning of the activations is due to fluctuations in random initialization, shedding new light on classical initialization schemes and their consequences.

##### Abstract (translated by Google)
批量标准化是一种无处不在的深度学习技术，可以使中间层中的激活正常化。它与改进的准确性和更快的学习有关，但尽管取得了巨大的成功，但它为什么没有达成共识。我们的目标是纠正这一点，并采取经验方法来理解批量标准化。我们的主要观察结果是，批量归一化所带来的较高学习率具有正常化效应，这极大地改善了规范化网络的泛化，这在理论上是经验性的和动机性的。我们展示激活如何变大，以及卷积通道如何在非规范化网络中变得越来越不健康，以及如何导致更大的与输入无关的梯度。除了梯度缩放之外，我们还演示了未规模化网络中的学习速率如何进一步受激活量的大小的影响，这些激活量随着大参数更新的网络深度呈指数级增长，这种批量规范化可以避免的问题。最近随机矩阵理论的结果激发了我们的观点，认为激活的不适应是由随机初始化的波动引起的，这为传统初始化方案及其后果揭开了新的曙光。

##### URL
[http://arxiv.org/abs/1806.02375](http://arxiv.org/abs/1806.02375)

##### PDF
[http://arxiv.org/pdf/1806.02375](http://arxiv.org/pdf/1806.02375)

