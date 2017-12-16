---
layout: post
title: "Espresso: Efficient Forward Propagation for BCNNs"
date: 2017-05-19 20:29:42
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Fabrizio Pedersoli, George Tzanetakis, Andrea Tagliasacchi
mathjax: true
---

* content
{:toc}

##### Abstract
There are many applications scenarios for which the computational performance and memory footprint of the prediction phase of Deep Neural Networks (DNNs) needs to be optimized. Binary Neural Networks (BDNNs) have been shown to be an effective way of achieving this objective. In this paper, we show how Convolutional Neural Networks (CNNs) can be implemented using binary representations. Espresso is a compact, yet powerful library written in C/CUDA that features all the functionalities required for the forward propagation of CNNs, in a binary file less than 400KB, without any external dependencies. Although it is mainly designed to take advantage of massive GPU parallelism, Espresso also provides an equivalent CPU implementation for CNNs. Espresso provides special convolutional and dense layers for BCNNs, leveraging bit-packing and bit-wise computations for efficient execution. These techniques provide a speed-up of matrix-multiplication routines, and at the same time, reduce memory usage when storing parameters and activations. We experimentally show that Espresso is significantly faster than existing implementations of optimized binary neural networks ($\approx$ 2 orders of magnitude). Espresso is released under the Apache 2.0 license and is available at this http URL

##### Abstract (translated by Google)
深度神经网络（DNN）的预测阶段的计算性能和存储器占用空间需要被优化。二进制神经网络（BDNN）已被证明是实现这一目标的有效途径。在本文中，我们展示了如何使用二进制表示来实现卷积神经网络（CNN）。 Espresso是一个用C / CUDA编写的紧凑但功能强大的库，它具有CNN向前传播所需的全部功能，二进制文件小于400KB，无需任何外部依赖。虽然它主要是为了利用庞大的GPU并行性而设计的，但Espresso还提供了一个与CNN等效的CPU实现。 Espresso为BCNN提供特殊的卷积和密集层，利用位打包和按位计算来实现高效执行。这些技术提供了矩阵乘法例程的加速，同时在存储参数和激活时减少了内存使用量。我们通过实验证明，Espresso比现有的优化二元神经网络（$ \约$ 2个数量级）快得多。 Espresso是在Apache 2.0许可下发布的，可以在这个http URL中找到

##### URL
[https://arxiv.org/abs/1705.07175](https://arxiv.org/abs/1705.07175)

##### PDF
[https://arxiv.org/pdf/1705.07175](https://arxiv.org/pdf/1705.07175)

