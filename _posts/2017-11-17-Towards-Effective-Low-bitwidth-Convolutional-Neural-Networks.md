---
layout: post
title: "Towards Effective Low-bitwidth Convolutional Neural Networks"
date: 2017-11-17 01:35:27
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Bohan Zhuang, Chunhua Shen, Mingkui Tan, Lingqiao Liu, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tackles the problem of training a deep convolutional neural network with both low-precision weights and low-bitwidth activations. Optimizing a low-precision network is very challenging since the training process can easily get trapped in a poor local minima, which results in substantial accuracy loss. To mitigate this problem, we propose three simple-yet-effective approaches to improve the network training. First, we propose to use a two-stage optimization strategy to progressively find good local minima. Specifically, we propose to first optimize a net with quantized weights and then quantized activations. This is in contrast to the traditional methods which optimize them simultaneously. Second, following a similar spirit of the first method, we propose another progressive optimization approach which progressively decreases the bit-width from high-precision to low-precision during the course of training. Third, we adopt a novel learning scheme to jointly train a full-precision model alongside the low-precision one. By doing so, the full-precision model provides hints to guide the low-precision model training. Extensive experiments on various datasets ( i.e., CIFAR-100 and ImageNet) show the effectiveness of the proposed methods. To highlight, using our methods to train a 4-bit precision network leads to no performance decrease in comparison with its full-precision counterpart with standard network architectures ( i.e., AlexNet and ResNet-50).

##### Abstract (translated by Google)
本文解决了训练低精度权重和低位激活的深度卷积神经网络的问题。优化低精度网络是非常具有挑战性的，因为训练过程很容易陷入局部极小的情况，从而导致严重的精度损失。为了缓解这个问题，我们提出了三个简单而有效的方法来改善网络培训。首先，我们建议使用两阶段优化策略逐步找到良好的局部最小值。具体来说，我们建议先量化权重，然后量化激活。这与同时优化它们的传统方法相反。其次，遵循第一种方法的类似精神，我们提出了另一种渐进式优化方法，在训练过程中逐步将比特宽度从高精度降低到低精度。第三，我们采用了一种新颖的学习方案，与低精度模型一起共同训练一个全精度模型。通过这样做，全精度模型提供了指导低精度模型训练的线索。对各种数据集（即CIFAR-100和ImageNet）的大量实验显示了所提出的方法的有效性。为了突出显示，使用我们的方法来训练一个4位精度的网络，与带有标准网络体系结构（即AlexNet和ResNet-50）的全精度网络相比，性能没有下降。

##### URL
[https://arxiv.org/abs/1711.00205](https://arxiv.org/abs/1711.00205)

##### PDF
[https://arxiv.org/pdf/1711.00205](https://arxiv.org/pdf/1711.00205)

