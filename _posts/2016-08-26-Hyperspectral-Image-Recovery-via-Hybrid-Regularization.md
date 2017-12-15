---
layout: post
title: "Hyperspectral Image Recovery via Hybrid Regularization"
date: 2016-08-26 02:27:31
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge
author: Reza Arablouei, Frank de Hoog
mathjax: true
---

* content
{:toc}

##### Abstract
Natural images tend to mostly consist of smooth regions with individual pixels having highly correlated spectra. This information can be exploited to recover hyperspectral images of natural scenes from their incomplete and noisy measurements. To perform the recovery while taking full advantage of the prior knowledge, we formulate a composite cost function containing a square-error data-fitting term and two distinct regularization terms pertaining to spatial and spectral domains. The regularization for the spatial domain is the sum of total-variation of the image frames corresponding to all spectral bands. The regularization for the spectral domain is the l1-norm of the coefficient matrix obtained by applying a suitable sparsifying transform to the spectra of the pixels. We use an accelerated proximal-subgradient method to minimize the formulated cost function. We analyze the performance of the proposed algorithm and prove its convergence. Numerical simulations using real hyperspectral images exhibit that the proposed algorithm offers an excellent recovery performance with a number of measurements that is only a small fraction of the hyperspectral image data size. Simulation results also show that the proposed algorithm significantly outperforms an accelerated proximal-gradient algorithm that solves the classical basis-pursuit denoising problem to recover the hyperspectral image.

##### Abstract (translated by Google)
自然图像往往主要由具有高度相关光谱的单个像素的平滑区域组成。这个信息可以被利用来从其不完整和噪声的测量中恢复自然场景的高光谱图像。为了在充分利用先验知识的情况下进行恢复，我们制定了一个复合成本函数，其中包含一个平方误差的数据拟合项和两个与空间和频谱域有关的不同的正则化项。空间域的正则化是对应于所有光谱带的图像帧的总变化量的总和。谱域的正则化是通过对像素的谱应用适当的稀疏变换获得的系数矩阵的l1范数。我们使用一种加速的近端次梯度方法来最小化所制定的成本函数。分析了算法的性能，证明了算法的收敛性。使用真实高光谱图像的数值模拟表明，所提出的算法提供了优异的恢复性能，其中多个测量仅仅是高光谱图像数据大小的一小部分。仿真结果也表明，该算法明显优于加速近谱梯度算法，解决了经典基追踪去噪问题以恢复高光谱图像。

##### URL
[https://arxiv.org/abs/1511.02928](https://arxiv.org/abs/1511.02928)

##### PDF
[https://arxiv.org/pdf/1511.02928](https://arxiv.org/pdf/1511.02928)

