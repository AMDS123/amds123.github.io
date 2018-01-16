---
layout: post
title: "SuperNeurons: Dynamic GPU Memory Management for Training Deep Neural Networks"
date: 2018-01-13 04:11:41
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Linnan Wang, Jinmian Ye, Yiyang Zhao, Wei Wu, Ang Li, Shuaiwen Leon Song, Zenglin Xu, Tim Kraska
mathjax: true
---

* content
{:toc}

##### Abstract
Going deeper and wider in neural architectures improves the accuracy, while the limited GPU DRAM places an undesired restriction on the network design domain. Deep Learning (DL) practitioners either need change to less desired network architectures, or nontrivially dissect a network across multiGPUs. These distract DL practitioners from concentrating on their original machine learning tasks. We present SuperNeurons: a dynamic GPU memory scheduling runtime to enable the network training far beyond the GPU DRAM capacity. SuperNeurons features 3 memory optimizations, \textit{Liveness Analysis}, \textit{Unified Tensor Pool}, and \textit{Cost-Aware Recomputation}, all together they effectively reduce the network-wide peak memory usage down to the maximal memory usage among layers. We also address the performance issues in those memory saving techniques. Given the limited GPU DRAM, SuperNeurons not only provisions the necessary memory for the training, but also dynamically allocates the memory for convolution workspaces to achieve the high performance. Evaluations against Caffe, Torch, MXNet and TensorFlow have demonstrated that SuperNeurons trains at least 3.2432 deeper network than current ones with the leading performance. Particularly, SuperNeurons can train ResNet2500 that has $10^4$ basic network layers on a 12GB K40c.

##### Abstract (translated by Google)
在神经架构中越来越深入地提高了准确性，而有限的GPU DRAM对网络设计领域造成了不必要的限制。深度学习（DL）从业者或者需要改变为不太期望的网络架构，或者跨越多个GPU来非分裂网络。这些使得DL从业者不能专注于他们原来的机器学习任务。我们提出SuperNeurons：一个动态的GPU内存调度运行时间，使网络训练远远超出了GPU的DRAM容量。 SuperNeurons具有3个内存优化功能\ textit {Liveness Analysis}，\ textit {Unified Tensor Pool}和\ Textit {Cost-Aware Recomputation}，可以有效降低网络峰值内存使用率，层。我们还解决了这些内存节省技术中的性能问题。考虑到GPU DRAM的有限性，SuperNeurons不仅为训练提供了必要的内存，而且还为卷积工作空间动态分配内存以实现高性能。针对Caffe，Torch，MXNet和TensorFlow的评估表明，SuperNeurons训练的网络深度至少为3.2432，比目前的网络具有领先的性能。特别是SuperNeurons可以训练ResNet2500，在12GB的K40c上有$ 10 ^ 4 $的基本网络层。

##### URL
[https://arxiv.org/abs/1801.04380](https://arxiv.org/abs/1801.04380)

##### PDF
[https://arxiv.org/pdf/1801.04380](https://arxiv.org/pdf/1801.04380)

