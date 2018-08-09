---
layout: post
title: "The steerable graph Laplacian and its application to filtering image data-sets"
date: 2018-08-07 19:00:04
categories: arXiv_CV
tags: arXiv_CV
author: Boris Landa, Yoel Shkolnisky
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, improvements in various image acquisition techniques gave rise to the need for adaptive processing methods, aimed particularly for large datasets corrupted by noise and deformations. In this work, we consider datasets of images sampled from a low-dimensional manifold (i.e. an image-valued manifold), where the images can assume arbitrary planar rotations. To derive an adaptive and rotation-invariant framework for processing such datasets, we introduce a graph Laplacian (GL)-like operator over the dataset, termed ${\textit{steerable graph Laplacian}}$. Essentially, the steerable GL extends the standard GL by accounting for all (infinitely-many) planar rotations of all images. As it turns out, similarly to the standard GL, a properly normalized steerable GL converges to the Laplace-Beltrami operator on the low-dimensional manifold. However, the steerable GL admits an improved convergence rate compared to the GL, where the improved convergence behaves as if the intrinsic dimension of the underlying manifold is lower by one. Moreover, it is shown that the steerable GL admits eigenfunctions of the form of Fourier modes (along the orbits of the images' rotations) multiplied by eigenvectors of certain matrices, which can be computed efficiently by the FFT. For image datasets corrupted by noise, we employ a subset of these eigenfunctions to "filter" the dataset via a Fourier-like filtering scheme, essentially using all images and their rotations simultaneously. We demonstrate our filtering framework by de-noising simulated single-particle cryo-EM image datasets.

##### Abstract (translated by Google)
近年来，各种图像采集技术的改进引起了对自适应处理方法的需求，该方法特别针对被噪声和变形破坏的大型数据集。在这项工作中，我们考虑从低维流形（即图像值流形）采样的图像的数据集，其中图像可以呈现任意平面旋转。为了导出用于处理此类数据集的自适应和旋转不变框架，我们在数据集上引入了一个类似拉普拉斯（GL）的运算符，称为$ {\ textit {steerable graph Laplacian}} $。基本上，可转向GL通过考虑所有图像的所有（无限多个）平面旋转来扩展标准GL。事实证明，与标准GL类似，正确归一化的可操纵GL在低维流形上收敛于Laplace-Beltrami算子。然而，与GL相比，可操纵GL允许改进的收敛速度，其中改进的收敛表现为好像下面的歧管的固有尺寸低一。此外，示出了可操纵GL允许傅立叶模式形式的特征函数（沿着图像旋转的轨道）乘以某些矩阵的特征向量，这可以通过FFT有效地计算。对于被噪声破坏的图像数据集，我们使用这些特征函数的子集来通过类似傅立叶的滤波方案“过滤”数据集，基本上同时使用所有图像及其旋转。我们通过对模拟的单粒子低温EM图像数据集进行去噪来演示我们的过滤框架。

##### URL
[http://arxiv.org/abs/1802.01894](http://arxiv.org/abs/1802.01894)

##### PDF
[http://arxiv.org/pdf/1802.01894](http://arxiv.org/pdf/1802.01894)

