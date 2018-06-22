---
layout: post
title: "Quantizing deep convolutional networks for efficient inference: A whitepaper"
date: 2018-06-21 17:32:46
categories: arXiv_CV
tags: arXiv_CV Review CNN Optimization Inference Classification
author: Raghuraman Krishnamoorthi
mathjax: true
---

* content
{:toc}

##### Abstract
We present an overview of techniques for quantizing convolutional neural networks for inference with integer weights and activations. Per-channel quantization of weights and per-layer quantization of activations to 8-bits of precision post-training produces classification accuracies within 2% of floating point networks for a wide variety of CNN architectures. Model sizes can be reduced by a factor of 4 by quantizing weights to 8-bits, even when 8-bit arithmetic is not supported. This can be achieved with simple, post training quantization of weights.We benchmark latencies of quantized networks on CPUs and DSPs and observe a speedup of 2x-3x for quantized implementations compared to floating point on CPUs. Speedups of up to 10x are observed on specialized processors with fixed point SIMD capabilities, like the Qualcomm QDSPs with HVX. 
 Quantization-aware training can provide further improvements, reducing the gap to floating point to 1% at 8-bit precision. Quantization-aware training also allows for reducing the precision of weights to four bits with accuracy losses ranging from 2% to 10%, with higher accuracy drop for smaller networks.We introduce tools in TensorFlow and TensorFlowLite for quantizing convolutional networks and review best practices for quantization-aware training to obtain high accuracy with quantized weights and activations. We recommend that per-channel quantization of weights and per-layer quantization of activations be the preferred quantization scheme for hardware acceleration and kernel optimization. We also propose that future processors and hardware accelerators for optimized inference support precisions of 4, 8 and 16 bits.

##### Abstract (translated by Google)
我们概述了量化卷积神经网络以整数权重和激活进行推理的技术。按照8位精度后置训练的权重和每层量化激活的每通道量化，在各种CNN体系结构的浮点网络的2％内产生分类精度。即使不支持8位算术，通过将权重量化为8位，模型大小可以减少4倍。这可以通过简单的后置训练量化权重来实现。我们测量了CPU和DSP上的量化网络的延迟，并观察了与CPU上的浮点相比，量化实现的加速比为2x-3x。在具有定点SIMD功能的专用处理器上观察到高达10倍的加速，例如带有HVX的Qualcomm QDSP。
 量化意识培训可以提供进一步的改进，以8位精度将浮点差距缩小到1％。量化感知训练还允许将权重精度降低到4比特，准确度损失范围从2％到10％不等，对于较小的网络精度下降更高。我们在TensorFlow和TensorFlowLite中引入工具来量化卷积网络并审阅最佳实践量化意识训练以获得具有量化权重和激活的高精度。我们建议每个通道的权重量化和激活的每层量化都是硬件加速和内核优化的首选量化方案。我们还建议未来的处理器和硬件加速器可以优化推理，支持4,8和16位的精度。

##### URL
[http://arxiv.org/abs/1806.08342](http://arxiv.org/abs/1806.08342)

##### PDF
[http://arxiv.org/pdf/1806.08342](http://arxiv.org/pdf/1806.08342)

