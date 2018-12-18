---
layout: post
title: "Fast Learning-based Registration of Sparse Clinical Images"
date: 2018-12-17 18:14:24
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Kathleen M. Lewis, Guha Balakrishnan, Natalia S. Rost, John Guttag, Adrian V. Dalca
mathjax: true
---

* content
{:toc}

##### Abstract
Deformable registration of clinical scans is a fundamental task for many applications, such as population studies or the monitoring of long-term disease progression in individual patients. This task is challenging because, in contrast to high-resolution research-quality scans, clinical images are often sparse, missing up to 85% of the slices in comparison. Furthermore, the anatomy in the acquired slices is not consistent across scans because of variations in patient orientation with respect to the scanner. In this work, we introduce Sparse VoxelMorph (SparseVM), which adapts a state-of-the-art learning-based registration method to improve the registration of sparse clinical images. SparseVM is a fast, unsupervised method that weights voxel contributions to registration in proportion to confidence in the voxels. This leads to improved registration performance on volumes with voxels of varying reliability, such as interpolated clinical scans. SparseVM registers 3D scans in under a second on the GPU, which is orders of magnitudes faster than the best performing clinical registration methods, while still achieving comparable accuracy. Because of its short runtimes and accurate behavior, SparseVM can enable clinical analyses not previously possible. The code is publicly available at voxelmorph.mit.edu.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06932](http://arxiv.org/abs/1812.06932)

##### PDF
[http://arxiv.org/pdf/1812.06932](http://arxiv.org/pdf/1812.06932)

