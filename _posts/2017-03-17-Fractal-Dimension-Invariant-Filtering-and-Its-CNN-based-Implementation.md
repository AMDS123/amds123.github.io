---
layout: post
title: "Fractal Dimension Invariant Filtering and Its CNN-based Implementation"
date: 2017-03-17 03:10:56
categories: arXiv_CV
tags: arXiv_CV
author: Hongteng Xu, Junchi Yan, Nils Persson, Weiyao Lin, Hongyuan Zha
mathjax: true
---

* content
{:toc}

##### Abstract
Fractal analysis has been widely used in computer vision, especially in texture image processing and texture analysis. The key concept of fractal-based image model is the fractal dimension, which is invariant to bi-Lipschitz transformation of image, and thus capable of representing intrinsic structural information of image robustly. However, the invariance of fractal dimension generally does not hold after filtering, which limits the application of fractal-based image model. In this paper, we propose a novel fractal dimension invariant filtering (FDIF) method, extending the invariance of fractal dimension to filtering operations. Utilizing the notion of local self-similarity, we first develop a local fractal model for images. By adding a nonlinear post-processing step behind anisotropic filter banks, we demonstrate that the proposed filtering method is capable of preserving the local invariance of the fractal dimension of image. Meanwhile, we show that the FDIF method can be re-instantiated approximately via a CNN-based architecture, where the convolution layer extracts anisotropic structure of image and the nonlinear layer enhances the structure via preserving local fractal dimension of image. The proposed filtering method provides us with a novel geometric interpretation of CNN-based image model. Focusing on a challenging image processing task --- detecting complicated curves from the texture-like images, the proposed method obtains superior results to the state-of-art approaches.

##### Abstract (translated by Google)
分形分析在计算机视觉领域得到了广泛的应用，特别是在纹理图像处理和纹理分析方面。分形图像模型的关键概念是分形维数，它对图像的双Lipschitz变换不变，从而能够鲁棒地表示图像的内在结构信息。然而，分形维数的不变性一般在滤波后不成立，这限制了分形图像模型的应用。在本文中，我们提出了一种新的分形维不变滤波（FDIF）方法，将分维的不变性扩展到滤波操作。利用局部自相似的概念，我们首先开发一个局部的图像分形模型。通过在各向异性滤波器组之后添加非线性后处理步骤，我们证明了所提出的滤波方法能够保持图像分形维的局部不变性。同时，我们证明FDIF方法可以通过基于CNN的体系结构重新实例化，其中卷积层提取图像的各向异性结构，非线性层通过保留图像局部分形维来增强结构。所提出的滤波方法为我们提供了一种基于CNN的图像模型的新颖的几何解释。针对具有挑战性的图像处理任务 - 从类似纹理的图像中检测复杂的曲线，所提出的方法获得了优越的结果，以现有技术的方法。

##### URL
[https://arxiv.org/abs/1603.06036](https://arxiv.org/abs/1603.06036)

##### PDF
[https://arxiv.org/pdf/1603.06036](https://arxiv.org/pdf/1603.06036)

