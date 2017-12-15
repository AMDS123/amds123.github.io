---
layout: post
title: "Deep Adaptive Network: An Efficient Deep Neural Network with Sparse Binary Connections"
date: 2016-04-21 01:47:33
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Deep_Learning Recognition
author: Xichuan Zhou, Shengli Li, Kai Qin, Kunping Li, Fang Tang, Shengdong Hu, Shujun Liu, Zhi Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are state-of-the-art models for understanding the content of images, video and raw input data. However, implementing a deep neural network in embedded systems is a challenging task, because a typical deep neural network, such as a Deep Belief Network using 128x128 images as input, could exhaust Giga bytes of memory and result in bandwidth and computing bottleneck. To address this challenge, this paper presents a hardware-oriented deep learning algorithm, named as the Deep Adaptive Network, which attempts to exploit the sparsity in the neural connections. The proposed method adaptively reduces the weights associated with negligible features to zero, leading to sparse feedforward network architecture. Furthermore, since the small proportion of important weights are significantly larger than zero, they can be robustly thresholded and represented using single-bit integers (-1 and +1), leading to implementations of deep neural networks with sparse and binary connections. Our experiments showed that, for the application of recognizing MNIST handwritten digits, the features extracted by a two-layer Deep Adaptive Network with about 25% reserved important connections achieved 97.2% classification accuracy, which was almost the same with the standard Deep Belief Network (97.3%). Furthermore, for efficient hardware implementations, the sparse-and-binary-weighted deep neural network could save about 99.3% memory and 99.9% computation units without significant loss of classification accuracy for pattern recognition applications.

##### Abstract (translated by Google)
深度神经网络是理解图像，视频和原始输入数据内容的最先进的模型。然而，在嵌入式系统中实现深度神经网络是一个具有挑战性的任务，因为典型的深度神经网络，例如使用128x128图像作为输入的Deep Belief Network，可能会耗尽千兆字节的内存，并导致带宽和计算瓶颈。针对这一挑战，本文提出了一种面向硬件的深度学习算法，称为深度自适应网络，它试图利用神经连接的稀疏性。所提出的方法自适应地将与可忽略的特征相关的权重减小到零，导致稀疏的前馈网络结构。此外，由于重要权重的一小部分显着大于零，因此可以使用单位整数（-1和+1）对它们进行鲁棒阈值化处理，从而实现具有稀疏和二元连接的深度神经网络。我们的实验表明，对于识别MNIST手写数字的应用，二层深度自适应网络提取的特征约占预留重要连接的25％，达到了97.2％的分类精度，与标准的Deep Belief Network（几乎相同） 97.3％）。此外，为了实现高效的硬件实现，稀疏二进制加权深度神经网络可以节省大约99.3％的存储器和99.9％的计算单位，而模式识别应用的分类精度没有显着的损失。

##### URL
[https://arxiv.org/abs/1604.06154](https://arxiv.org/abs/1604.06154)

##### PDF
[https://arxiv.org/pdf/1604.06154](https://arxiv.org/pdf/1604.06154)

