---
layout: post
title: "Deep Learning with Low Precision by Half-wave Gaussian Quantization"
date: 2017-02-03 10:11:40
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Zhaowei Cai, Xiaodong He, Jian Sun, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of quantizing the activations of a deep neural network is considered. An examination of the popular binary quantization approach shows that this consists of approximating a classical non-linearity, the hyperbolic tangent, by two functions: a piecewise constant sign function, which is used in feedforward network computations, and a piecewise linear hard tanh function, used in the backpropagation step during network learning. The problem of approximating the ReLU non-linearity, widely used in the recent deep learning literature, is then considered. An half-wave Gaussian quantizer (HWGQ) is proposed for forward approximation and shown to have efficient implementation, by exploiting the statistics of of network activations and batch normalization operations commonly used in the literature. To overcome the problem of gradient mismatch, due to the use of different forward and backward approximations, several piece-wise backward approximators are then investigated. The implementation of the resulting quantized network, denoted as HWGQ-Net, is shown to achieve much closer performance to full precision networks, such as AlexNet, ResNet, GoogLeNet and VGG-Net, than previously available low-precision networks, with 1-bit binary weights and 2-bit quantized activations.

##### Abstract (translated by Google)
量化深度神经网络的激活的问题被考虑。对流行的二进制量化方法的研究表明，这包括通过两个函数近似经典的非线性，即双曲正切：在前馈网络计算中使用的分段常数符号函数和分段线性硬tanh函数，用于网络学习期间的反向传播步骤。然后考虑近期深度学习文献中广泛使用的近似ReLU非线性问题。通过利用文献中常用的网络激活和批量归一化操作的统计，提出了一种半波高斯量化器（HWGQ），用于前向逼近，并表现出高效的实现。为了克服梯度失配的问题，由于使用了不同的前向和后向近似，然后研究了几个分段后向逼近器。表示为HWGQ-Net的最终量化网络的实现被示出为比以前可用的低精度网络（例如AlexNet，ResNet，GoogLeNet和VGG-Net）更接近于全精度网络，具有1比特二进制权重和2位量化激活。

##### URL
[https://arxiv.org/abs/1702.00953](https://arxiv.org/abs/1702.00953)

##### PDF
[https://arxiv.org/pdf/1702.00953](https://arxiv.org/pdf/1702.00953)

