---
layout: post
title: "Low-memory GEMM-based convolution algorithms for deep neural networks"
date: 2017-09-08 06:32:33
categories: arXiv_CV
tags: arXiv_CV Inference
author: Andrew Anderson, Aravind Vasudevan, Cormac Keane, David Gregg
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) require very large amounts of computation both for training and for inference when deployed in the field. A common approach to implementing DNNs is to recast the most computationally expensive operations as general matrix multiplication (GEMM). However, as we demonstrate in this paper, there are a great many different ways to express DNN convolution operations using GEMM. Although different approaches all perform the same number of operations, the size of temporary data structures differs significantly. Convolution of an input matrix with dimensions $C \times H \times W$, requires $O(K^2CHW)$ additional space using the classical im2col approach. More recently memory-efficient approaches requiring just $O(KCHW)$ auxiliary space have been proposed. We present two novel GEMM-based algorithms that require just $O(MHW)$ and $O(KW)$ additional space respectively, where $M$ is the number of channels in the result of the convolution. These algorithms dramatically reduce the space overhead of DNN convolution, making it much more suitable for memory-limited embedded systems. Experimental evaluation shows that our low-memory algorithms are just as fast as the best patch-building approaches despite requiring just a fraction of the amount of additional memory. Our low-memory algorithms have excellent data locality which gives them a further edge over patch-building algorithms when multiple cores are used. As a result, our low memory algorithms often outperform the best patch-building algorithms using multiple threads.

##### Abstract (translated by Google)
深度神经网络（DNN）在现场部署时需要进行大量的训练和推理计算。实现DNN的一种常见方法是将最耗费大计算量的操作改写为通用矩阵乘法（GEMM）。但是，正如我们在本文中所展示的那样，使用GEMM来表达DNN卷积操作有很多不同的方法。尽管不同的方法都执行相同数量的操作，但临时数据结构的大小差别很大。输入矩阵与维数$ C \ times H \ times W $的卷积，使用传统的im2col方法需要$ O（K ^ 2CHW）$额外的空间。最近提出了只需要$ O（KCHW）$辅助空间的高效内存方法。我们提出了两种新的基于GEMM的算法，分别只需要$ O（MHW）$和$ O（KW）$额外的空间，其中$ M $是卷积结果中的通道数目。这些算法大大降低了DNN卷积的空间开销，使其更适合内存有限的嵌入式系统。实验评估表明，尽管只需要额外内存的一小部分，但是我们的低内存算法与最好的补丁构建方法一样快。我们的低内存算法具有出色的数据局部性，这使得它们在使用多个内核时比修补构建算法更具优势。因此，我们的低内存算法通常优于使用多线程的最佳补丁构建算法。

##### URL
[https://arxiv.org/abs/1709.03395](https://arxiv.org/abs/1709.03395)

##### PDF
[https://arxiv.org/pdf/1709.03395](https://arxiv.org/pdf/1709.03395)

