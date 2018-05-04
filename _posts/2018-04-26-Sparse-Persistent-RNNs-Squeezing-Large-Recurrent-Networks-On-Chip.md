---
layout: post
title: "Sparse Persistent RNNs: Squeezing Large Recurrent Networks On-Chip"
date: 2018-04-26 18:18:57
categories: arXiv_CL
tags: arXiv_CL Sparse Speech_Recognition Optimization NMT RNN Recognition
author: Feiwen Zhu, Jeff Pool, Michael Andersch, Jeremy Appleyard, Fung Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) are powerful tools for solving sequence-based problems, but their efficacy and execution time are dependent on the size of the network. Following recent work in simplifying these networks with model pruning and a novel mapping of work onto GPUs, we design an efficient implementation for sparse RNNs. We investigate several optimizations and tradeoffs: Lamport timestamps, wide memory loads, and a bank-aware weight layout. With these optimizations, we achieve speedups of over 6x over the next best algorithm for a hidden layer of size 2304, batch size of 4, and a density of 30%. Further, our technique allows for models of over 5x the size to fit on a GPU for a speedup of 2x, enabling larger networks to help advance the state-of-the-art. We perform case studies on NMT and speech recognition tasks in the appendix, accelerating their recurrent layers by up to 3x.

##### Abstract (translated by Google)
递归神经网络（RNN）是解决基于序列的问题的强大工具，但其功效和执行时间取决于网络的大小。继最近通过模型修剪和工作映射到GPU上的简化这些网络的工作之后，我们为稀疏RNN设计了一个高效的实现。我们调查了几项优化和折衷：Lamport时间戳，宽内存负载和银行意识重量布局。通过这些优化，我们的隐藏层大小为2304，批量大小为4，密度为30％的隐藏层的下一个最佳算法实现了超过6倍的加速。此外，我们的技术允许超过5倍尺寸的模型适合GPU加速2倍，从而使更大的网络能够帮助推进最先进的技术。我们对附录中的NMT和语音识别任务进行案例研究，将其复发层次加速至3倍。

##### URL
[https://arxiv.org/abs/1804.10223](https://arxiv.org/abs/1804.10223)

##### PDF
[https://arxiv.org/pdf/1804.10223](https://arxiv.org/pdf/1804.10223)

