---
layout: post
title: "Sparse + Low Rank Decomposition of Annihilating Filter-based Hankel Matrix for Impulse Noise Removal"
date: 2015-10-19 16:11:24
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Kyong Hwan Jin, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, so called annihilating filer-based low rank Hankel matrix (ALOHA) approach was proposed as a powerful image inpainting method. Based on the observation that smoothness or textures within an image patch corresponds to sparse spectral components in the frequency domain, ALOHA exploits the existence of annihilating filters and the associated rank-deficient Hankel matrices in the image domain to estimate the missing pixels. By extending this idea, here we propose a novel impulse noise removal algorithm using sparse + low rank decomposition of an annihilating filter-based Hankel matrix. The new approach, what we call the robust ALOHA, is motivated by the observation that an image corrupted with impulse noises has intact pixels; so the impulse noises can be modeled as sparse components, whereas the underlying image can be still modeled using a low-rank Hankel structured matrix. To solve the sparse + low rank decomposition problem, we propose an alternating direction method of multiplier (ADMM) method with initial factorized matrices coming from low rank matrix fitting (LMaFit) algorithm. To adapt the local image statistics that have distinct spectral distributions, the robust ALOHA is applied patch by patch. Experimental results from two types of impulse noises - random valued impulse noises and salt/pepper noises - for both single channel and multi-channel color images demonstrate that the robust ALOHA outperforms the existing algorithms up to 8dB in terms of the peak signal to noise ratio (PSNR).

##### Abstract (translated by Google)
最近，所谓的基于歼灭文件的低秩Hankel矩阵（ALOHA）方法被提出作为一种强大的图像修复方法。基于图像块内的平滑或纹理对应于频域中的稀疏频谱分量的观察，ALOHA利用图像域中的湮灭滤波器和相关的秩缺失的汉克尔（Hankel）矩阵的存在来估计缺失的像素。通过扩展这个思想，在这里我们提出了一种新颖的基于歼灭滤波器的Hankel矩阵的稀疏+低秩分解的脉冲噪声去除算法。这种新的方法，我们称之为强大的ALOHA，是由观察到脉冲噪声的图像具有完整像素的动机。所以脉冲噪声可以被建模为稀疏分量，而底层图像仍然可以使用低秩Hankel结构矩阵来建模。为了解决稀疏+低秩分解问题，提出了一种交替方向的乘法器（ADMM）方法，其初始分解矩阵来自低阶矩阵拟合（LMaFit）算法。为了适应具有不同光谱分布的局部图像统计量，稳健的ALOHA逐块地应用。对于单通道和多通道彩色图像，两种脉冲噪声 - 随机值脉冲噪声和椒盐噪声的实验结果表明，强大的ALOHA在峰值信噪比方面优于现有的高达8dB的算法（PSNR）。

##### URL
[https://arxiv.org/abs/1510.05559](https://arxiv.org/abs/1510.05559)

##### PDF
[https://arxiv.org/pdf/1510.05559](https://arxiv.org/pdf/1510.05559)

