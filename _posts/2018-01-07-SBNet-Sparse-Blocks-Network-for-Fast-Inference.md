---
layout: post
title: "SBNet: Sparse Blocks Network for Fast Inference"
date: 2018-01-07 01:03:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Knowledge Segmentation CNN Semantic_Segmentation Inference Classification Detection
author: Mengye Ren, Andrei Pokrovsky, Bin Yang, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional deep convolutional neural networks (CNNs) apply convolution operators uniformly in space across all feature maps for hundreds of layers - this incurs a high computational cost for real time applications. For many problems such as object detection and semantic segmentation, we are able to obtain a low-cost computation mask, either from a priori problem knowledge, or from a low resolution segmentation network. We show that such computation masks can be used to reduce computation in the high resolution main network. Variants of sparse activation CNNs have previously been explored on small scale tasks, and showed no degradation in terms of object classification accuracy, but often measured gains in terms of theoretical FLOPs without realizing a practical speed-up when compared to highly optimized dense convolution implementations. In this work, we leverage the sparsity structure of computation masks and propose a novel tiling-based sparse convolution algorithm. We verified the effectiveness of our sparse CNN on LiDAR based 3D object detection, and we report significant wall-clock speed-ups compared to dense convolution, as well as improved detection accuracy.

##### Abstract (translated by Google)
传统的深度卷积神经网络（CNN）在所有特征图的空间中均匀地将卷积运算符应用于数百个层 - 这为实时应用程序带来了高计算成本。对于诸如对象检测和语义分割等许多问题，我们能够从先验问题知识或低分辨率分割网络中获得低成本的计算掩模。我们证明这样的计算掩模可以用来减少高分辨率主网络中的计算。稀疏激活CNN的变体先前已经在小规模任务上进行了探索，并且在对象分类准确性方面没有显示退化，但是与高度优化的密集卷积实现相比，在理论FLOP方面经常测量增益而没有实现实际的加速。在这项工作中，我们利用计算掩码的稀疏结构，提出了一种新颖的基于稀疏的稀疏卷积算法。我们验证了稀疏CNN在基于LiDAR的三维物体检测上的有效性，并且我们报告了与密集卷积相比显着的时钟加速，以及改进的检测精度。

##### URL
[http://arxiv.org/abs/1801.02108](http://arxiv.org/abs/1801.02108)

##### PDF
[http://arxiv.org/pdf/1801.02108](http://arxiv.org/pdf/1801.02108)

