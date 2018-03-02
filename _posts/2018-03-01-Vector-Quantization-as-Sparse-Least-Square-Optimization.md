---
layout: post
title: "Vector Quantization as Sparse Least Square Optimization"
date: 2018-03-01 04:07:40
categories: arXiv_AI
tags: arXiv_AI Sparse Optimization Recognition
author: Chen Wang, Ruisen Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Vector quantization aims to form new vectors/matrices with shared values close to the original. It could compress data with acceptable information loss, and could be of great usefulness in areas like Image Processing, Pattern Recognition and Machine Learning. In recent years, the importance of quantization has been soaring as it has been discovered huge potentials in deploying practical neural networks, which is among one of the most popular research topics. Conventional vector quantization methods usually suffer from their own flaws: hand-coding domain rules quantization could produce poor results when encountering complex data, and clustering-based algorithms have the problem of inexact solution and high time consumption. In this paper, we explored vector quantization problem from a new perspective of sparse least square optimization and designed multiple algorithms with their program implementations. Specifically, deriving from a sparse form of coefficient matrix, three types of sparse least squares, with $l_0$, $l_1$, and generalized $l_1 + l_2$ penalizations, are designed and implemented respectively. In addition, to produce quantization results with given amount of quantized values(instead of penalization coefficient $\lambda$), this paper proposed a cluster-based least square quantization method, which could also be regarded as an improvement of information preservation of conventional clustering algorithm. The algorithms were tested on various data and tasks and their computational properties were analyzed. The paper offers a new perspective to probe the area of vector quantization, while the algorithms proposed could provide more appropriate options for quantization tasks under different circumstances.

##### Abstract (translated by Google)
矢量量化旨在形成具有接近原始值的共享值的新矢量/矩阵。它可以压缩可接受的信息损失的数据，并且在图像处理，模式识别和机器学习等领域可能非常有用。近年来，量化的重要性一直在飞涨，因为它已经发现了部署实用神经网络的巨大潜力，这是最受欢迎的研究课题之一。传统的矢量量化方法通常存在着自身的缺陷：当遇到复杂的数据时，手编码域规则量化可能会产生较差的结果，并且基于聚类的算法存在不精确的解决方案和高时间消耗的问题。在本文中，我们从稀疏最小二乘优化的角度探讨了矢量量化问题，并设计了多种算法及其程序实现。具体而言，从稀疏形式的系数矩阵导出，分别设计和实现了三种类型的稀疏最小二乘，分别为$ l_0 $，$ l_1 $和广义$ l_1 + l_2 $惩罚。此外，为了产生具有给定量化值的量化结果（而不是惩罚系数$ \ lambda $），本文提出了一种基于聚类的最小二乘量化方法，该方法也可以被认为是对常规聚类的信息保存的改进算法。对算法进行了各种数据和任务的测试，并对其计算特性进行了分析。本文为探究矢量量化领域提供了一个新的视角，而提出的算法可以为不同情况下的量化任务提供更合适的选择。

##### URL
[http://arxiv.org/abs/1803.00204](http://arxiv.org/abs/1803.00204)

##### PDF
[http://arxiv.org/pdf/1803.00204](http://arxiv.org/pdf/1803.00204)

