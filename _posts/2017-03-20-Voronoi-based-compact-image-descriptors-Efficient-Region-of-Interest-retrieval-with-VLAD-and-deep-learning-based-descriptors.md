---
layout: post
title: "Voronoi-based compact image descriptors: Efficient Region-of-Interest retrieval with VLAD and deep-learning-based descriptors"
date: 2017-03-20 18:37:56
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN
author: Aaron Chadha, Yiannis Andreopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of image retrieval based on visual queries when the latter comprise arbitrary regions-of-interest (ROI) rather than entire images. Our proposal is a compact image descriptor that combines the state-of-the-art in content-based descriptor extraction with a multi-level, Voronoi-based spatial partitioning of each dataset image. The proposed multi-level Voronoi-based encoding uses a spatial hierarchical K-means over interest-point locations, and computes a content-based descriptor over each cell. In order to reduce the matching complexity with minimal or no sacrifice in retrieval performance: (i) we utilize the tree structure of the spatial hierarchical K-means to perform a top-to-bottom pruning for local similarity maxima; (ii) we propose a new image similarity score that combines relevant information from all partition levels into a single measure for similarity; (iii) we combine our proposal with a novel and efficient approach for optimal bit allocation within quantized descriptor representations. By deriving both a Voronoi-based VLAD descriptor (termed as Fast-VVLAD) and a Voronoi-based deep convolutional neural network (CNN) descriptor (termed as Fast-VDCNN), we demonstrate that our Voronoi-based framework is agnostic to the descriptor basis, and can easily be slotted into existing frameworks. Via a range of ROI queries in two standard datasets, it is shown that the Voronoi-based descriptors achieve comparable or higher mean Average Precision against conventional grid-based spatial search, while offering more than two-fold reduction in complexity. Finally, beyond ROI queries, we show that Voronoi partitioning improves the geometric invariance of compact CNN descriptors, thereby resulting in competitive performance to the current state-of-the-art on whole image retrieval.

##### Abstract (translated by Google)
当后者包含任意兴趣区域（ROI）而不是整个图像时，我们研究基于视觉查询的图像检索问题。我们的建议是一个紧凑的图像描述符，结合了基于内容的描述符提取与基于Voronoi的多层次空间划分的每个数据集图像。所提出的多级基于Voronoi的编码在兴趣点位置上使用空间分层K均值，并计算每个小区上的基于内容的描述符。为了减少匹配的复杂性，在牺牲检索性能的同时减少或不牺牲：（1）我们利用空间层次K-means的树结构对局部相似度最大值进行从上到下的修剪; （ii）我们提出了一个新的图像相似度分数，它将来自所有分区级别的相关信息组合成一个单一的相似度量; （iii）我们将我们的建议与在量化描述符表示内的最佳比特分配的新颖且有效的方法相结合。通过推导基于Voronoi的VLAD描述符（称为Fast-VVLAD）和基于Voronoi的深度卷积神经网络（CNN）描述符（称为Fast-VDCNN），我们证明了基于Voronoi的框架与描述符不可知基础上，可以很容易地插入到现有的框架。通过两个标准数据集中的一系列ROI查询，可以看出，基于Voronoi的描述符相对于传统的基于网格的空间搜索实现了可比较的或更高的平均平均精度，同时提供了两倍以上的复杂度降低。最后，除了ROI查询之外，我们还证明了Voronoi划分提高了紧凑CNN描述符的几何不变性，从而在整个图像检索中获得了当前最先进的竞争性能。

##### URL
[https://arxiv.org/abs/1611.08906](https://arxiv.org/abs/1611.08906)

##### PDF
[https://arxiv.org/pdf/1611.08906](https://arxiv.org/pdf/1611.08906)

