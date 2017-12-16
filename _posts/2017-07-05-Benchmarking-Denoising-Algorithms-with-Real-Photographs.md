---
layout: post
title: "Benchmarking Denoising Algorithms with Real Photographs"
date: 2017-07-05 10:51:59
categories: arXiv_CV
tags: arXiv_CV
author: Tobias Plötz, Stefan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Lacking realistic ground truth data, image denoising techniques are traditionally evaluated on images corrupted by synthesized i.i.d. Gaussian noise. We aim to obviate this unrealistic setting by developing a methodology for benchmarking denoising techniques on real photographs. We capture pairs of images with different ISO values and appropriately adjusted exposure times, where the nearly noise-free low-ISO image serves as reference. To derive the ground truth, careful post-processing is needed. We correct spatial misalignment, cope with inaccuracies in the exposure parameters through a linear intensity transform based on a novel heteroscedastic Tobit regression model, and remove residual low-frequency bias that stems, e.g., from minor illumination changes. We then capture a novel benchmark dataset, the Darmstadt Noise Dataset (DND), with consumer cameras of differing sensor sizes. One interesting finding is that various recent techniques that perform well on synthetic noise are clearly outperformed by BM3D on photographs with real noise. Our benchmark delineates realistic evaluation scenarios that deviate strongly from those commonly used in the scientific literature.

##### Abstract (translated by Google)
由于缺乏现实的地面实况数据，图像去噪技术传统上是在被合成i.i.d破坏的图像上评估的。高斯噪声。我们的目标是通过开发基于真实照片去噪技术的方法论来消除这种不切实际的情况。我们捕获具有不同ISO值的图像对，并适当调整曝光时间，以几乎无噪声的低ISO图像作为参考。为了推导出事实真相，需要仔细的后期处理。我们通过基于新颖的异方差Tobit回归模型的线性强度变换来校正空间不对准，处理暴露参数中的不准确性，并去除残留的低频偏差，例如由于较小的照度变化。然后，我们用不同的传感器尺寸的消费类相机拍摄了一个新的基准数据集，即达姆施塔特噪声数据集（DND）。一个有趣的发现是，各种最近在合成噪声方面表现优异的技术在具有真实噪声的照片上明显优于BM3D。我们的基准描述了与科学文献中常用的偏离的现实评估方案。

##### URL
[https://arxiv.org/abs/1707.01313](https://arxiv.org/abs/1707.01313)

##### PDF
[https://arxiv.org/pdf/1707.01313](https://arxiv.org/pdf/1707.01313)

