---
layout: post
title: "Caffe con Troll: Shallow Ideas to Speed Up Deep Learning"
date: 2015-05-26 20:12:33
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Stefan Hadjis, Firas Abuzaid, Ce Zhang, Christopher Ré
mathjax: true
---

* content
{:toc}

##### Abstract
We present Caffe con Troll (CcT), a fully compatible end-to-end version of the popular framework Caffe with rebuilt internals. We built CcT to examine the performance characteristics of training and deploying general-purpose convolutional neural networks across different hardware architectures. We find that, by employing standard batching optimizations for CPU training, we achieve a 4.5x throughput improvement over Caffe on popular networks like CaffeNet. Moreover, with these improvements, the end-to-end training time for CNNs is directly proportional to the FLOPS delivered by the CPU, which enables us to efficiently train hybrid CPU-GPU systems for CNNs.

##### Abstract (translated by Google)
我们提供Caffe con巨魔（CcT），一个完全兼容的流行框架Caffe与重建内部的端到端版本。我们构建了CcT来检查训练的性能特征，并在不同的硬件架构上部署通用卷积神经网络。我们发现，通过对CPU培训进行标准批量优化，我们在CaffeNet等流行网络上的吞吐量提高了4.5倍。此外，通过这些改进，CNN的端到端培训时间与CPU提供的FLOPS成正比，这使我们能够有效地培训CNN的混合CPU-GPU系统。

##### URL
[https://arxiv.org/abs/1504.04343](https://arxiv.org/abs/1504.04343)

##### PDF
[https://arxiv.org/pdf/1504.04343](https://arxiv.org/pdf/1504.04343)

