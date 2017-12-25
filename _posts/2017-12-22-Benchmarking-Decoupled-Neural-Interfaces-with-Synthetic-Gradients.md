---
layout: post
title: "Benchmarking Decoupled Neural Interfaces with Synthetic Gradients"
date: 2017-12-22 06:28:28
categories: arXiv_CV
tags: arXiv_CV Face
author: Ekaba Bisong
mathjax: true
---

* content
{:toc}

##### Abstract
Artifical Neural Network are a particular class of learning system modeled after biological neural functions with an interesting penchant for Hebbian learning, that is "neurons that wire together, fire together". However, unlike their natural counterparts, artificial neural networks have a close and stringent coupling between the modules of neurons in the network. This coupling or locking imposes upon the network a strict and inflexible structure that prevent layers in the network from updating their weights until a full feed-forward and backward pass has occurred. Such a constraint though may have sufficed for a while, is now no longer feasible in the era of very-large-scale machine learning, coupled with the increased desire for parallelization of the learning process across multiple computing infrastructures. To solve this problem, synthetic gradients (SG) with decoupled neural interfaces (DNI) are introduced as a viable alternative to the backpropagation algorithm. This paper performs a speed benchmark to compare the speed and accuracy capabilities of SG-DNI as over to a standard neural interface using multilayer perceptron MLP. SG-DNI shows good promise, in that it not only captures the learning problem, it is also over 3-fold faster due to it asynchronous learning capabilities.

##### Abstract (translated by Google)
人工神经网络是一种以生物神经功能为模型的特殊类别的学习系统，具有对Hebbian学习的有趣倾向，即“连接在一起，共同起火的神经元”。然而，与自然对应物不同的是，人工神经网络在网络中的神经元模块之间具有紧密且严格的耦合。这种耦合或锁定对网络施加严格而不灵活的结构，以防止网络中的层更新其权重，直到发生完整的前馈和反向传递。这样的约束虽然可能已经足够，但现在在非常大规模的机器学习的时代已经不再可行，而且在多个计算基础设施之间对学习过程并行化的期望也越来越高。为了解决这个问题，引入具有解耦神经接口（DNI）的合成梯度（SG）作为反向传播算法的可行替代方案。本文执行速度基准，将SG-DNI的速度和准确性能力与使用多层感知器MLP的标准神经接口进行比较。 SG-DNI显示出良好的前景，它不仅捕捉到了学习问题，而且由于它的异步学习能力，它也快了3倍。

##### URL
[https://arxiv.org/abs/1712.08314](https://arxiv.org/abs/1712.08314)

##### PDF
[https://arxiv.org/pdf/1712.08314](https://arxiv.org/pdf/1712.08314)

