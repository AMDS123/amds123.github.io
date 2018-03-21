---
layout: post
title: "I Know What You See: Power Side-Channel Attack on Convolutional Neural Network Accelerators"
date: 2018-03-05 11:35:14
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Recognition
author: Lingxiao Wei, Yannan Liu, Bo Luo, Yu Li, Qiang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has become the de-facto computational paradigm for various kinds of perception problems, including many privacy-sensitive applications such as online medical image analysis. No doubt to say, the data privacy of these deep learning systems is a serious concern. Different from previous research focusing on exploiting privacy leakage from deep learning models, in this paper, we present the first attack on the implementation of deep learning models. To be specific, we perform the attack on an FPGA-based convolutional neural network accelerator and we manage to recover the input image from the collected power traces without knowing the detailed parameters in the neural network by utilizing the characteristics of the "line buffer" performing convolution in the CNN accelerators. For the MNIST dataset, our power side-channel attack is able to achieve up to 89% recognition accuracy.

##### Abstract (translated by Google)
深度学习已成为各种感知问题的事实上的计算范例，包括许多隐私敏感的应用，如在线医学图像分析。毫无疑问，这些深度学习系统的数据隐私是一个严重的问题。与以往的研究侧重于利用深度学习模型中的隐私泄漏不同，本文提出了深度学习模型实施的第一次攻击。具体而言，我们在基于FPGA的卷积神经网络加速器上执行攻击，并通过利用“行缓冲区”执行的特性，在不知道神经网络中的详细参数的情况下，从收集的功率曲线中恢复输入图像卷积在CNN加速器中。对于MNIST数据集，我们的功率旁通道攻击能够实现高达89％的识别精度。

##### URL
[https://arxiv.org/abs/1803.05847](https://arxiv.org/abs/1803.05847)

##### PDF
[https://arxiv.org/pdf/1803.05847](https://arxiv.org/pdf/1803.05847)

