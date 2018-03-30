---
layout: post
title: "Diagonalwise Refactorization: An Efficient Training Method for Depthwise Convolutions"
date: 2018-03-27 07:06:54
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Zheng Qin, Zhaoning Zhang, Dongsheng Li, Yiming Zhang, Yuxing Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Depthwise convolutions provide significant performance benefits owing to the reduction in both parameters and mult-adds. However, training depthwise convolution layers with GPUs is slow in current deep learning frameworks because their implementations cannot fully utilize the GPU capacity. To address this problem, in this paper we present an efficient method (called diagonalwise refactorization) for accelerating the training of depthwise convolution layers. Our key idea is to rearrange the weight vectors of a depthwise convolution into a large diagonal weight matrix so as to convert the depthwise convolution into one single standard convolution, which is well supported by the cuDNN library that is highly-optimized for GPU computations. We have implemented our training method in five popular deep learning frameworks. Evaluation results show that our proposed method gains $15.4\times$ training speedup on Darknet, $8.4\times$ on Caffe, $5.4\times$ on PyTorch, $3.5\times$ on MXNet, and $1.4\times$ on TensorFlow, compared to their original implementations of depthwise convolutions.

##### Abstract (translated by Google)
深度卷积由于参数和多加减少而提供显着的性能优势。然而，在当前的深度学习框架中，使用GPU对深度卷积层进行深度训练速度较慢，因为它们的实现不能充分利用GPU的容量。为了解决这个问题，在本文中，我们提出了一种有效的方法（称为对角线重构）来加速深度卷积层的训练。我们的主要想法是将深度卷积的权重向量重新排列为大对角权重矩阵，以便将深度卷积转换为单个标准卷积，这受到针对GPU计算高度优化的cuDNN库的良好支持。我们在五个流行的深度学习框架中实施了我们的培训方法。评估结果表明，我们提出的方法在Darknet上获得了15.4倍的培训加速，在Caffe上获得了8.4美元/次，在PyTorch上获得了5.4美元/倍，MXNet获得了3.5美元/倍，TensorFlow获得了1.4美元/倍$，深度卷积的实现。

##### URL
[https://arxiv.org/abs/1803.09926](https://arxiv.org/abs/1803.09926)

##### PDF
[https://arxiv.org/pdf/1803.09926](https://arxiv.org/pdf/1803.09926)

