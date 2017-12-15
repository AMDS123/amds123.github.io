---
layout: post
title: "Efficient forward propagation of time-sequences in convolutional neural networks using Deep Shifting"
date: 2016-03-11 15:16:09
categories: arXiv_CV
tags: arXiv_CV CNN
author: Koen Groenland, Sander Bohte
mathjax: true
---

* content
{:toc}

##### Abstract
When a Convolutional Neural Network is used for on-the-fly evaluation of continuously updating time-sequences, many redundant convolution operations are performed. We propose the method of Deep Shifting, which remembers previously calculated results of convolution operations in order to minimize the number of calculations. The reduction in complexity is at least a constant and in the best case quadratic. We demonstrate that this method does indeed save significant computation time in a practical implementation, especially when the networks receives a large number of time-frames.

##### Abstract (translated by Google)
当使用卷积神经网络对连续更新的时间序列进行实时评估时，执行了许多冗余的卷积操作。我们提出了深移的方法，它记住了先前计算的卷积运算结果，以最小化计算次数。复杂度的降低至少是一个常数，在最好的情况下是二次的。我们证明这种方法的确在实际实现中节省了大量的计算时间，特别是当网络接收到大量的时间帧时。

##### URL
[https://arxiv.org/abs/1603.03657](https://arxiv.org/abs/1603.03657)

##### PDF
[https://arxiv.org/pdf/1603.03657](https://arxiv.org/pdf/1603.03657)

