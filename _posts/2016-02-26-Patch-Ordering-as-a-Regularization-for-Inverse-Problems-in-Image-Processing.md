---
layout: post
title: "Patch-Ordering as a Regularization for Inverse Problems in Image Processing"
date: 2016-02-26 21:31:01
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Gregory Vaksman, Michael Zibulevsky, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work in image processing suggests that operating on (overlapping) patches in an image may lead to state-of-the-art results. This has been demonstrated for a variety of problems including denoising, inpainting, deblurring, and super-resolution. The work reported in [1,2] takes an extra step forward by showing that ordering these patches to form an approximate shortest path can be leveraged for better processing. The core idea is to apply a simple filter on the resulting 1D smoothed signal obtained after the patch-permutation. This idea has been also explored in combination with a wavelet pyramid, leading eventually to a sophisticated and highly effective regularizer for inverse problems in imaging. In this work we further study the patch-permutation concept, and harness it to propose a new simple yet effective regularization for image restoration problems. Our approach builds on the classic Maximum A'posteriori probability (MAP), with a penalty function consisting of a regular log-likelihood term and a novel permutation-based regularization term. Using a plain 1D Laplacian, the proposed regularization forces robust smoothness (L1) on the permuted pixels. Since the permutation originates from patch-ordering, we propose to accumulate the smoothness terms over all the patches' pixels. Furthermore, we take into account the found distances between adjacent patches in the ordering, by weighting the Laplacian outcome. We demonstrate the proposed scheme on a diverse set of problems: (i) severe Poisson image denoising, (ii) Gaussian image denoising, (iii) image deblurring, and (iv) single image super-resolution. In all these cases, we use recent methods that handle these problems as initialization to our scheme. This is followed by an L-BFGS optimization of the above-described penalty function, leading to state-of-the-art results, and especially so for highly ill-posed cases.

##### Abstract (translated by Google)
最近在图像处理方面的工作表明，对图像中的（重叠）块进行操作可能会导致最新的结果。对于包括去噪，修补，去模糊和超解析在内的各种问题已经证明了这一点。在[1,2]中报告的工作向前迈进了一步，表明将这些补丁排列成近似最短路径可以用于更好的处理。其核心思想是对贴片置换后得到的一维平滑信号应用一个简单的滤波器。这个想法也与小波金字塔相结合，最终导致了一个复杂的，高效的正则化成像反演问题。在这项工作中，我们进一步研究贴片置换的概念，并利用它提出一个新的简单而有效的正则化的图像恢复问题。我们的方法建立在经典的最大后验概率（MAP）上，其中惩罚函数由规则的对数似然项和新的基于置换的正则化项组成。使用普通的一维拉普拉斯算子，所提出的正则化强制排列像素的鲁棒光滑度（L1）。由于置换源自贴片排序，因此我们建议在所有贴片的像素上累积平滑项。此外，我们考虑在排序中相邻贴片之间的距离，通过对拉普拉斯结果进行加权。我们证明了提出的方案在不同的问题上：（i）严重的泊松图像去噪，（ii）高斯图像去噪，（iii）图像去模糊，和（iv）单图像超分辨率。在所有这些情况下，我们使用最近处理这些问题的方法作为我们方案的初始化。随后是上述惩罚函数的L-BFGS优化，导致最先进的结果，特别是对于非常不适合的情况。

##### URL
[https://arxiv.org/abs/1602.08510](https://arxiv.org/abs/1602.08510)

##### PDF
[https://arxiv.org/pdf/1602.08510](https://arxiv.org/pdf/1602.08510)

