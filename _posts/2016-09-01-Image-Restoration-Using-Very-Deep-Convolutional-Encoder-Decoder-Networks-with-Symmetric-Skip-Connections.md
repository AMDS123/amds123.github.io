---
layout: post
title: "Image Restoration Using Very Deep Convolutional Encoder-Decoder Networks with Symmetric Skip Connections"
date: 2016-09-01 01:15:42
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Xiao-Jiao Mao, Chunhua Shen, Yu-Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a very deep fully convolutional encoding-decoding framework for image restoration such as denoising and super-resolution. The network is composed of multiple layers of convolution and de-convolution operators, learning end-to-end mappings from corrupted images to the original ones. The convolutional layers act as the feature extractor, which capture the abstraction of image contents while eliminating noises/corruptions. De-convolutional layers are then used to recover the image details. We propose to symmetrically link convolutional and de-convolutional layers with skip-layer connections, with which the training converges much faster and attains a higher-quality local optimum. First, The skip connections allow the signal to be back-propagated to bottom layers directly, and thus tackles the problem of gradient vanishing, making training deep networks easier and achieving restoration performance gains consequently. Second, these skip connections pass image details from convolutional layers to de-convolutional layers, which is beneficial in recovering the original image. Significantly, with the large capacity, we can handle different levels of noises using a single model. Experimental results show that our network achieves better performance than all previously reported state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一个非常深入的完全卷积编码 - 解码框架，用于图像恢复，如去噪和超分辨率。网络由多层卷积和解卷积算子组成，学习从破坏图像到原始图像的端到端映射。卷积层充当特征提取器，其捕获图像内容的抽象，同时消除噪声/损坏。去卷积层然后用于恢复图像细节。我们建议将卷积和去卷积层与跳层连接对称地连接起来，训练收敛得更快，并获得更高质量的局部最优。首先，跳过连接允许信号直接反向传播到底层，从而解决了梯度消失的问题，使训练深度网络更容易，从而实现了恢复性能的提高。其次，这些跳过连接将图像细节从卷积层传递到去卷积层，这有利于恢复原始图像。重要的是，在大容量的情况下，我们可以使用单一的模型来处理不同的噪音水平。实验结果表明，我们的网络比以前报道的所有最先进的方法都能获得更好的性能。

##### URL
[https://arxiv.org/abs/1603.09056](https://arxiv.org/abs/1603.09056)

##### PDF
[https://arxiv.org/pdf/1603.09056](https://arxiv.org/pdf/1603.09056)

