---
layout: post
title: "A Region Based Easy Path Wavelet Transform For Sparse Image Representation"
date: 2017-02-15 10:41:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sparse Segmentation Relation
author: Renato Budinich
mathjax: true
---

* content
{:toc}

##### Abstract
The Easy Path Wavelet Transform is an adaptive transform for bivariate functions (in particular natural images) which has been proposed in [1]. It provides a sparse representation by finding a path in the domain of the function leveraging the local correlations of the function values. It then applies a one dimensional wavelet transform to the obtained vector, decimates the points and iterates the procedure. The main drawback of such method is the need to store, for each level of the transform, the path which vectorizes the two dimensional data. Here we propose a variation on the method which consists of firstly applying a segmentation procedure to the function domain, partitioning it into regions where the variation in the function values is low; in a second step, inside each such region, a path is found in some deterministic way, i.e. not data-dependent. This circumvents the need to store the paths at each level, while still obtaining good quality lossy compression. This method is particularly well suited to encode a Region of Interest in the image with different quality than the rest of the image. [1] Gerlind Plonka. The easy path wavelet transform: A new adaptive wavelet transform for sparse representation of two-dimensional data. Multiscale Modeling & Simulation, 7(3):1474$-$1496, 2008.

##### Abstract (translated by Google)
简易路径小波变换是对[1]中提出的二元函数（特别是自然图像）的自适应变换。它通过在函数的域中找到利用函数值的局部相关性的路径来提供稀疏表示。然后对所获得的矢量应用一维小波变换，抽取点并迭代该过程。这种方法的主要缺点是需要为变换的每个级别存储矢量化二维数据的路径。在这里我们提出了一种变化的方法，首先将分割过程应用于函数域，将其分割成函数值变化较小的区域;在第二步中，在每个这样的区域内，以某种确定的方式找到路径，即不是数据相关的。这避免了需要存储每个级别的路径，同时仍然获得良好质量的有损压缩。该方法特别适合于以与图像的其余部分不同的质量对图像中的感兴趣区域进行编码。 [1] Gerlind Plonka。易路径小波变换：一种新的自适应小波变换用于二维数据的稀疏表示。多尺度建模与模拟，7（3）：1474 $  -  $ 1496，2008。

##### URL
[https://arxiv.org/abs/1702.01961](https://arxiv.org/abs/1702.01961)

##### PDF
[https://arxiv.org/pdf/1702.01961](https://arxiv.org/pdf/1702.01961)

