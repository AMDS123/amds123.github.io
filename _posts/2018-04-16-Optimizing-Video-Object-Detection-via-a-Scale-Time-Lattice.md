---
layout: post
title: "Optimizing Video Object Detection via a Scale-Time Lattice"
date: 2018-04-16 01:52:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse CNN Detection Relation
author: Kai Chen, Jiaqi Wang, Shuo Yang, Xingcheng Zhang, Yuanjun Xiong, Chen Change Loy, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
High-performance object detection relies on expensive convolutional networks to compute features, often leading to significant challenges in applications, e.g. those that require detecting objects from video streams in real time. The key to this problem is to trade accuracy for efficiency in an effective way, i.e. reducing the computing cost while maintaining competitive performance. To seek a good balance, previous efforts usually focus on optimizing the model architectures. This paper explores an alternative approach, that is, to reallocate the computation over a scale-time space. The basic idea is to perform expensive detection sparsely and propagate the results across both scales and time with substantially cheaper networks, by exploiting the strong correlations among them. Specifically, we present a unified framework that integrates detection, temporal propagation, and across-scale refinement on a Scale-Time Lattice. On this framework, one can explore various strategies to balance performance and cost. Taking advantage of this flexibility, we further develop an adaptive scheme with the detector invoked on demand and thus obtain improved tradeoff. On ImageNet VID dataset, the proposed method can achieve a competitive mAP 79.6% at 20 fps, or 79.0% at 62 fps as a performance/speed tradeoff.

##### Abstract (translated by Google)
高性能对象检测依赖于昂贵的卷积网络来计算特征，这经常导致应用中的重大挑战，例如，那些需要实时从视频流中检测对象的应用程序。这个问题的关键是以有效的方式交换效率的准确性，即在保持竞争性能的同时降低计算成本。为了寻求一个良好的平衡，以前的努力通常集中于优化模型架构。本文探讨了另一种方法，即重新分配一个尺度空间的计算。基本思想是稀疏地执行昂贵的检测，并通过大量廉价的网络，通过利用它们之间的强相关性，在大小和时间上传播结果。具体而言，我们提出了一个统一的框架，将检测，时间传播和跨尺度精细化整合到一个Scale-Time格中。在此框架中，可以探索各种策略来平衡性能和成本。利用这种灵活性，我们进一步开发一种自适应方案，并根据需要调用检测器，从而获得改进的折衷。在ImageNet VID数据集中，所提出的方法可以在20fps下达到79.6％的竞争性mAP，或者在62fps下达到79.0％作为性能/速度折衷。

##### URL
[https://arxiv.org/abs/1804.05472](https://arxiv.org/abs/1804.05472)

##### PDF
[https://arxiv.org/pdf/1804.05472](https://arxiv.org/pdf/1804.05472)

