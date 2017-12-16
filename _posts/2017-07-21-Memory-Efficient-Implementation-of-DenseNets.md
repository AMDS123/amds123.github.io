---
layout: post
title: "Memory-Efficient Implementation of DenseNets"
date: 2017-07-21 17:51:36
categories: arXiv_CV
tags: arXiv_CV Classification
author: Geoff Pleiss, Danlu Chen, Gao Huang, Tongcheng Li, Laurens van der Maaten, Kilian Q. Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
The DenseNet architecture is highly computationally efficient as a result of feature reuse. However, a naive DenseNet implementation can require a significant amount of GPU memory: If not properly managed, pre-activation batch normalization and contiguous convolution operations can produce feature maps that grow quadratically with network depth. In this technical report, we introduce strategies to reduce the memory consumption of DenseNets during training. By strategically using shared memory allocations, we reduce the memory cost for storing feature maps from quadratic to linear. Without the GPU memory bottleneck, it is now possible to train extremely deep DenseNets. Networks with 14M parameters can be trained on a single GPU, up from 4M. A 264-layer DenseNet (73M parameters), which previously would have been infeasible to train, can now be trained on a single workstation with 8 NVIDIA Tesla M40 GPUs. On the ImageNet ILSVRC classification dataset, this large DenseNet obtains a state-of-the-art single-crop top-1 error of 20.26%.

##### Abstract (translated by Google)
DenseNet体系结构由于特性重用而具有很高的计算效率。然而，一个天真的DenseNet实现可能需要大量的GPU内存：如果管理不当，预激活批量规范化和连续卷积操作可以生成随网络深度二次增长的特征映射。在这份技术报告中，我们介绍了在培训期间减少DenseNets内存消耗的策略。通过战略性地使用共享内存分配，我们减少了将特征映射从二次到线性存储的内存成本。没有GPU内存瓶颈，现在可以训练非常深的DenseNets。具有14M参数的网络可以在单个GPU上训练，从4M到4M。现在可以在一台带有8个NVIDIA Tesla M40 GPU的工作站上训练以前不可能训练的264层DenseNet（73M参数）。在ImageNet ILSVRC分类数据集上，这个大型的DenseNet获得了20.26％的最先进的单庄稼top-1错误。

##### URL
[https://arxiv.org/abs/1707.06990](https://arxiv.org/abs/1707.06990)

##### PDF
[https://arxiv.org/pdf/1707.06990](https://arxiv.org/pdf/1707.06990)

