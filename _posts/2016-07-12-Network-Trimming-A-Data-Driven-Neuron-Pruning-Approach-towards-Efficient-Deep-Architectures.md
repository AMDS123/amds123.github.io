---
layout: post
title: "Network Trimming: A Data-Driven Neuron Pruning Approach towards Efficient Deep Architectures"
date: 2016-07-12 07:43:01
categories: arXiv_CV
tags: arXiv_CV
author: Hengyuan Hu, Rui Peng, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art neural networks are getting deeper and wider. While their performance increases with the increasing number of layers and neurons, it is crucial to design an efficient deep architecture in order to reduce computational and memory costs. Designing an efficient neural network, however, is labor intensive requiring many experiments, and fine-tunings. In this paper, we introduce network trimming which iteratively optimizes the network by pruning unimportant neurons based on analysis of their outputs on a large dataset. Our algorithm is inspired by an observation that the outputs of a significant portion of neurons in a large network are mostly zero, regardless of what inputs the network received. These zero activation neurons are redundant, and can be removed without affecting the overall accuracy of the network. After pruning the zero activation neurons, we retrain the network using the weights before pruning as initialization. We alternate the pruning and retraining to further reduce zero activations in a network. Our experiments on the LeNet and VGG-16 show that we can achieve high compression ratio of parameters without losing or even achieving higher accuracy than the original network.

##### Abstract (translated by Google)
最先进的神经网络越来越广泛。虽然它们的性能随着层数和神经元数量的增加而增加，但为了降低计算和存储成本，设计高效的深层架构至关重要。然而，设计高效的神经网络需要大量劳动力，需要进行许多实验和微调。在本文中，我们介绍网络修整，它通过修剪不重要的神经元基于对大数据集的输出进行分析来迭代地优化网络。我们的算法受到观察的启发，即大型网络中大部分神经元的输出大多为零，而不管网络接收到什么输入。这些零激活神经元是多余的，可以在不影响网络整体准确性的情况下被移除。修剪零激活神经元之后，我们使用修剪之前的权重重新训练网络作为初始化。我们轮流修剪和再训练，以进一步减少网络中的零激活。我们在LeNet和VGG-16上进行的实验表明，我们可以实现参数的高压缩比，而不会损失甚至达到比原始网络更高的精度。

##### URL
[https://arxiv.org/abs/1607.03250](https://arxiv.org/abs/1607.03250)

##### PDF
[https://arxiv.org/pdf/1607.03250](https://arxiv.org/pdf/1607.03250)

