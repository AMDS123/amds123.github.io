---
layout: post
title: "UNIQ: Uniform Noise Injection for the Quantization of Neural Networks"
date: 2018-04-29 17:38:20
categories: arXiv_AI
tags: arXiv_AI Inference
author: Chaim Baskin, Eli Schwartz, Evgenii Zheltonozhskii, Natan Liss, Raja Giryes, Alex M. Bronstein, Avi Mendelson
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method for training deep neural network amenable to inference in low-precision arithmetic with quantized weights and activations. The training is performed in full precision with random noise injection emulating quantization noise. In order to circumvent the need to simulate realistic quantization noise distributions, the weight and the activation distributions are uniformized by a non-linear transformation, and uniform noise is injected. An inverse transformation is then applied. This procedure emulates a non-uniform k-quantile quantizer at inference time, which is shown to achieve state-of-the-art results for training low-precision networks on CIFAR-10 and ImageNet-1K datasets. In particular, we observe no degradation in accuracy for MobileNet and ResNet-18 on ImageNet with as low as 2-bit quantization of the activations and minimal degradation for as little as 4 bits for the weights.

##### Abstract (translated by Google)
我们提出了一种新的训练深度神经网络的方法，可用于量化权重和激活的低精度算术中的推理。训练以完全精确的方式进行，使用仿真量化噪声的随机噪声注入。为了避免模拟现实量化噪声分布的需要，通过非线性变换使加权和激活分布均匀化，并且注入均匀的噪声。然后应用逆变换。该过程在推理时间内模拟非均匀k-分位量化器，该算法被证明可以在CIFAR-10和ImageNet-1K数据集上获得用于训练低精度网络的最新结果。尤其是，我们观察到ImageNet上的MobileNet和ResNet-18的准确性没有降低，对激活的量化低至2比特量化，对于权重只有4比特的劣化最小。

##### URL
[https://arxiv.org/abs/1804.10969](https://arxiv.org/abs/1804.10969)

##### PDF
[https://arxiv.org/pdf/1804.10969](https://arxiv.org/pdf/1804.10969)

