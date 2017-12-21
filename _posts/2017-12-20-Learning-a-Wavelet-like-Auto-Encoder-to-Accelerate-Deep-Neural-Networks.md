---
layout: post
title: "Learning a Wavelet-like Auto-Encoder to Accelerate Deep Neural Networks"
date: 2017-12-20 14:24:00
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Recognition
author: Tianshui Chen, Liang Lin, Wangmeng Zuo, Xiaonan Luo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Accelerating deep neural networks (DNNs) has been attracting increasing attention as it can benefit a wide range of applications, e.g., enabling mobile systems with limited computing resources to own powerful visual recognition ability. A practical strategy to this goal usually relies on a two-stage process: operating on the trained DNNs (e.g., approximating the convolutional filters with tensor decomposition) and fine-tuning the amended network, leading to difficulty in balancing the trade-off between acceleration and maintaining recognition performance. In this work, aiming at a general and comprehensive way for neural network acceleration, we develop a Wavelet-like Auto-Encoder (WAE) that decomposes the original input image into two low-resolution channels (sub-images) and incorporate the WAE into the classification neural networks for joint training. The two decomposed channels, in particular, are encoded to carry the low-frequency information (e.g., image profiles) and high-frequency (e.g., image details or noises), respectively, and enable reconstructing the original input image through the decoding process. Then, we feed the low-frequency channel into a standard classification network such as VGG or ResNet and employ a very lightweight network to fuse with the high-frequency channel to obtain the classification result. Compared to existing DNN acceleration solutions, our framework has the following advantages: i) it is tolerant to any existing convolutional neural networks for classification without amending their structures; ii) the WAE provides an interpretable way to preserve the main components of the input image for classification.

##### Abstract (translated by Google)
加速深度神经网络（DNN）已经引起越来越多的关注，因为它可以有益于广泛的应用，例如使得具有有限计算资源的移动系统具有强大的视觉识别能力。实现这一目标的一个实际策略通常依赖于一个两阶段的过程：在训练好的DNN上运行（例如，用张量分解逼近卷积滤波器）并微调修正后的网络，导致难以平衡加速度并保持表扬。本文针对神经网络加速的一般和全面的方法，开发了一种小波状自动编码器（WAE），将原始输入图像分解成两个低分辨率的通道（子图像），并将WAE联合训练的分类神经网络。这两个分解的信道尤其被编码以分别携带低频信息（例如，图像轮廓）和高频（例如，图像细节或噪声），并且能够通过解码处理来重建原始输入图像。然后将低频信道送入VGG，ResNet等标准分类网络，采用非常轻的网络与高频信道融合，得到分类结果。与现有的DNN加速解决方案相比，我们的框架具有以下优点：1）能够容忍任何现有的卷积神经网络进行分类而不需要修改其结构; ii）WAE提供可解释的方式来保存输入图像的主要组成部分以进行分类。

##### URL
[https://arxiv.org/abs/1712.07493](https://arxiv.org/abs/1712.07493)

##### PDF
[https://arxiv.org/pdf/1712.07493](https://arxiv.org/pdf/1712.07493)

