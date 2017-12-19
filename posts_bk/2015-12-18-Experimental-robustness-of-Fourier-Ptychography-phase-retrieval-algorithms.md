---
layout: post
title: "Experimental robustness of Fourier Ptychography phase retrieval algorithms"
date: 2015-12-18 07:33:10
categories: arXiv_CV
tags: arXiv_CV
author: Li-Hao Yeh, Jonathan Dong, Jingshan Zhong, Lei Tian, Michael Chen, Gongguo Tang, Mahdi Soltanolkotabi, Laura Waller
mathjax: true
---

* content
{:toc}

##### Abstract
Fourier ptychography is a new computational microscopy technique that provides gigapixel-scale intensity and phase images with both wide field-of-view and high resolution. By capturing a stack of low-resolution images under different illumination angles, a nonlinear inverse algorithm can be used to computationally reconstruct the high-resolution complex field. Here, we compare and classify multiple proposed inverse algorithms in terms of experimental robustness. We find that the main sources of error are noise, aberrations and mis-calibration (i.e. model mis-match). Using simulations and experiments, we demonstrate that the choice of cost function plays a critical role, with amplitude-based cost functions performing better than intensity-based ones. The reason for this is that Fourier ptychography datasets consist of images from both brightfield and darkfield illumination, representing a large range of measured intensities. Both noise (e.g. Poisson noise) and model mis-match errors are shown to scale with intensity. Hence, algorithms that use an appropriate cost function will be more tolerant to both noise and model mis-match. Given these insights, we propose a global Newton's method algorithm which is robust and computationally efficient. Finally, we discuss the impact of procedures for algorithmic correction of aberrations and mis-calibration.

##### Abstract (translated by Google)
傅立叶倍频是一种新的计算显微镜技术，可以提供宽视野和高分辨率的千兆像素级强度和相位图像。通过在不同照明角度下拍摄一叠低分辨率图像，可以使用非线性逆算法来计算重构高分辨率复数场。在这里，我们比较和分类多个提出的反演算法在实验的鲁棒性方面。我们发现误差的主要来源是噪声，像差和误校准（即模型不匹配）。使用模拟和实验，我们证明了成本函数的选择起着关键的作用，基于振幅的成本函数比基于强度的成本函数表现更好。其原因是傅里叶pychography数据集包括来自明场和暗场照明的图像，表示大范围的测量强度。示出了噪声（例如泊松噪声）和模型失配误差两者都与强度成比例。因此，使用适当的成本函数的算法将更容忍噪声和模型的不匹配。鉴于这些见解，我们提出了一种全局的牛顿法算法，该算法是鲁棒的并且计算效率高。最后，我们讨论程序对畸变算法校正和误校准的影响。

##### URL
[https://arxiv.org/abs/1511.02986](https://arxiv.org/abs/1511.02986)

##### PDF
[https://arxiv.org/pdf/1511.02986](https://arxiv.org/pdf/1511.02986)

