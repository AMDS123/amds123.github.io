---
layout: post
title: "STDP-based spiking deep convolutional neural networks for object recognition"
date: 2017-12-25 12:57:57
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Sparse CNN Deep_Learning Detection Recognition
author: Saeed Reza Kheradpisheh, Mohammad Ganjtabesh, Simon J Thorpe, Timoth&#xe9;e Masquelier
mathjax: true
---

* content
{:toc}

##### Abstract
Previous studies have shown that spike-timing-dependent plasticity (STDP) can be used in spiking neural networks (SNN) to extract visual features of low or intermediate complexity in an unsupervised manner. These studies, however, used relatively shallow architectures, and only one layer was trainable. Another line of research has demonstrated - using rate-based neural networks trained with back-propagation - that having many layers increases the recognition robustness, an approach known as deep learning. We thus designed a deep SNN, comprising several convolutional (trainable with STDP) and pooling layers. We used a temporal coding scheme where the most strongly activated neurons fire first, and less activated neurons fire later or not at all. The network was exposed to natural images. Thanks to STDP, neurons progressively learned features corresponding to prototypical patterns that were both salient and frequent. Only a few tens of examples per category were required and no label was needed. After learning, the complexity of the extracted features increased along the hierarchy, from edge detectors in the first layer to object prototypes in the last layer. Coding was very sparse, with only a few thousands spikes per image, and in some cases the object category could be reasonably well inferred from the activity of a single higher-order neuron. More generally, the activity of a few hundreds of such neurons contained robust category information, as demonstrated using a classifier on Caltech 101, ETH-80, and MNIST databases. We also demonstrate the superiority of STDP over other unsupervised techniques such as random crops (HMAX) or auto-encoders. Taken together, our results suggest that the combination of STDP with latency coding may be a key to understanding the way that the primate visual system learns, its remarkable processing speed and its low energy consumption.

##### Abstract (translated by Google)
以前的研究表明，尖峰时间相关可塑性（STDP）可用于峰值神经网络（SNN）以无监督的方式提取低或中等复杂度的视觉特征。然而，这些研究使用的是相对较浅的架构，只有一层是可训练的。另一线研究已经证明 - 使用基于速率的反向传播训练的神经网络 - 有许多层增加了识别鲁棒性，这种方法被称为深度学习。因此，我们设计了一个深度SNN，包括几个卷积（可训练的STDP）和汇聚层。我们使用了时间编码方案，其中最强烈激活的神经元先激发，较少激活的神经元晚激发或根本不激活。网络暴露于自然的图像。由于STDP，神经元逐渐学习了对应于典型模式的特征，这些模式既突出又频繁。每个类别只需要几十个例子，不需要标签。在学习之后，提取的特征的复杂度沿着层次增加，从第一层的边缘检测器到最后一层的对象原型。编码非常稀疏，每幅图像只有数千个尖峰，在某些情况下，可以从单个高阶神经元的活动中合理地推断出对象类别。更一般地，数百个这样的神经元的活动包含强健的类别信息，如使用加州理工学院101，ETH-80和MNIST数据库中的分类器所证明的。我们还证明了STDP优于其他无监督技术，如随机作物（HMAX）或自动编码器。总之，我们的研究结果表明，STDP与延迟编码的结合可能是理解灵长类动物视觉系统学习方式，其显着的处理速度和低能耗的关键。

##### URL
[http://arxiv.org/abs/1611.01421](http://arxiv.org/abs/1611.01421)

##### PDF
[http://arxiv.org/pdf/1611.01421](http://arxiv.org/pdf/1611.01421)

