---
layout: post
title: "Theory and Tools for the Conversion of Analog to Spiking Convolutional Neural Networks"
date: 2016-12-13 07:58:34
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Bodo Rueckauer, Iulia-Alexandra Lungu, Yuhuang Hu, Michael Pfeiffer
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have shown great potential for numerous real-world machine learning applications, but performing inference in large CNNs in real-time remains a challenge. We have previously demonstrated that traditional CNNs can be converted into deep spiking neural networks (SNNs), which exhibit similar accuracy while reducing both latency and computational load as a consequence of their data-driven, event-based style of computing. Here we provide a novel theory that explains why this conversion is successful, and derive from it several new tools to convert a larger and more powerful class of deep networks into SNNs. We identify the main sources of approximation errors in previous conversion methods, and propose simple mechanisms to fix these issues. Furthermore, we develop spiking implementations of common CNN operations such as max-pooling, softmax, and batch-normalization, which allow almost loss-less conversion of arbitrary CNN architectures into the spiking domain. Empirical evaluation of different network architectures on the MNIST and CIFAR10 benchmarks leads to the best SNN results reported to date.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）已经显示出了许多现实世界中的机器学习应用的巨大潜力，但是在大型CNN中实时推断仍然是一个挑战。我们之前已经证明，传统的CNN可以转化为深度尖峰神经网络（SNN），由于其数据驱动的基于事件的计算风格的结果，传统的CNN可以表现出相似的准确性，同时减少了延迟和计算负担。在这里，我们提供了一个新颖的理论，解释了为什么这个转换是成功的，并从中推导出一些新的工具，将更大，更强大的深度网络转换成SNN。我们确定以前的转换方法中的近似误差的主要来源，并提出简单的机制来解决这些问题。此外，我们开发了通用CNN操作的尖峰实现，例如max-pooling，softmax和batch-normalization，它们允许将任意CNN体系结构几乎毫无损失地转换为spiking域。对MNIST和CIFAR10基准的不同网络体系结构的实证评估导致迄今为止报告的最佳SNN结果。

##### URL
[https://arxiv.org/abs/1612.04052](https://arxiv.org/abs/1612.04052)

##### PDF
[https://arxiv.org/pdf/1612.04052](https://arxiv.org/pdf/1612.04052)

