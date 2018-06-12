---
layout: post
title: "Neural Proximal Gradient Descent for Compressive Imaging"
date: 2018-06-01 21:48:39
categories: arXiv_CV
tags: arXiv_CV Face Gradient_Descent
author: Morteza Mardani, Qingyun Sun, Shreyas Vasawanala, Vardan Papyan, Hatef Monajemi, John Pauly, David Donoho
mathjax: true
---

* content
{:toc}

##### Abstract
Recovering high-resolution images from limited sensory data typically leads to a serious ill-posed inverse problem, demanding inversion algorithms that effectively capture the prior information. Learning a good inverse mapping from training data faces severe challenges, including: (i) scarcity of training data; (ii) need for plausible reconstructions that are physically feasible; (iii) need for fast reconstruction, especially in real-time applications. We develop a successful system solving all these challenges, using as basic architecture the recurrent application of proximal gradient algorithm. We learn a proximal map that works well with real images based on residual networks. Contraction of the resulting map is analyzed, and incoherence conditions are investigated that drive the convergence of the iterates. Extensive experiments are carried out under different settings: (a) reconstructing abdominal MRI of pediatric patients from highly undersampled Fourier-space data and (b) superresolving natural face images. Our key findings include: 1. a recurrent ResNet with a single residual block unrolled from an iterative algorithm yields an effective proximal which accurately reveals MR image details. 2. Our architecture significantly outperforms conventional non-recurrent deep ResNets by 2dB SNR; it is also trained much more rapidly. 3. It outperforms state-of-the-art compressed-sensing Wavelet-based methods by 4dB SNR, with 100x speedups in reconstruction time.

##### Abstract (translated by Google)
从有限的感觉数据中恢复高分辨率图像通常会导致严重的不适合的反演问题，要求有效捕获先验信息的反演算法。从培训数据中学习一个好的逆映射会面临严峻的挑战，其中包括：（i）培训数据稀缺; （ii）需要物理上可行的合理的重建; （iii）需要快速重建，特别是在实时应用中。我们开发了一个解决所有这些挑战的成功系统，使用近端梯度算法的经常性应用作为基本架构。我们学习了一张基于残差网络的真实图像的近端地图。分析所得映射的收缩，并调查不连续条件以推动迭代的收敛。在不同的设置下进行了大量的实验：（a）从高度欠采样的傅里叶空间数据重建儿科患者的腹部MRI;（b）超分辨自然面部图像。我们的主要发现包括：1.从迭代算法中展开的具有单个残差块的经常性ResNet产生有效的近端，其精确地显示MR图像细节。 2.我们的架构显着优于传统的非经常性深度ResNets 2dB的SNR;它也训练得更快。 3.它的性能优于最先进的基于压缩感知小波的方法，信噪比为4dB，重建时间加速100倍。

##### URL
[http://arxiv.org/abs/1806.03963](http://arxiv.org/abs/1806.03963)

##### PDF
[http://arxiv.org/pdf/1806.03963](http://arxiv.org/pdf/1806.03963)

