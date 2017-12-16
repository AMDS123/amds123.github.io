---
layout: post
title: "Efficiently Computing Piecewise Flat Embeddings for Data Clustering and Image Segmentation"
date: 2016-12-20 03:06:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding
author: Renee T. Meinhold, Tyler L. Hayes, Nathan D. Cahill
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is a popular area of research in computer vision that has many applications in automated image processing. A recent technique called piecewise flat embeddings (PFE) has been proposed for use in image segmentation; PFE transforms image pixel data into a lower dimensional representation where similar pixels are pulled close together and dissimilar pixels are pushed apart. This technique has shown promising results, but its original formulation is not computationally feasible for large images. We propose two improvements to the algorithm for computing PFE: first, we reformulate portions of the algorithm to enable various linear algebra operations to be performed in parallel; second, we propose utilizing an iterative linear solver (preconditioned conjugate gradient) to quickly solve a linear least-squares problem that occurs in the inner loop of a nested iteration. With these two computational improvements, we show on a publicly available image database that PFE can be sped up by an order of magnitude without sacrificing segmentation performance. Our results make this technique more practical for use on large data sets, not only for image segmentation, but for general data clustering problems.

##### Abstract (translated by Google)
图像分割是计算机视觉领域的一个热门研究领域，在自动图像处理中有很多应用。最近提出了一种称为分段平坦嵌入（PFE）的技术用于图像分割。 PFE将图像像素数据转换成较低维度表示，其中类似的像素被拉近在一起，并且不相似的像素被分开。这种技术已经显示出有希望的结果，但是对于大的图像来说，其原始公式在计算上是不可行的。我们对计算PFE的算法提出了两个改进：首先，我们重新构造算法的各个部分，使各种线性代数运算能够并行执行;其次，我们提出利用迭代线性求解器（预条件共轭梯度）来快速求解在嵌套迭代的内循环中发生的线性最小二乘问题。有了这两个计算改进，我们在一个公开的图像数据库上显示PFE可以加速一个数量级而不牺牲分割性能。我们的结果使这种技术更适用于大数据集，不仅用于图像分割，还用于一般数据聚类问题。

##### URL
[https://arxiv.org/abs/1612.06496](https://arxiv.org/abs/1612.06496)

##### PDF
[https://arxiv.org/pdf/1612.06496](https://arxiv.org/pdf/1612.06496)

