---
layout: post
title: "Optimizing Memory Efficiency for Deep Convolutional Neural Networks on GPUs"
date: 2016-10-12 07:02:48
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Recognition
author: Chao Li, Yi Yang, Min Feng, Srimat Chakradhar, Huiyang Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Leveraging large data sets, deep Convolutional Neural Networks (CNNs) achieve state-of-the-art recognition accuracy. Due to the substantial compute and memory operations, however, they require significant execution time. The massive parallel computing capability of GPUs make them as one of the ideal platforms to accelerate CNNs and a number of GPU-based CNN libraries have been developed. While existing works mainly focus on the computational efficiency of CNNs, the memory efficiency of CNNs have been largely overlooked. Yet CNNs have intricate data structures and their memory behavior can have significant impact on the performance. In this work, we study the memory efficiency of various CNN layers and reveal the performance implication from both data layouts and memory access patterns. Experiments show the universal effect of our proposed optimizations on both single layers and various networks, with up to 27.9x for a single layer and up to 5.6x on the whole networks.

##### Abstract (translated by Google)
利用大型数据集，深度卷积神经网络（CNN）实现了最先进的识别精度。但是，由于大量的计算和内存操作，它们需要大量的执行时间。 GPU的庞大并行计算能力使其成为加速CNN的理想平台之一，并开发了一些基于GPU的CNN库。现有的工作主要集中在CNN的计算效率上，CNN的记忆效率在很大程度上被忽略了。然而CNN具有错综复杂的数据结构，其记忆行为会对性能产生重大影响。在这项工作中，我们研究了各种CNN层的内存效率，揭示了数据布局和内存访问模式的性能意义。实验表明，我们提出的优化对单层和各种网络的普遍影响，单层高达27.9倍，整个网络高达5.6倍。

##### URL
[https://arxiv.org/abs/1610.03618](https://arxiv.org/abs/1610.03618)

##### PDF
[https://arxiv.org/pdf/1610.03618](https://arxiv.org/pdf/1610.03618)

