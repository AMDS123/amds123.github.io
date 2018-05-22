---
layout: post
title: "Faster Neural Network Training with Approximate Tensor Operations"
date: 2018-05-21 14:14:14
categories: arXiv_AI
tags: arXiv_AI RNN
author: Menachem Adelman, Mark Silberstein
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel technique for faster Neural Network (NN) training by systematically approximating all the constituent matrix multiplications and convolutions. This approach is complementary to other approximation techniques, requires no changes to the dimensions of the network layers, hence compatible with existing training frameworks. We first analyze the applicability of the existing methods for approximating matrix multiplication to NN training, and extend the most suitable column-row sampling algorithm to approximating multi-channel convolutions. We apply approximate tensor operations to training MLP, CNN and LSTM network architectures on MNIST, CIFAR-100 and Penn Tree Bank datasets and demonstrate 30%-80% reduction in the amount of computations while maintaining little or no impact on the test accuracy. Our promising results encourage further study of general methods for approximating tensor operations and their application to NN training.

##### Abstract (translated by Google)
我们提出了一种快速神经网络（NN）训练的新技术，系统地近似所有组成矩阵乘法和卷积。这种方法与其他近似技术是互补的，不需要改变网络层的尺寸，因此与现有的培训框架兼容。我们首先分析现有方法用于近似矩阵乘法的神经网络训练的适用性，并将最适合的列行采样算法扩展到逼近多通道卷积。我们应用近似张量运算来训练MNIST，CIFAR-100和Penn Tree Bank数据集上的MLP，CNN和LSTM网络架构，并且演示计算量减少30％-80％，同时对测试精度几乎没有影响。我们有希望的结果鼓励进一步研究近似张量运算的一般方法及其在NN训练中的应用。

##### URL
[https://arxiv.org/abs/1805.08079](https://arxiv.org/abs/1805.08079)

##### PDF
[https://arxiv.org/pdf/1805.08079](https://arxiv.org/pdf/1805.08079)

