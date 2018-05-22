---
layout: post
title: "UNIQ: Uniform Noise Injection for non-uniform Quantization of neural networks"
date: 2018-05-18 20:11:25
categories: arXiv_AI
tags: arXiv_AI Inference
author: Chaim Baskin, Eli Schwartz, Evgenii Zheltonozhskii, Natan Liss, Raja Giryes, Alex M. Bronstein, Avi Mendelson
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method for training a neural network amenable to inference in low-precision arithmetic with quantized weights and activations. The training is performed in full precision with random noise injection emulating quantization noise. In order to circumvent the need to simulate realistic quantization noise distributions, the weight distributions are uniformized by a non-linear transformation, and uniform noise is injected. This procedure emulates a non-uniform k-quantile quantizer at inference time, which adapts to the specific distribution of the quantized parameters. As a by-product of injecting noise to weights, we find that activations can also be quantized to as low as 8-bit with only a minor accuracy degradation. The method achieves state-of-the-art results for training low-precision networks on ImageNet. In particular, we observe no degradation in accuracy for MobileNet and ResNet-18/34/50 on ImageNet with as low as 4-bit quantization of weights. Our solution achieves the state-of-the-art results in accuracy, in the low computational budget regime, compared to similar models.

##### Abstract (translated by Google)
我们提出了一种新的方法来训练一个神经网络适合推理在低精度算术与量化权重和激活。训练以完全精确的方式进行，使用仿真量化噪声的随机噪声注入。为了避免模拟实际量化噪声分布的需要，通过非线性变换使重量分布均匀化，并且注入均匀的噪声。该过程在推理时模拟非均匀k-分位量化器，其适应量化参数的特定分布。作为向噪声注入噪声的副产品，我们发现激活也可以被量化为低至8位，只有很小的精度下降。该方法实现了在ImageNet上训练低精度网络的最新成果。尤其是，我们观察到MobileNet和ResNet-18/34/50在ImageNet上的准确性没有降低，权重低至4位量化。与类似的模型相比，我们的解决方案在低计算预算制度下实现了最新的精确结果。

##### URL
[http://arxiv.org/abs/1804.10969](http://arxiv.org/abs/1804.10969)

##### PDF
[http://arxiv.org/pdf/1804.10969](http://arxiv.org/pdf/1804.10969)

