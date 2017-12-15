---
layout: post
title: "A Parallel Framework for Parametric Maximum Flow Problems in Image Segmentation"
date: 2015-12-07 14:08:32
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Vlad Olaru, Mihai Florea, Cristian Sminchisescu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a framework that supports the implementation of parallel solutions for the widespread parametric maximum flow computational routines used in image segmentation algorithms. The framework is based on supergraphs, a special construction combining several image graphs into a larger one, and works on various architectures (multi-core or GPU), either locally or remotely in a cluster of computing nodes. The framework can also be used for performance evaluation of parallel implementations of maximum flow algorithms. We present the case study of a state-of-the-art image segmentation algorithm based on graph cuts, Constrained Parametric Min-Cut (CPMC), that uses the parallel framework to solve parametric maximum flow problems, based on a GPU implementation of the well-known push-relabel algorithm. Our results indicate that real-time implementations based on the proposed techniques are possible.

##### Abstract (translated by Google)
本文提出了一个框架，支持在图像分割算法中使用的广泛的参数最大流量计算例程的并行解决方案的实现。该框架基于超图，一种将多个图像合并为一个大图的特殊结构，可以在各种架构（多核或GPU）上运行，可以在本地或远程计算节点集群中运行。该框架也可用于最大流算法的并行实现的性能评估。我们提出了一种基于图割的约束参数最小割（CPMC）的最先进的图像分割算法的案例研究，该算法使用并行框架来解决参数最大流问题，基于GPU实现着名的push-relabel算法。我们的结果表明，基于所提出的技术的实时实现是可能的。

##### URL
[https://arxiv.org/abs/1509.06004](https://arxiv.org/abs/1509.06004)

##### PDF
[https://arxiv.org/pdf/1509.06004](https://arxiv.org/pdf/1509.06004)

