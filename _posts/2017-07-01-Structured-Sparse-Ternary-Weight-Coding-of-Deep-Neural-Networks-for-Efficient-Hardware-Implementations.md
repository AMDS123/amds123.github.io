---
layout: post
title: "Structured Sparse Ternary Weight Coding of Deep Neural Networks for Efficient Hardware Implementations"
date: 2017-07-01 05:38:55
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference
author: Yoonho Boo, Wonyong Sung
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) usually demand a large amount of operations for real-time inference. Especially, fully-connected layers contain a large number of weights, thus they usually need many off-chip memory accesses for inference. We propose a weight compression method for deep neural networks, which allows values of +1 or -1 only at predetermined positions of the weights so that decoding using a table can be conducted easily. For example, the structured sparse (8,2) coding allows at most two non-zero values among eight weights. This method not only enables multiplication-free DNN implementations but also compresses the weight storage by up to x32 compared to floating-point networks. Weight distribution normalization and gradual pruning techniques are applied to mitigate the performance degradation. The experiments are conducted with fully-connected deep neural networks and convolutional neural networks.

##### Abstract (translated by Google)
深度神经网络（DNN）通常要求大量的实时推理操作。特别是，完全连接的层包含大量的权重，因此通常需要许多片外存储器访问来进行推断。我们提出了一种深度神经网络的权重压缩方法，它只允许在权重的预定位置上+1或-1的值，这样使用表格的解码可以容易地进行。例如，结构化稀疏（8,2）编码允许八个权重中的至多两个非零值。这种方法不仅可以实现无乘法DNN实现，而且与浮点网络相比，还可以将权重存储压缩到x32。应用重量分布规范化和逐步修剪技术来缓解性能下降。实验采用全连接的深度神经网络和卷积神经网络进行。

##### URL
[https://arxiv.org/abs/1707.03684](https://arxiv.org/abs/1707.03684)

##### PDF
[https://arxiv.org/pdf/1707.03684](https://arxiv.org/pdf/1707.03684)

