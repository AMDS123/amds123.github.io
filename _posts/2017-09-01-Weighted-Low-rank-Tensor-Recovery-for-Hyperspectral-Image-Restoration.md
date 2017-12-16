---
layout: post
title: "Weighted Low-rank Tensor Recovery for Hyperspectral Image Restoration"
date: 2017-09-01 07:58:34
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Relation
author: Yi Chang, Luxin Yan, Houzhang Fang, Sheng Zhong, Zhijun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral imaging, providing abundant spatial and spectral information simultaneously, has attracted a lot of interest in recent years. Unfortunately, due to the hardware limitations, the hyperspectral image (HSI) is vulnerable to various degradations, such noises (random noise, HSI denoising), blurs (Gaussian and uniform blur, HSI deblurring), and down-sampled (both spectral and spatial downsample, HSI super-resolution). Previous HSI restoration methods are designed for one specific task only. Besides, most of them start from the 1-D vector or 2-D matrix models and cannot fully exploit the structurally spectral-spatial correlation in 3-D HSI. To overcome these limitations, in this work, we propose a unified low-rank tensor recovery model for comprehensive HSI restoration tasks, in which non-local similarity between spectral-spatial cubic and spectral correlation are simultaneously captured by 3-order tensors. Further, to improve the capability and flexibility, we formulate it as a weighted low-rank tensor recovery (WLRTR) model by treating the singular values differently, and study its analytical solution. We also consider the exclusive stripe noise in HSI as the gross error by extending WLRTR to robust principal component analysis (WLRTR-RPCA). Extensive experiments demonstrate the proposed WLRTR models consistently outperform state-of-the-arts in typical low level vision HSI tasks, including denoising, destriping, deblurring and super-resolution.

##### Abstract (translated by Google)
高光谱成像，同时提供丰富的空间和光谱信息，近年来引起了人们极大的兴趣。不幸的是，由于硬件限制，高光谱图像（HSI）容易受到各种降级，诸如噪声（随机噪声，HSI去噪），模糊（高斯和均匀模糊，HSI去模糊）和降采样（光谱和空间降采样，HSI超分辨率）。以前的HSI恢复方法只针对一个特定的任务。另外，它们大多从一维矢量或二维矩阵模型开始，不能充分利用三维恒虚模型中的结构光谱空间相关性。为了克服这些局限性，本文提出了一个统一的低秩张量恢复模型，用于全面的HSI恢复任务，利用三阶张量同时捕获谱空间三次和谱相关的非局部相似性。此外，为了提高能力和灵活性，我们将奇异值分解为加权低秩张量恢复（WLRTR）模型，并研究其解析解。通过将WLRTR扩展到鲁棒主成分分析（WLRTR-RPCA），我们还将HSI中的独占条纹噪声视为总误差。广泛的实验证明，所提出的WLRTR模型在典型的低水平视觉HSI任务中始终优于现有技术，包括去噪，去模糊，去模糊和超分辨率。

##### URL
[https://arxiv.org/abs/1709.00192](https://arxiv.org/abs/1709.00192)

##### PDF
[https://arxiv.org/pdf/1709.00192](https://arxiv.org/pdf/1709.00192)

