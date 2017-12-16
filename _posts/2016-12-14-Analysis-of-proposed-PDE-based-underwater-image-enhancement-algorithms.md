---
layout: post
title: "Analysis of proposed PDE-based underwater image enhancement algorithms"
date: 2016-12-14 00:47:51
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement Quantitative
author: U. A. Nnolim
mathjax: true
---

* content
{:toc}

##### Abstract
This report describes the experimental analysis of proposed underwater image enhancement algorithms based on partial differential equations (PDEs). The algorithms perform simultaneous smoothing and enhancement due to the combination of both processes within the PDE-formulation. The framework enables the incorporation of suitable colour and contrast enhancement algorithms within one unified functional. Additional modification of the formulation includes the combination of the popular Contrast Limited Adaptive Histogram Equalization (CLAHE) with the proposed approach. This modification enables the hybrid algorithm to provide both local enhancement (due to the CLAHE) and global enhancement (due to the proposed contrast term). Additionally, the CLAHE clip limit parameter is computed dynamically in each iteration and used to gauge the amount of local enhancement performed by the CLAHE within the formulation. This enables the algorithm to reduce or prevent the enhancement of noisy artifacts, which if present, are also smoothed out by the anisotropic diffusion term within the PDE formulation. In other words, the modified algorithm combines the strength of the CLAHE, AD and the contrast term while minimizing their weaknesses. Ultimately, the system is optimized using image data metrics for automated enhancement and compromise between visual and quantitative results. Experiments indicate that the proposed algorithms perform a series of functions such as illumination correction, colour enhancement correction and restoration, contrast enhancement and noise suppression. Moreover, the proposed approaches surpass most other conventional algorithms found in the literature.

##### Abstract (translated by Google)
本报告描述了基于偏微分方程（PDE）的提出的水下图像增强算法的实验分析。由于在PDE制定中两个过程的组合，算法执行同时平滑和增强。该框架能够在一个统一的功能内结合合适的颜色和对比度增强算法。该公式的额外修改包括将流行的对比度有限自适应直方图均衡化（CLAHE）与所提出的方法相结合。这种修改使得混合算法能够提供局部增强（由于CLAHE）和全局增强（由于所提出的对比术语）。此外，CLAHE限制参数是在每次迭代中动态计算的，并用于衡量CLAHE在配方中执行的局部增强量。这使得该算法能够减少或防止噪声伪影的增强，如果存在的话，其也可以通过PDE制定中的各向异性扩散项来平滑化。换句话说，改进的算法结合了CLAHE，AD和对比术语的强度，同时最大限度地减少了它们的弱点。最终，系统使用图像数据指标进行了优化，以实现视觉和定量结果之间的自动增强和折衷。实验表明，提出的算法执行一系列的功能，如光照校正，色彩增强校正和恢复，对比度增强和噪声抑制。此外，所提出的方法超过了文献中发现的大多数其他常规算法。

##### URL
[https://arxiv.org/abs/1612.04447](https://arxiv.org/abs/1612.04447)

##### PDF
[https://arxiv.org/pdf/1612.04447](https://arxiv.org/pdf/1612.04447)

