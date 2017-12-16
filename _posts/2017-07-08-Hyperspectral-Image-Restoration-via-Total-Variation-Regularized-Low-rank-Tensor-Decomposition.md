---
layout: post
title: "Hyperspectral Image Restoration via Total Variation Regularized Low-rank Tensor Decomposition"
date: 2017-07-08 18:41:06
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Optimization Relation
author: Yao Wang, Jiangjun Peng, Qian Zhao, Deyu Meng, Yee Leung, Xi-Le Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral images (HSIs) are often corrupted by a mixture of several types of noise during the acquisition process, e.g., Gaussian noise, impulse noise, dead lines, stripes, and many others. Such complex noise could degrade the quality of the acquired HSIs, limiting the precision of the subsequent processing. In this paper, we present a novel tensor-based HSI restoration approach by fully identifying the intrinsic structures of the clean HSI part and the mixed noise part respectively. Specifically, for the clean HSI part, we use tensor Tucker decomposition to describe the global correlation among all bands, and an anisotropic spatial-spectral total variation (SSTV) regularization to characterize the piecewise smooth structure in both spatial and spectral domains. For the mixed noise part, we adopt the $\ell_1$ norm regularization to detect the sparse noise, including stripes, impulse noise, and dead pixels. Despite that TV regulariztion has the ability of removing Gaussian noise, the Frobenius norm term is further used to model heavy Gaussian noise for some real-world scenarios. Then, we develop an efficient algorithm for solving the resulting optimization problem by using the augmented Lagrange multiplier (ALM) method. Finally, extensive experiments on simulated and real-world noise HSIs are carried out to demonstrate the superiority of the proposed method over the existing state-of-the-art ones.

##### Abstract (translated by Google)
高光谱图像（HSI）经常在采集过程中由几种类型的噪声的混合物（例如，高斯噪声，脉冲噪声，死线，条纹等等）破坏。这种复杂的噪声可能会降低所获得的HSI的质量，限制后续处理的精度。在本文中，我们提出了一种新型的基于张量的HSI复原方法，分别完全识别干净的HSI部分和混合噪声部分的内在结构。具体而言，对于干净的HSI部分，我们使用张量Tucker分解来描述所有波段之间的全局相关性，以及各向异性空间谱总变化（SSTV）正则化来表征空间和频谱域中的分段平滑结构。对于混合噪声部分，我们采用$ \ ell_1 $范数正则化来检测稀疏噪声，包括条纹，脉冲噪声和坏点。尽管电视正规化具有消除高斯噪声的能力，但Frobenius范数项还被用于为一些真实世界的场景模拟重度高斯噪声。然后，我们利用增广的拉格朗日乘子（ALM）方法开发了一种有效的求解最优化问题的算法。最后，对模拟噪声和真实噪声HSI进行了广泛的实验，以证明所提出方法优于现有技术的优点。

##### URL
[https://arxiv.org/abs/1707.02477](https://arxiv.org/abs/1707.02477)

##### PDF
[https://arxiv.org/pdf/1707.02477](https://arxiv.org/pdf/1707.02477)

