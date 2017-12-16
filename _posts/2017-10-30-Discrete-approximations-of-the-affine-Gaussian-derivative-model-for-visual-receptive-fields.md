---
layout: post
title: "Discrete approximations of the affine Gaussian derivative model for visual receptive fields"
date: 2017-10-30 14:59:02
categories: arXiv_CV
tags: arXiv_CV
author: Tony Lindeberg
mathjax: true
---

* content
{:toc}

##### Abstract
The affine Gaussian derivative model can in several respects be regarded as a canonical model for receptive fields over a spatial image domain: (i) it can be derived by necessity from scale-space axioms that reflect structural properties of the world, (ii) it constitutes an excellent model for the receptive fields of simple cells in the primary visual cortex and (iii) it is covariant under affine image deformations, which enables more accurate modelling of image measurements under the local image deformations caused by the perspective mapping, compared to the more commonly used Gaussian derivative model based on derivatives of the rotationally symmetric Gaussian kernel. This paper presents a theory for discretizing the affine Gaussian scale-space concept underlying the affine Gaussian derivative model, so that scale-space properties hold also for the discrete implementation. Two ways of discretizing spatial smoothing with affine Gaussian kernels are presented: (i) by solving semi-discretized affine diffusion equation, which has derived by necessity from the requirements of a semi-group structure over scale as parameterized by a family of spatial covariance matrices and obeying non-creation of new structures from any finer to any coarser scale in terms of non-enhancement of local extrema and (ii) approximating these semi-discrete affine receptive fields by parameterized families of 3x3-kernels as obtained from an additional discretization along the scale direction. The latter discrete approach can be optionally complemented by spatial subsampling at coarser scales, leading to the notion of affine hybrid pyramids. Using these theoretical results, we outline hybrid architectures for discrete approximations of affine covariant receptive field families, to be used as a first processing layer for affine covariant and affine invariant visual operations at higher levels.

##### Abstract (translated by Google)
仿射高斯导数模型可以在几个方面被认为是一个空间图像域上的感受域的典范模型：（i）它可以从必要的反映结构特性的尺度空间公理得到，（ii）它构成了原始视皮层中简单细胞的感受野的一个优秀模型，并且（iii）在仿射图像变形下是协变的，这使得在透视映射引起的局部图像变形下更精确地建模图像测量结果基于旋转对称高斯核导数的更常用的高斯导数模型。本文提出了离散化仿射高斯导数模型下的仿射高斯尺度空间概念的理论，使得尺度空间性质也适用于离散实现。提出了两种利用仿射高斯核离散化空间平滑的方法：（i）通过求解半离散化的仿射扩散方程，该方程必须根据半尺寸结构规模的要求由空间协方差矩阵族参数化并且服从非增强的新结构，从非增强的局部极值方面来说，也不会产生新的结构;（2）通过附加离散得到的参数化的3×3核函数族来近似这些半离散的仿射感受域规模方向。后者的离散方法可以通过在较粗尺度上的空间子采样来选择性地补充，从而导致仿射混合金字塔的概念。利用这些理论结果，我们概述了仿射协变感受域族的离散逼近的混合结构，作为仿射协变和仿射不变视觉操作的第一个处理层。

##### URL
[https://arxiv.org/abs/1701.02127](https://arxiv.org/abs/1701.02127)

##### PDF
[https://arxiv.org/pdf/1701.02127](https://arxiv.org/pdf/1701.02127)

