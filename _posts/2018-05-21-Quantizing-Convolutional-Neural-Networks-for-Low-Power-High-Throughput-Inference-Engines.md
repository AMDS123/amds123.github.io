---
layout: post
title: "Quantizing Convolutional Neural Networks for Low-Power High-Throughput Inference Engines"
date: 2018-05-21 08:31:46
categories: arXiv_AI
tags: arXiv_AI CNN Inference Deep_Learning
author: Sean O. Settle, Manasa Bollavaram, Paolo D'Alberto, Elliott Delaye, Oscar Fernandez, Nicholas Fraser, Aaron Ng, Ashish Sirasao, Michael Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning as a means to inferencing has proliferated thanks to its versatility and ability to approach or exceed human-level accuracy. These computational models have seemingly insatiable appetites for computational resources not only while training, but also when deployed at scales ranging from data centers all the way down to embedded devices. As such, increasing consideration is being made to maximize the computational efficiency given limited hardware and energy resources and, as a result, inferencing with reduced precision has emerged as a viable alternative to the IEEE 754 Standard for Floating-Point Arithmetic. We propose a quantization scheme that allows inferencing to be carried out using arithmetic that is fundamentally more efficient when compared to even half-precision floating-point. Our quantization procedure is significant in that we determine our quantization scheme parameters by calibrating against its reference floating-point model using a single inference batch rather than (re)training and achieve end-to-end post quantization accuracies comparable to the reference model.

##### Abstract (translated by Google)
由于其多功能性和接近或超过人类准确度的能力，作为推理手段的深度学习激增。这些计算模型不仅在训练时对计算资源看起来永不满足，而且在从数据中心一直到嵌入式设备的各种规模上都有部署。因此，考虑到有限的硬件和能量资源，越来越多的考虑将计算效率最大化，因此，降低精度的推理已经成为IEEE 754浮点运算标准的可行替代方案。我们提出了一种量化方案，它允许使用与甚至半精度浮点相比基本上更高效的算术进行推理。我们的量化过程非常重要，因为我们通过使用单个推理批量而不是（重新）训练来针对其参考浮点模型进行校准来确定量化方案参数，并且实现了与参考模型相当的端到端后期量化精度。

##### URL
[https://arxiv.org/abs/1805.07941](https://arxiv.org/abs/1805.07941)

##### PDF
[https://arxiv.org/pdf/1805.07941](https://arxiv.org/pdf/1805.07941)

