---
layout: post
title: "MEC: Memory-efficient Convolution for Deep Neural Network"
date: 2017-06-21 13:00:39
categories: arXiv_CV
tags: arXiv_CV
author: Minsik Cho, Daniel Brand
mathjax: true
---

* content
{:toc}

##### Abstract
Convolution is a critical component in modern deep neural networks, thus several algorithms for convolution have been developed. Direct convolution is simple but suffers from poor performance. As an alternative, multiple indirect methods have been proposed including im2col-based convolution, FFT-based convolution, or Winograd-based algorithm. However, all these indirect methods have high memory-overhead, which creates performance degradation and offers a poor trade-off between performance and memory consumption. In this work, we propose a memory-efficient convolution or MEC with compact lowering, which reduces memory-overhead substantially and accelerates convolution process. MEC lowers the input matrix in a simple yet efficient/compact way (i.e., much less memory-overhead), and then executes multiple small matrix multiplications in parallel to get convolution completed. Additionally, the reduced memory footprint improves memory sub-system efficiency, improving performance. Our experimental results show that MEC reduces memory consumption significantly with good speedup on both mobile and server platforms, compared with other indirect convolution algorithms.

##### Abstract (translated by Google)
卷积是现代深度神经网络中的关键组件，因此已经开发了几种卷积算法。直接卷积很简单，但性能不佳。作为替代，已经提出了多种间接方法，包括基于im2col的卷积，基于FFT的卷积或基于Winograd的算法。但是，所有这些间接方法都具有很高的内存开销，从而导致性能下降，并且在性能和内存消耗之间提供较差的折衷。在这项工作中，我们提出了一个紧凑的降低内存效率的卷积或MEC，这大大减少了内存开销，并加速了卷积过程。 MEC以简单但有效/紧凑的方式降低了输入矩阵（即，少得多的存储器开销），然后并行地执行多个小矩阵乘法以完成卷积。另外，减少的内存占用量提高了内存子系统效率，提高了性能。我们的实验结果表明，与其他间接卷积算法相比，MEC在移动和服务器平台上都有很好的加速比，显着降低了内存消耗。

##### URL
[https://arxiv.org/abs/1706.06873](https://arxiv.org/abs/1706.06873)

##### PDF
[https://arxiv.org/pdf/1706.06873](https://arxiv.org/pdf/1706.06873)

