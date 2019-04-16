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


##### URL
[https://arxiv.org/abs/1709.03395](https://arxiv.org/abs/1709.03395)

##### PDF
[https://arxiv.org/pdf/1709.03395](https://arxiv.org/pdf/1709.03395)

