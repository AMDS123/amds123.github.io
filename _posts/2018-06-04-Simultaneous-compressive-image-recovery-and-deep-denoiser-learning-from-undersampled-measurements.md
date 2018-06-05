---
layout: post
title: "Simultaneous compressive image recovery and deep denoiser learning from undersampled measurements"
date: 2018-06-04 05:41:46
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning
author: Magauiya Zhussip, Se Young Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Compressive image recovery utilizes sparse image priors such as wavelet l1 norm, total-variation (TV) norm, or self-similarity to reconstruct good quality images from highly compressive samples. Recently, there have been some attempts to exploit data-driven image priors from massive amount of clean images in compressive image recovery such as LDAMP algorithm. By utilizing large-scale noiseless images for training deep neural network denoisers, LDAMP outperformed other conventional compressive image reconstruction methods. However, one drawback of LDAMP is that large-scale noiseless images must be acquired for deep learning based denoisers. In this article, we propose a method for simultaneous compressive image recovery and deep denoiser learning from undersampled measurements that enables compressive image recovery methods to use data-driven image priors when only large-scale compressive samples are available without ground truth images. By utilizing the structure of LDAMP and Stein's Unbiased Risk Estimator (SURE) based deep neural network denoiser, we showed that our proposed methods were able to achieve better performance than other methods such as conventional BM3D-AMP and LDAMP methods trained with the results of BM3D-AMP for training data and/or testing data for all cases with i.i.d. Gaussian random and coded diffraction measurement matrices at various compression ratios. We also investigated accurate noise level estimation methods in LDAMP for coded diffraction measurement matrix to train deep denoiser networks for high performance.

##### Abstract (translated by Google)
压缩图像恢复利用稀疏图像先验（如小波l1范数，总变化（TV）范数或自相似性）来重建高压缩样本的高质量图像。最近，已经有一些尝试在LDAMP算法等压缩图像恢复中利用大量干净图像的数据驱动图像先验。利用大规模无噪声图像训练深度神经网络分解器，LDAMP胜过了其他传统的压缩图像重建方法。然而，LDAMP的一个缺点是，对于基于深度学习的分解器而言，必须获得大规模无噪声图像。在本文中，我们提出了一种同时压缩图像恢复和欠采样测量的深度降噪学习方法，当只有大规模压缩样本没有地面真实图像时，压缩图像恢复方法才能使用数据驱动的图像先验。通过利用基于LDAMP和Stein's无偏风险评估器（SURE）的深度神经网络降噪器的结构，我们发现我们提出的方法能够取得比其他方法如用BM3D结果训练的常规BM3D-AMP和LDAMP方法更好的性能-AMP用于培训所有iid案例的数据和/或测试数据高斯随机和编码衍射测量矩阵在各种压缩比。我们还研究了LDAMP中用于编码衍射测量矩阵的精确噪声水平估计方法，以训练深度降噪网络以获得高性能。

##### URL
[http://arxiv.org/abs/1806.00961](http://arxiv.org/abs/1806.00961)

##### PDF
[http://arxiv.org/pdf/1806.00961](http://arxiv.org/pdf/1806.00961)

