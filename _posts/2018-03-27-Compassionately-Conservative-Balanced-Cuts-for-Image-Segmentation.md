---
layout: post
title: "Compassionately Conservative Balanced Cuts for Image Segmentation"
date: 2018-03-27 05:42:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding
author: Nathan D. Cahill, Tyler L. Hayes, Renee T. Meinhold, John F. Hamilton
mathjax: true
---

* content
{:toc}

##### Abstract
The Normalized Cut (NCut) objective function, widely used in data clustering and image segmentation, quantifies the cost of graph partitioning in a way that biases clusters or segments that are balanced towards having lower values than unbalanced partitionings. However, this bias is so strong that it avoids any singleton partitions, even when vertices are very weakly connected to the rest of the graph. Motivated by the B\"uhler-Hein family of balanced cut costs, we propose the family of Compassionately Conservative Balanced (CCB) Cut costs, which are indexed by a parameter that can be used to strike a compromise between the desire to avoid too many singleton partitions and the notion that all partitions should be balanced. We show that CCB-Cut minimization can be relaxed into an orthogonally constrained $\ell_{\tau}$-minimization problem that coincides with the problem of computing Piecewise Flat Embeddings (PFE) for one particular index value, and we present an algorithm for solving the relaxed problem by iteratively minimizing a sequence of reweighted Rayleigh quotients (IRRQ). Using images from the BSDS500 database, we show that image segmentation based on CCB-Cut minimization provides better accuracy with respect to ground truth and greater variability in region size than NCut-based image segmentation.

##### Abstract (translated by Google)
在数据聚类和图像分割中广泛使用的归一化切割（NCut）目标函数量化了图形分割的成本，这种方式偏向于具有比不平衡分割低的值的平衡聚类或分段。然而，这种偏见非常强烈，以至于它避免了任何单独分区，即使顶点与图的其余部分非常弱地连接。在平衡削减成本的Bühler-Hein家族的推动下，我们提出了一系列合乎情理的保守平衡（CCB）削减成本，这些成本由一个参数索引，可用于避免太多单个分区和所有分区应该平衡的概念，我们证明CCB-Cut最小化可以放松到一个正交约束问题中，这个问题与计算分段平坦嵌入（PFE）的问题相一致，对于一个特定的索引值，我们提出了一种通过迭代地最小化重新加权的瑞利商（IRRQ）序列来解决松弛问题的算法。使用来自BSDS500数据库的图像，我们显示基于CCB切割最小化的图像分割提供更好的准确性相对于基于NCut的图像分割的地面真实性和区域大小的更大变化性。

##### URL
[https://arxiv.org/abs/1803.09903](https://arxiv.org/abs/1803.09903)

##### PDF
[https://arxiv.org/pdf/1803.09903](https://arxiv.org/pdf/1803.09903)

