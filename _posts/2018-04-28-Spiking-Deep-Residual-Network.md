---
layout: post
title: "Spiking Deep Residual Network"
date: 2018-04-28 06:44:13
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Yangfan Hu, Huajin Tang, Yueming Wang, Gang Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, spiking neural network (SNN) has received significant attentions for its biological plausibility. SNN theoretically has at least the same computational power as traditional artificial neural networks (ANNs), and it has the potential to achieve revolutionary energy-efficiency. However, at current stage, it is still a big challenge to train a very deep SNN. In this paper, we propose an efficient approach to build a spiking version of deep residual network (ResNet), which represents the state-of-the-art convolutional neural networks (CNNs). We employ the idea of converting a trained ResNet to a network of spiking neurons named Spiking ResNet. To address the conversion problem, we propose a shortcut normalisation mechanism to appropriately scale continuous-valued activations to match firing rates in SNN, and a layer-wise error compensation approach to reduce the error caused by discretisation. Experimental results on MNIST, CIFAR-10, and CIFAR-100 demonstrate that the proposed Spiking ResNet yields the state-of-the-art performance of SNNs.

##### Abstract (translated by Google)
最近，尖峰神经网络（SNN）因其生物合理性受到了重大关注。理论上SNN至少具有与传统人工神经网络（ANN）相同的计算能力，并且它有可能实现革命性的能量效率。然而，在现阶段，培养一个非常深的SNN仍然是一个巨大的挑战。在本文中，我们提出了一种有效的方法来构建代表最先进的卷积神经网络（CNN）的深度残留网络（ResNet）的尖峰版本。我们采用将经过训练的ResNet转换为Spiking神经元网络Spiking ResNet的想法。为了解决转换问题，我们提出了一种快捷标准化机制来适当缩放连续值激活以匹配SNN中的发射速率，以及一种逐层误差补偿方法来减少由离散导致的误差。在MNIST，CIFAR-10和CIFAR-100上的实验结果证明了所提出的Spiking ResNet能够产生SNN的最新性能。

##### URL
[http://arxiv.org/abs/1805.01352](http://arxiv.org/abs/1805.01352)

##### PDF
[http://arxiv.org/pdf/1805.01352](http://arxiv.org/pdf/1805.01352)

