---
layout: post
title: "Deep Slice Interpolation via Marginal Super-Resolution, Fusion and Refinement"
date: 2019-08-15 15:48:54
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Segmentation CNN Semantic_Segmentation
author: Cheng Peng, Wei-An Lin, Haofu Liao, Rama Chellappa, S. Kevin Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a marginal super-resolution (MSR) approach based on 2D convolutional neural networks (CNNs) for interpolating an anisotropic brain magnetic resonance scan along the highly under-sampled direction, which is assumed to axial without loss of generality. Previous methods for slice interpolation only consider data from pairs of adjacent 2D slices. The possibility of fusing information from the direction orthogonal to the 2D slices remains unexplored. Our approach performs MSR in both sagittal and coronal directions, which provides an initial estimate for slice interpolation. The interpolated slices are then fused and refined in the axial direction for improved consistency. Since MSR consists of only 2D operations, it is more feasible in terms of GPU memory consumption and requires fewer training samples compared to 3D CNNs. Our experiments demonstrate that the proposed method outperforms traditional linear interpolation and baseline 2D/3D CNN-based approaches. We conclude by showcasing the method's practical utility in estimating brain volumes from under-sampled brain MR scans through semantic segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05599](http://arxiv.org/abs/1908.05599)

##### PDF
[http://arxiv.org/pdf/1908.05599](http://arxiv.org/pdf/1908.05599)

