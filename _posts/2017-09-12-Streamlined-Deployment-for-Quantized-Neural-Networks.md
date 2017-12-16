---
layout: post
title: "Streamlined Deployment for Quantized Neural Networks"
date: 2017-09-12 21:14:57
categories: arXiv_CV
tags: arXiv_CV Inference
author: Yaman Umuroglu, Magnus Jahre
mathjax: true
---

* content
{:toc}

##### Abstract
Running Deep Neural Network (DNN) models on devices with limited computational capability is a challenge due to large compute and memory requirements. Quantized Neural Networks (QNNs) have emerged as a potential solution to this problem, promising to offer most of the DNN accuracy benefits with much lower computational cost. However, harvesting these benefits on existing mobile CPUs is a challenge since operations on highly quantized datatypes are not natively supported in most instruction set architectures (ISAs). In this work, we first describe a streamlining flow to convert all QNN inference operations to integer ones. Afterwards, we provide techniques based on processing one bit position at a time (bit-serial) to show how QNNs can be efficiently deployed using common bitwise operations. We demonstrate the potential of QNNs on mobile CPUs with microbenchmarks and on a quantized AlexNet, which is 3.5x faster than an optimized 8-bit baseline.

##### Abstract (translated by Google)
在计算能力有限的设备上运行深度神经网络（DNN）模型是一个挑战，因为计算和内存要求很大。量化的神经网络（QNNs）已经成为解决这个问题的一个潜在的解决方案，承诺以更低的计算成本提供大部分DNN准确度的好处。然而，在现有的移动CPU上获取这些好处是一个挑战，因为在大多数指令集体系结构（ISA）中本质上不支持高度量化数据类型的操作。在这项工作中，我们首先描述一个简化的流程，将所有的QNN推理操作转换为整数。之后，我们提供基于一次处理一位位置的技术（比特序列），以显示如何使用常见的按位运算有效地部署QNN。我们展示了使用微基准的移动CPU和量化的AlexNet上QNN的潜力，其比优化的8位基线快3.5倍。

##### URL
[https://arxiv.org/abs/1709.04060](https://arxiv.org/abs/1709.04060)

##### PDF
[https://arxiv.org/pdf/1709.04060](https://arxiv.org/pdf/1709.04060)

