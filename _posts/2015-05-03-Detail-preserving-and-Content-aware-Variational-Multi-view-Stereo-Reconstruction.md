---
layout: post
title: "Detail-preserving and Content-aware Variational Multi-view Stereo Reconstruction"
date: 2015-05-03 03:03:49
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Face
author: Zhaoxin Li, Kuanquan Wang, Wangmeng Zuo, Deyu Meng, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate recovery of 3D geometrical surfaces from calibrated 2D multi-view images is a fundamental yet active research area in computer vision. Despite the steady progress in multi-view stereo reconstruction, most existing methods are still limited in recovering fine-scale details and sharp features while suppressing noises, and may fail in reconstructing regions with few textures. To address these limitations, this paper presents a Detail-preserving and Content-aware Variational (DCV) multi-view stereo method, which reconstructs the 3D surface by alternating between reprojection error minimization and mesh denoising. In reprojection error minimization, we propose a novel inter-image similarity measure, which is effective to preserve fine-scale details of the reconstructed surface and builds a connection between guided image filtering and image registration. In mesh denoising, we propose a content-aware $\ell_{p}$-minimization algorithm by adaptively estimating the $p$ value and regularization parameters based on the current input. It is much more promising in suppressing noise while preserving sharp features than conventional isotropic mesh smoothing. Experimental results on benchmark datasets demonstrate that our DCV method is capable of recovering more surface details, and obtains cleaner and more accurate reconstructions than state-of-the-art methods. In particular, our method achieves the best results among all published methods on the Middlebury dino ring and dino sparse ring datasets in terms of both completeness and accuracy.

##### Abstract (translated by Google)
从校准的二维多视图图像精确恢复三维几何表面是计算机视觉领域的一个基本而积极的研究领域。尽管在多视点立体重建中取得了稳定的进展，但现有的大多数方法在抑制噪声的同时，仍然限制了细节细节和清晰特征的恢复，并且在重建纹理较少的区域时仍然存在失败。为了解决这些局限性，本文提出了一种细节保留和内容感知变分（DCV）多视点立体方法，通过在重投影误差最小化和网格去噪之间交替重构三维表面。在重投影误差最小化方面，我们提出了一种新的图像间相似性度量方法，该方法有效地保留了重构曲面的细节细节，并在引导图像滤波和图像配准之间建立了联系。在网格去噪中，我们提出了一种基于当前输入的自适应估计$ p $值和正则化参数的内容感知$ \ ell_ {p} $  - 最小化算法。与传统的各向同性网格平滑相比，在保留尖锐特征的同时抑制噪声更有前景。基准数据集上的实验结果表明，我们的DCV方法能够恢复更多的表面细节，并且比现有技术方法获得更清晰和更准确的重构。特别是，我们的方法在所有公布的Middlebury迪诺环和恐龙稀疏环数据集的完整性和准确性方面取得了最好的结果。

##### URL
[https://arxiv.org/abs/1505.00389](https://arxiv.org/abs/1505.00389)

##### PDF
[https://arxiv.org/pdf/1505.00389](https://arxiv.org/pdf/1505.00389)

