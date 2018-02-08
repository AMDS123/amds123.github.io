---
layout: post
title: "Universal Deep Neural Network Compression"
date: 2018-02-07 00:39:56
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference
author: Yoojin Choi, Mostafa El-Khamy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Compression of deep neural networks (DNNs) for memory- and computation-efficient compact feature representations becomes a critical problem particularly for deployment of DNNs on resource-limited platforms. In this paper, we investigate lossy compression of DNNs by weight quantization and lossless source coding for memory-efficient inference. Whereas the previous work addressed non-universal scalar quantization and entropy coding of DNN weights, we for the first time introduce universal DNN compression by universal vector quantization and universal source coding. In particular, we examine universal randomized lattice quantization of DNNs, which randomizes DNN weights by uniform random dithering before lattice quantization and can perform near-optimally on any source without relying on knowledge of its probability distribution. Entropy coding schemes such as Huffman codes require prior calculation of source statistics, which is computationally consuming. Instead, we propose universal lossless source coding schemes such as variants of Lempel-Ziv-Welch or the Burrows-Wheeler transform. Finally, we present the methods of fine-tuning vector quantized DNNs to recover the performance loss after quantization. Our experimental results show that the proposed universal DNN compression scheme achieves compression ratios of 124.80, 47.10 and 42.46 for LeNet5, 32-layer ResNet and AlexNet, respectively.

##### Abstract (translated by Google)
深度神经网络（DNN）的压缩用于内存和计算高效的紧凑特征表示成为一个关键问题，特别是在资源有限的平台上部署DNN。在本文中，我们通过权重量化和无损信源编码来研究DNN的有损压缩以进行内存有效的推断。而以前的工作是针对DNN权重的非通用标量量化和熵编码，首次引入了通用矢量量化和通用信源编码的通用DNN压缩。具体而言，我们研究了DNN的通用随机化晶格量化，其通过在晶格量化之前的均匀随机抖动随机化DNN权重，并且可以在不依赖于其概率分布的知识的情况下在任何源上近乎最佳地执行。诸如霍夫曼码之类的熵编码方案需要事先计算源统计量，这在计算上是消耗的。相反，我们提出通用无损信源编码方案，例如Lempel-Ziv-Welch变体或Burrows-Wheeler变换。最后，提出了对矢量量化DNN进行微调以恢复量化后的性能损失的方法。我们的实验结果表明，所提出的通用DNN压缩方案分别实现了对LeNet5,32层ResNet和AlexNet的压缩比分别为124.80,47.10和42.46。

##### URL
[https://arxiv.org/abs/1802.02271](https://arxiv.org/abs/1802.02271)

##### PDF
[https://arxiv.org/pdf/1802.02271](https://arxiv.org/pdf/1802.02271)

