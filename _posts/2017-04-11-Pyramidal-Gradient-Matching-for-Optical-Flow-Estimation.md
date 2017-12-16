---
layout: post
title: "Pyramidal Gradient Matching for Optical Flow Estimation"
date: 2017-04-11 09:38:52
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Yuanwei Li
mathjax: true
---

* content
{:toc}

##### Abstract
Initializing optical flow field by either sparse descriptor matching or dense patch matches has been proved to be particularly useful for capturing large displacements. In this paper, we present a pyramidal gradient matching approach that can provide dense matches for highly accurate and efficient optical flow estimation. A novel contribution of our method is that image gradient is used to describe image patches and proved to be able to produce robust matching. Therefore, our method is more efficient than methods that adopt special features (like SIFT) or patch distance metric. Moreover, we find that image gradient is scalable for optical flow estimation, which means we can use different levels of gradient feature (for example, full gradients or only direction information of gradients) to obtain different complexity without dramatic changes in accuracy. Another contribution is that we uncover the secrets of limited PatchMatch through a thorough analysis and design a pyramidal matching framework based these secrets. Our pyramidal matching framework is aimed at robust gradient matching and effective to grow inliers and reject outliers. In this framework, we present some special enhancements for outlier filtering in gradient matching. By initializing EpicFlow with our matches, experimental results show that our method is efficient and robust (ranking 1st on both clean pass and final pass of MPI Sintel dataset among published methods).

##### Abstract (translated by Google)
通过稀疏描述符匹配或稠密色块匹配来初始化光学流场已被证明对于捕获大位移特别有用。在本文中，我们提出了一种金字塔梯度匹配方法，可以提供高精度和高效的光流估计的密集匹配。我们的方法的一个新贡献是图像梯度被用来描述图像块，并被证明能够产生鲁棒的匹配。因此，我们的方法比采用特殊特征（如SIFT）或贴片距离度量的方法更有效。此外，我们发现图像梯度对于光流估计是可伸缩的，这意味着我们可以使用不同级别的梯度特征（例如，完全梯度或仅梯度的方向信息）来获得不同的复杂度，而不会在准确性方面发生显着变化。另一个贡献就是我们通过深入分析揭示了有限PatchMatch的秘密，并基于这些秘密设计了一个金字塔匹配框架。我们的金字塔匹配框架旨在强大的梯度匹配和有效地增长内点和拒绝离群点。在这个框架中，我们给出了梯度匹配中异常过滤的一些特殊增强。通过使用我们的匹配来初始化EpicFlow，实验结果表明，我们的方法是高效和稳健的（在已发布的方法中，在MPI Sintel数据集的清理通过和最终通过中排名第一）。

##### URL
[https://arxiv.org/abs/1704.03217](https://arxiv.org/abs/1704.03217)

##### PDF
[https://arxiv.org/pdf/1704.03217](https://arxiv.org/pdf/1704.03217)

