---
layout: post
title: "Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour"
date: 2017-06-08 16:51:53
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning Recognition
author: Priya Goyal, Piotr Dollár, Ross Girshick, Pieter Noordhuis, Lukasz Wesolowski, Aapo Kyrola, Andrew Tulloch, Yangqing Jia, Kaiming He
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning thrives with large neural networks and large datasets. However, larger networks and larger datasets result in longer training times that impede research and development progress. Distributed synchronous SGD offers a potential solution to this problem by dividing SGD minibatches over a pool of parallel workers. Yet to make this scheme efficient, the per-worker workload must be large, which implies nontrivial growth in the SGD minibatch size. In this paper, we empirically show that on the ImageNet dataset large minibatches cause optimization difficulties, but when these are addressed the trained networks exhibit good generalization. Specifically, we show no loss of accuracy when training with large minibatch sizes up to 8192 images. To achieve this result, we adopt a linear scaling rule for adjusting learning rates as a function of minibatch size and develop a new warmup scheme that overcomes optimization challenges early in training. With these simple techniques, our Caffe2-based system trains ResNet-50 with a minibatch size of 8192 on 256 GPUs in one hour, while matching small minibatch accuracy. Using commodity hardware, our implementation achieves ~90% scaling efficiency when moving from 8 to 256 GPUs. This system enables us to train visual recognition models on internet-scale data with high efficiency.

##### Abstract (translated by Google)
深度学习随着大型神经网络和大型数据集的兴起而兴旺起来。然而，更大的网络和更大的数据集导致更长的培训时间，阻碍了研发进展。分布式同步SGD通过在并行工作者池中划分SGD小型备用数据库，为这个问题提供了一个潜在的解决方案。然而为了使这个计划有效率，每个员工的工作量必须很大，这意味着SGD小批量的大幅增长。在本文中，我们经验地表明，在ImageNet数据集中，大型小型文件系统会导致优化困难，但是当这些问题得到解决时，训练好的网络就会表现出很好的泛化能力。具体来说，我们显示，在大批量的8192图像训练时，不会出现任何精度损失。为了达到这个结果，我们采用线性缩放规则来调整学习率作为小批量的函数，并开发出一种新的热身方案，以克服训练早期的优化挑战。通过这些简单的技术，我们基于Caffe2的系统在一个小时内在256个GPU上训练ResNet-50，其小批量大小为8192个，同时匹配小的小批量精度。使用商品硬件时，我们的实现在从8个GPU移动到256个GPU时实现了〜90％的扩展效率。该系统使我们能够高效率地在互联网规模的数据上训练视觉识别模型。

##### URL
[https://arxiv.org/abs/1706.02677](https://arxiv.org/abs/1706.02677)

##### PDF
[https://arxiv.org/pdf/1706.02677](https://arxiv.org/pdf/1706.02677)

