---
layout: post
title: "Registering large volume serial-section electron microscopy image sets for neural circuit reconstruction using FFT signal whitening"
date: 2016-12-14 20:03:05
categories: arXiv_CV
tags: arXiv_CV Relation
author: Arthur W. Wetzel, Jennifer Bakal, Markus Dittrich, David G. C. Hildebrand, Josh L. Morgan, Jeff W. Lichtman
mathjax: true
---

* content
{:toc}

##### Abstract
The detailed reconstruction of neural anatomy for connectomics studies requires a combination of resolution and large three-dimensional data capture provided by serial section electron microscopy (ssEM). The convergence of high throughput ssEM imaging and improved tissue preparation methods now allows ssEM capture of complete specimen volumes up to cubic millimeter scale. The resulting multi-terabyte image sets span thousands of serial sections and must be precisely registered into coherent volumetric forms in which neural circuits can be traced and segmented. This paper introduces a Signal Whitening Fourier Transform Image Registration approach (SWiFT-IR) under development at the Pittsburgh Supercomputing Center and its use to align mouse and zebrafish brain datasets acquired using the wafer mapper ssEM imaging technology recently developed at Harvard University. Unlike other methods now used for ssEM registration, SWiFT-IR modifies its spatial frequency response during image matching to maximize a signal-to-noise measure used as its primary indicator of alignment quality. This alignment signal is more robust to rapid variations in biological content and unavoidable data distortions than either phase-only or standard Pearson correlation, thus allowing more precise alignment and statistical confidence. These improvements in turn enable an iterative registration procedure based on projections through multiple sections rather than more typical adjacent-pair matching methods. This projection approach, when coupled with known anatomical constraints and iteratively applied in a multi-resolution pyramid fashion, drives the alignment into a smooth form that properly represents complex and widely varying anatomical content such as the full cross-section zebrafish data.

##### Abstract (translated by Google)
连接组学研究的神经解剖学的详细重建需要结合分辨率和由连续切片电子显微镜（ssEM）提供的大量三维数据捕获。高通量ssEM成像和改进的组织制备方法的融合现在允许ssEM捕获高达立方毫米规模的完整样本体积。由此产生的多TB图像集涵盖了数千个连续的部分，并且必须精确地注册到可以追踪和分割神经回路的连贯的体积形式中。本文介绍了匹兹堡超级计算中心正在开发的信号白化傅立叶变换图像配准方法（SWiFT-IR），以及利用最近在哈佛大学开发的晶圆映射器ssEM成像技术获得的鼠标和斑马鱼大脑数据集。与现在用于ssEM配准的其他方法不同，SWiFT-IR在图像匹配期间修改其空间频率响应，以最大化信噪比度量作为其对准质量的主要指标。这种对准信号对于生物内容的快速变化以及不可避免的数据失真比单相或标准Pearson相关更稳健，从而允许更精确的比对和统计置信度。这些改进反过来使基于通过多个部分的投影的迭代注册过程成为可能，而不是更典型的相邻对匹配方法。这种投影方法与已知的解剖学约束相结合，并以多分辨率金字塔形式迭代应用，将对齐驱动为平滑的形式，能够正确表示复杂和广泛变化的解剖学内容，如完整的斑马鱼数据。

##### URL
[https://arxiv.org/abs/1612.04787](https://arxiv.org/abs/1612.04787)

##### PDF
[https://arxiv.org/pdf/1612.04787](https://arxiv.org/pdf/1612.04787)

