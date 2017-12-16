---
layout: post
title: "Adaptive Detrending to Accelerate Convolutional Gated Recurrent Unit Training for Contextual Video Recognition"
date: 2017-05-24 13:52:23
categories: arXiv_CV
tags: arXiv_CV CNN RNN Recognition
author: Minju Jung, Haanvid Lee, Jun Tani
mathjax: true
---

* content
{:toc}

##### Abstract
Based on the progress of image recognition, video recognition has been extensively studied recently. However, most of the existing methods are focused on short-term but not long-term video recognition, called contextual video recognition. To address contextual video recognition, we use convolutional recurrent neural networks (ConvRNNs) having a rich spatio-temporal information processing capability, but ConvRNNs requires extensive computation that slows down training. In this paper, inspired by the normalization and detrending methods, we propose adaptive detrending (AD) for temporal normalization in order to accelerate the training of ConvRNNs, especially for convolutional gated recurrent unit (ConvGRU). AD removes internal covariate shift within a sequence of each neuron in recurrent neural networks (RNNs) by subtracting a trend. In the experiments for contextual recognition on ConvGRU, the results show that (1) ConvGRU clearly outperforms the feed-forward neural networks, (2) AD consistently offers a significant training acceleration and generalization improvement, and (3) AD is further improved by collaborating with the existing normalization methods.

##### Abstract (translated by Google)
基于图像识别技术的进步，近年来视频识别技术得到了广泛的研究。然而，现有的方法大多集中在短时间的视频识别，而不是长时间的视频识别。为了解决上下文视频识别问题，我们使用具有丰富空间 - 时间信息处理能力的卷积递归神经网络（ConvRNN），但是ConvRNN需要大量计算来减慢训练速度。本文在归一化和去趋势化的方法的启发下，提出了适应性时间归一化（AD），以加速ConvRNN的训练，尤其是卷积门控循环单元（ConvGRU）。 AD通过减去趋势来消除递归神经网络（RNN）中的每个神经元的序列内的内部协变量移位。在ConvGRU的情境识别实验中，结果表明：（1）ConvGRU明显优于前馈神经网络;（2）AD始终提供显着的训练加速和泛化改善;（3）AD通过协作与现有的标准化方法。

##### URL
[https://arxiv.org/abs/1705.08764](https://arxiv.org/abs/1705.08764)

##### PDF
[https://arxiv.org/pdf/1705.08764](https://arxiv.org/pdf/1705.08764)

