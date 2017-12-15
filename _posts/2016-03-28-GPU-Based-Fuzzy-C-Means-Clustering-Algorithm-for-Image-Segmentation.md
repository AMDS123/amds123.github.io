---
layout: post
title: "GPU-Based Fuzzy C-Means Clustering Algorithm for Image Segmentation"
date: 2016-03-28 09:47:29
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Mishal Almazrooie, Mogana Vadiveloo, Rosni Abdullah
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a fast and practical GPU-based implementation of Fuzzy C-Means(FCM) clustering algorithm for image segmentation is proposed. First, an extensive analysis is conducted to study the dependency among the image pixels in the algorithm for parallelization. The proposed GPU-based FCM has been tested on digital brain simulated dataset to segment white matter(WM), gray matter(GM) and cerebrospinal fluid (CSF) soft tissue regions. The execution time of the sequential FCM is 519 seconds for an image dataset with the size of 1MB. While the proposed GPU-based FCM requires only 2.33 seconds for the similar size of image dataset. An estimated 245-fold speedup is measured for the data size of 40 KB on a CUDA device that has 448 processors.

##### Abstract (translated by Google)
本文提出了一种快速实用的基于GPU的图像分割模糊C均值（FCM）聚类算法。首先进行广泛的分析，研究并行算法中图像像素间的依赖关系。提出的基于GPU的FCM已经在数字脑模拟数据集上进行测试，以分割白质（WM），灰质（GM）和脑脊液（CSF）软组织区域。对于大小为1MB的图像数据集，顺序FCM的执行时间为519秒。虽然提出的基于GPU的FCM只需要2.33秒的相似大小的图像数据集。估计有448个处理器的CUDA设备的数据量为40 KB时，加速度提高了245倍。

##### URL
[https://arxiv.org/abs/1601.00072](https://arxiv.org/abs/1601.00072)

##### PDF
[https://arxiv.org/pdf/1601.00072](https://arxiv.org/pdf/1601.00072)

