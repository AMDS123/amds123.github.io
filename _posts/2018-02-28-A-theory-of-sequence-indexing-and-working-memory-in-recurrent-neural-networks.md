---
layout: post
title: "A theory of sequence indexing and working memory in recurrent neural networks"
date: 2018-02-28 17:54:24
categories: arXiv_CV
tags: arXiv_CV RNN
author: E. Paxon Frady, Denis Kleyko, Friedrich T. Sommer
mathjax: true
---

* content
{:toc}

##### Abstract
To accommodate structured approaches of neural computation, we propose a class of recurrent neural networks for indexing and storing sequences of symbols or analog data vectors. These networks with randomized input weights and orthogonal recurrent weights implement coding principles previously described in vector symbolic architectures (VSA), and leverage properties of reservoir computing. In general, the storage in reservoir computing is lossy and crosstalk noise limits the retrieval accuracy and information capacity. A novel theory to optimize memory performance in such networks is presented and compared with simulation experiments. The theory describes linear readout of analog data, and readout with winner-take-all error correction of symbolic data as proposed in VSA models. We find that diverse VSA models from the literature have universal performance properties, which are superior to what previous analyses predicted. Further, we propose novel VSA models with the statistically optimal Wiener filter in the readout that exhibit much higher information capacity, in particular for storing analog data. The presented theory also applies to memory buffers, networks with gradual forgetting, which can operate on infinite data streams without memory overflow. Interestingly, we find that different forgetting mechanisms, such as attenuating recurrent weights or neural nonlinearities, produce very similar behavior if the forgetting time constants are aligned. Such models exhibit extensive capacity when their forgetting time constant is optimized for given noise conditions and network size. These results enable the design of new types of VSA models for the online processing of data streams.

##### Abstract (translated by Google)
为了适应神经计算的结构化方法，我们提出了一类用于索引和存储符号序列或模拟数据向量的递归神经网络。这些具有随机化输入权重和正交递归权重的网络实现了先前在矢量符号体系结构（VSA）中描述的编码原则，并利用了储层计算的特性。一般来说，储层计算中的存储是有损的，串扰噪声会限制检索精度和信息容量。提出了一种新颖的理论来优化这种网络中的存储器性能，并与仿真实验进行比较。该理论描述了模拟数据的线性读出，以及在VSA模型中提出的带符号数据的胜者全赢错误校正的读数。我们发现来自文献的不同VSA模型具有通用性能特性，这比以前的分析预测要好。此外，我们在读数中提出了具有统计上最佳Wiener滤波器的新型VSA模型，其具有更高的信息容量，特别是用于存储模拟数据。提出的理论也适用于内存缓冲区，逐渐遗忘的网络，它可以在没有内存溢出的无限数据流上操作。有趣的是，如果遗忘时间常数一致，我们发现不同的遗忘机制，例如衰减复发权或神经非线性，会产生非常相似的行为。当遗忘时间常数针对给定的噪声条件和网络大小进行优化时，这些模型展现出广泛的容量。这些结果使得能够设计用于在线处理数据流的新型VSA模型。

##### URL
[https://arxiv.org/abs/1803.00412](https://arxiv.org/abs/1803.00412)

##### PDF
[https://arxiv.org/pdf/1803.00412](https://arxiv.org/pdf/1803.00412)

