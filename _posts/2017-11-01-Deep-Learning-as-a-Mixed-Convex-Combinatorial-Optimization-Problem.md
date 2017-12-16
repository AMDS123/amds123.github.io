---
layout: post
title: "Deep Learning as a Mixed Convex-Combinatorial Optimization Problem"
date: 2017-11-01 17:58:16
categories: arXiv_CV
tags: arXiv_CV Optimization Classification Deep_Learning Gradient_Descent
author: Abram L. Friesen, Pedro Domingos
mathjax: true
---

* content
{:toc}

##### Abstract
As neural networks grow deeper and wider, learning networks with hard-threshold activations is becoming increasingly important, both for network quantization, which can drastically reduce time and energy requirements, and for creating large integrated systems of deep networks, which may have non-differentiable components and must avoid vanishing and exploding gradients for effective learning. However, since gradient descent is not applicable to hard-threshold functions, it is not clear how to learn them in a principled way. We address this problem by observing that setting targets for hard-threshold hidden units in order to minimize loss is a discrete optimization problem, and can be solved as such. The discrete optimization goal is to find a set of targets such that each unit, including the output, has a linearly separable problem to solve. Given these targets, the network decomposes into individual perceptrons, which can then be learned with standard convex approaches. Based on this, we develop a recursive mini-batch algorithm for learning deep hard-threshold networks that includes the popular but poorly justified straight-through estimator as a special case. Empirically, we show that our algorithm improves classification accuracy in a number of settings, including for AlexNet and ResNet-18 on ImageNet, when compared to the straight-through estimator.

##### Abstract (translated by Google)
随着神经网络越来越深入，具有硬阈值激活的学习网络变得越来越重要，既可以用于网络量化，这可以大大减少时间和能量需求，并且可以创建可能具有不可微分的深度网络的大集成系统组件，并且必须避免消失和爆炸渐变有效的学习。但是，由于梯度下降不适用于硬阈值函数，因此如何以原则的方式学习梯度下降并不明确。我们通过观察硬门限隐藏单元的设置目标以使损失最小化是一个离散优化问题来解决这个问题，并且可以这样解决。离散优化目标是找到一组目标，使得包括输出在内的每个单元都有可解决的线性分离问题。给定这些目标，网络分解成单独的感知器，然后可以用标准的凸面方法学习。在此基础上，我们开发了一个递归的小批量算法，用于学习深度硬阈值网络，其中包括流行的但是不合理的直通式估计器作为特例。通过实证，我们发现，与直通式估计器相比，我们的算法在许多设置中提高了分类准确性，包括ImageNet上的AlexNet和ResNet-18。

##### URL
[https://arxiv.org/abs/1710.11573](https://arxiv.org/abs/1710.11573)

##### PDF
[https://arxiv.org/pdf/1710.11573](https://arxiv.org/pdf/1710.11573)

