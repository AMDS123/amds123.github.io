---
layout: post
title: "Self-supervised Recurrent Neural Network for 4D Abdominal and In-utero MR Imaging"
date: 2019-08-28 17:24:26
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse CNN Classification Relation
author: Tong Zhang, Laurence H. Jackson, Alena Uus, James R. Clough, Lisa Story, Mary A. Rutherford, Joseph V. Hajnal, Maria Deprez
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately estimating and correcting the motion artifacts are crucial for 3D image reconstruction of the abdominal and in-utero magnetic resonance imaging (MRI). The state-of-art methods are based on slice-to-volume registration (SVR) where multiple 2D image stacks are acquired in three orthogonal orientations. In this work, we present a novel reconstruction pipeline that only needs one orientation of 2D MRI scans and can reconstruct the full high-resolution image without masking or registration steps. The framework consists of two main stages: the respiratory motion estimation using a self-supervised recurrent neural network, which learns the respiratory signals that are naturally embedded in the asymmetry relationship of the neighborhood slices and cluster them according to a respiratory state. Then, we train a 3D deconvolutional network for super-resolution (SR) reconstruction of the sparsely selected 2D images using integrated reconstruction and total variation loss. We evaluate the classification accuracy on 5 simulated images and compare our results with the SVR method in adult abdominal and in-utero MRI scans. The results show that the proposed pipeline can accurately estimate the respiratory state and reconstruct 4D SR volumes with better or similar performance to the 3D SVR pipeline with less than 20\% sparsely selected slices. The method has great potential to transform the 4D abdominal and in-utero MRI in clinical practice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10842](http://arxiv.org/abs/1908.10842)

##### PDF
[http://arxiv.org/pdf/1908.10842](http://arxiv.org/pdf/1908.10842)

