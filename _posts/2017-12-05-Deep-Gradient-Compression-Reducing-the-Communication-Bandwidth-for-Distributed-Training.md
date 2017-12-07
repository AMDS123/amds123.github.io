---
layout: post
title: "Deep Gradient Compression: Reducing the Communication Bandwidth for Distributed Training"
date: 2017-12-05 19:48:11
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Image_Classification Classification Language_Model Recognition
author: Yujun Lin, Song Han, Huizi Mao, Yu Wang, William J. Dally
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale distributed training requires significant communication bandwidth for gradient exchange that limits the scalability of multi-node training, and requires expensive high-bandwidth network infrastructure. The situation gets even worse with distributed training on mobile devices (federated learning), which suffers from higher latency, lower throughput, and intermittent poor connections. In this paper, we find 99.9% of the gradient exchange in distributed SGD is redundant, and propose Deep Gradient Compression (DGC) to greatly reduce the communication bandwidth. To preserve accuracy during compression, DGC employs four methods: momentum correction, local gradient clipping, momentum factor masking, and warm-up training. We have applied Deep Gradient Compression to image classification, speech recognition, and language modeling with multiple datasets including Cifar10, ImageNet, Penn Treebank, and Librispeech Corpus. On these scenarios, Deep Gradient Compression achieves a gradient compression ratio from 270x to 600x without losing accuracy, cutting the gradient size of ResNet-50 from 97MB to 0.35MB, and for DeepSpeech from 488MB to 0.74MB. Deep gradient compression enables large-scale distributed training on inexpensive commodity 1Gbps Ethernet and facilitates distributed training on mobile.

##### Abstract (translated by Google)
大规模分布式培训需要大量的梯度交换通信带宽，这限制了多节点培训的可扩展性，并且需要昂贵的高带宽网络基础设施。在移动设备（联合学习）上进行分布式培训会使情况变得更糟，因为这种培训存在延迟时间更长，吞吐量更低以及连接间歇性差等问题。在本文中，我们发现分布式SGD中99.9％的梯度交换是冗余的，并且提出了深度梯度压缩（DGC）以大大降低通信带宽。为了在压缩过程中保持准确性，DGC采用了四种方法：动量校正，局部梯度裁剪，动量因子掩盖和热身训练。我们已经将深梯度压缩应用于图像分类，语音识别和语言建模，包括Cifar10，ImageNet，Penn Treebank和Librispeech Corpus等多个数据集。在这些场景中，Deep Gradient Compression可实现从270x到600x的梯度压缩比，而不会降低准确性，ResNet-50的梯度大小从97MB降至0.35MB，DeepSpeech从488MB降至0.74MB。深度压缩能够在廉价商品1Gbps以太网上进行大规模的分布式培训，并促进移动设备上的分布式培训。

##### URL
[http://arxiv.org/abs/1712.01887](http://arxiv.org/abs/1712.01887)

##### PDF
[http://arxiv.org/pdf/1712.01887](http://arxiv.org/pdf/1712.01887)

