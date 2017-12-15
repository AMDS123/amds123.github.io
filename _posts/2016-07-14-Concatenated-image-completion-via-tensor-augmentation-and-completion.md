---
layout: post
title: "Concatenated image completion via tensor augmentation and completion"
date: 2016-07-14 00:24:33
categories: arXiv_CV
tags: arXiv_CV
author: Johann A. Bengua, Hoang D. Tuan, Ho N. Phien, Minh N. Do
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework called concatenated image completion via tensor augmentation and completion (ICTAC), which recovers missing entries of color images with high accuracy. Typical images are second- or third-order tensors (2D/3D) depending if they are grayscale or color, hence tensor completion algorithms are ideal for their recovery. The proposed framework performs image completion by concatenating copies of a single image that has missing entries into a third-order tensor, applying a dimensionality augmentation technique to the tensor, utilizing a tensor completion algorithm for recovering its missing entries, and finally extracting the recovered image from the tensor. The solution relies on two key components that have been recently proposed to take advantage of the tensor train (TT) rank: A tensor augmentation tool called ket augmentation (KA) that represents a low-order tensor by a higher-order tensor, and the algorithm tensor completion by parallel matrix factorization via tensor train (TMac-TT), which has been demonstrated to outperform state-of-the-art tensor completion algorithms. Simulation results for color image recovery show the clear advantage of our framework against current state-of-the-art tensor completion algorithms.

##### Abstract (translated by Google)
本文提出了一种通过张量增强和完成（ICTAC）的连续图像完成的新框架，该方法高精度地恢复彩色图像的缺失条​​目。典型的图像是二阶或三阶张量（二维/三维），这取决于它们是灰度还是颜色，因此张量完成算法对于它们的恢复是理想的。所提出的框架通过将具有缺失条目的单个图像的副本连接成三阶张量来执行图像完成，将张量补充技术应用于张量，利用张量完成算法来恢复其缺失条目，并最终提取恢复的图像从张量。该解决方案依赖于最近提出的利用张量列车（TT）等级的两个关键组件：称为ket增强（KA）的张量增强工具，其表示由高阶张量表示的低阶张量，通过张量训练并行矩阵分解（TMac-TT）完成算法张量完成，已经证明其性能优于最新的张量完成算法。对于彩色图像恢复的仿真结果显示了我们的框架与当前最先进的张量完成算法的明显优势。

##### URL
[https://arxiv.org/abs/1607.03967](https://arxiv.org/abs/1607.03967)

##### PDF
[https://arxiv.org/pdf/1607.03967](https://arxiv.org/pdf/1607.03967)

