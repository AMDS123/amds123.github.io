---
layout: post
title: "Incomplete Dot Products for Dynamic Computation Scaling in Neural Network Inference"
date: 2017-10-21 17:37:11
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Inference Classification
author: Bradley McDanel, Surat Teerapittayanon, H.T. Kung
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the use of incomplete dot products (IDP) to dynamically adjust the number of input channels used in each layer of a convolutional neural network during feedforward inference. IDP adds monotonically non-increasing coefficients, referred to as a "profile", to the channels during training. The profile orders the contribution of each channel in non-increasing order. At inference time, the number of channels used can be dynamically adjusted to trade off accuracy for lowered power consumption and reduced latency by selecting only a beginning subset of channels. This approach allows for a single network to dynamically scale over a computation range, as opposed to training and deploying multiple networks to support different levels of computation scaling. Additionally, we extend the notion to multiple profiles, each optimized for some specific range of computation scaling. We present experiments on the computation and accuracy trade-offs of IDP for popular image classification models and datasets. We demonstrate that, for MNIST and CIFAR-10, IDP reduces computation significantly, e.g., by 75%, without significantly compromising accuracy. We argue that IDP provides a convenient and effective means for devices to lower computation costs dynamically to reflect the current computation budget of the system. For example, VGG-16 with 50% IDP (using only the first 50% of channels) achieves 70% in accuracy on the CIFAR-10 dataset compared to the standard network which achieves only 35% accuracy when using the reduced channel set.

##### Abstract (translated by Google)
我们建议在前馈推断过程中使用不完全点积（IDP）来动态调整卷积神经网络每层中使用的输入通道的数量。 IDP在训练期间向信道添加单调不增加的系数（被称为“概况”）。配置文件以不增加的顺序排序每个通道的贡献。在推断时，可以动态地调整所使用的信道的数量，从而通过仅选择信道的开始子集来折衷精度以降低功耗并减少等待时间。这种方法允许单个网络动态扩展一个计算范围，而不是训练和部署多个网络来支持不同级别的计算缩放。此外，我们将这个概念扩展到多个配置文件，每个配置文件都针对特定的计算范围进行了优化。我们提出了流行的图像分类模型和数据集的IDP的计算和精度折衷的实验。我们证明，对于MNIST和CIFAR-10，IDP显着减少计算，例如减少75％，而不会显着降低准确性。我们认为，IDP为设备动态降低计算成本提供了一种方便有效的手段，以反映当前系统的计算预算。例如，与标准网络相比，具有50％IDP的VGG-16（仅使用前50％的通道）在CIFAR-10数据集上的准确度达到70％，而使用缩减通道集的标准网络仅达到35％的准确度。

##### URL
[https://arxiv.org/abs/1710.07830](https://arxiv.org/abs/1710.07830)

##### PDF
[https://arxiv.org/pdf/1710.07830](https://arxiv.org/pdf/1710.07830)

