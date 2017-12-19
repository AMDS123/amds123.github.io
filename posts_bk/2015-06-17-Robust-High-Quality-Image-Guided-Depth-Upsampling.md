---
layout: post
title: "Robust High Quality Image Guided Depth Upsampling"
date: 2015-06-17 02:38:43
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Wei Liu, Yijun Li, Xiaogang Chen, Jie Yang, Qiang Wu, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Time-of-Flight (ToF) depth sensing camera is able to obtain depth maps at a high frame rate. However, its low resolution and sensitivity to the noise are always a concern. A popular solution is upsampling the obtained noisy low resolution depth map with the guidance of the companion high resolution color image. However, due to the constrains in the existing upsampling models, the high resolution depth map obtained in such way may suffer from either texture copy artifacts or blur of depth discontinuity. In this paper, a novel optimization framework is proposed with the brand new data term and smoothness term. The comprehensive experiments using both synthetic data and real data show that the proposed method well tackles the problem of texture copy artifacts and blur of depth discontinuity. It also demonstrates sufficient robustness to the noise. Moreover, a data driven scheme is proposed to adaptively estimate the parameter in the upsampling optimization framework. The encouraging performance is maintained even in the case of large upsampling e.g. $8\times$ and $16\times$.

##### Abstract (translated by Google)
飞行时间（ToF）深度感测摄像机能够以高帧率获得深度图。但是，它的低分辨率和对噪声的敏感性总是令人担忧的。一种流行的解决方案是在伴随的高分辨率彩色图像的引导下对获得的噪声低分辨率深度图进行上采样。然而，由于现有上采样模型的约束，以这种方式获得的高分辨率深度图可能遭受纹理复制伪影或深度不连续性的模糊。本文提出了一个全新的数据项和平滑项的新型优化框架。利用合成数据和实际数据的综合实验表明，所提出的方法很好地解决了纹理复制伪影和深度不连续性的问题。它还表现出对噪声足够的鲁棒性。此外，提出了一种数据驱动方案来自适应地估计上采样优化框架中的参数。即使在大量采样的情况下也能保持令人鼓舞的性能。 $ 8 \ times $和$ 16 \ times $。

##### URL
[https://arxiv.org/abs/1506.05187](https://arxiv.org/abs/1506.05187)

##### PDF
[https://arxiv.org/pdf/1506.05187](https://arxiv.org/pdf/1506.05187)

