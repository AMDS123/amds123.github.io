---
layout: post
title: "Billion-scale similarity search with GPUs"
date: 2017-02-28 10:42:31
categories: arXiv_CV
tags: arXiv_CV
author: Jeff Johnson, Matthijs Douze, Hervé Jégou
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity search finds application in specialized database systems handling complex data such as images or videos, which are typically represented by high-dimensional features and require specific indexing structures. This paper tackles the problem of better utilizing GPUs for this task. While GPUs excel at data-parallel tasks, prior approaches are bottlenecked by algorithms that expose less parallelism, such as k-min selection, or make poor use of the memory hierarchy. We propose a design for k-selection that operates at up to 55% of theoretical peak performance, enabling a nearest neighbor implementation that is 8.5x faster than prior GPU state of the art. We apply it in different similarity search scenarios, by proposing optimized design for brute-force, approximate and compressed-domain search based on product quantization. In all these setups, we outperform the state of the art by large margins. Our implementation enables the construction of a high accuracy k-NN graph on 95 million images from the Yfcc100M dataset in 35 minutes, and of a graph connecting 1 billion vectors in less than 12 hours on 4 Maxwell Titan X GPUs. We have open-sourced our approach for the sake of comparison and reproducibility.

##### Abstract (translated by Google)
相似性搜索可以在处理复杂数据（如图像或视频）的专用数据库系统中找到应用，这些数据通常由高维特征表示，并且需要特定的索引结构。本文解决了更好地利用GPU执行此任务的问题。虽然GPU在数据并行任务方面表现出色，但是先前的方法却遇到了诸如k-min选择之类的并行性较差的算法，或者对存储器层次结构的使用较差。我们提出了一个k选择的设计，其运算速度高达55％的理论峰值性能，使最近邻居的实现比先前的GPU状态快8.5倍。将其应用于不同的相似搜索场景，提出了基于产品量化的蛮力，近似和压缩域搜索的优化设计。在所有这些设置中，我们都以大幅度的优势领先于现有技术。我们的实施使得能够在35分钟内从Yfcc100M数据集中构建9500万图像的高精度k-NN图，并且在4个Maxwell Titan X GPU上在不到12小时内连接10亿个矢量图。为了比较和重现性，我们开放了我们的方法。

##### URL
[https://arxiv.org/abs/1702.08734](https://arxiv.org/abs/1702.08734)

##### PDF
[https://arxiv.org/pdf/1702.08734](https://arxiv.org/pdf/1702.08734)

