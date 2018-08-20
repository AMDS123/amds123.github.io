---
layout: post
title: "Joint Training of Low-Precision Neural Network with Quantization Interval Parameters"
date: 2018-08-17 07:28:17
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Sangil Jung, Changyong Son, Seohyung Lee, Jinwoo Son, Youngjun Kwak, Jae-Joon Han, Changkyu Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Optimization for low-precision neural network is an important technique for deep convolutional neural network models to be deployed to mobile devices. In order to realize convolutional layers with the simple bit-wise operations, both activation and weight parameters need to be quantized with a low bit-precision. In this paper, we propose a novel optimization method for low-precision neural network which trains both activation quantization parameters and the quantized model weights. We parameterize the quantization intervals of the weights and the activations and train the parameters with the full-precision weights by directly minimizing the training loss rather than minimizing the quantization error. Thanks to the joint optimization of quantization parameters and model weights, we obtain the highly accurate low-precision network given a target bitwidth. We demonstrated the effectiveness of our method on two benchmarks: CIFAR-10 and ImageNet.

##### Abstract (translated by Google)
低精度神经网络的优化是深度卷积神经网络模型部署到移动设备的重要技术。为了利用简单的逐位操作实现卷积层，激活和权重参数都需要以低位精度量化。在本文中，我们提出了一种新的低精度神经网络优化方法，它训练激活量化参数和量化模型权重。我们通过直接最小化训练损失而不是最小化量化误差来参数化权重和激活的量化间隔并用全精度权重训练参数。由于量化参数和模型权重的联合优化，我们在给定目标位宽的情况下获得高度精确的低精度网络。我们在两个基准测试中证明了我们的方法的有效性：CIFAR-10和ImageNet。

##### URL
[http://arxiv.org/abs/1808.05779](http://arxiv.org/abs/1808.05779)

##### PDF
[http://arxiv.org/pdf/1808.05779](http://arxiv.org/pdf/1808.05779)

