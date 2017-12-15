---
layout: post
title: "FPGA system for real-time computational extended depth of field imaging using phase aperture coding"
date: 2016-08-03 05:28:18
categories: arXiv_CV
tags: arXiv_CV Sparse Quantitative
author: Tal Remez, Or Litany, Shachar Yoseff, Harel Haim, Alex Bronstein
mathjax: true
---

* content
{:toc}

##### Abstract
We present a proof-of-concept end-to-end system for computational extended depth of field (EDOF) imaging. The acquisition is performed through a phase-coded aperture implemented by placing a thin wavelength-dependent optical mask inside the pupil of a conventional camera lens, as a result of which, each color channel is focused at a different depth. The reconstruction process receives the raw Bayer image as the input, and performs blind estimation of the output color image in focus at an extended range of depths using a patch-wise sparse prior. We present a fast non-iterative reconstruction algorithm operating with constant latency in fixed-point arithmetics and achieving real-time performance in a prototype FPGA implementation. The output of the system, on simulated and real-life scenes, is qualitatively and quantitatively better than the result of clear-aperture imaging followed by state-of-the-art blind deblurring.

##### Abstract (translated by Google)
我们提出了计算扩展景深（EDOF）成像的概念验证端到端系统。通过在传统照相机镜头的瞳孔内放置依赖于波长的光学掩模而实现的相位编码光圈来执行获取，结果是每个颜色通道被聚焦在不同的深度。重建过程接收原始拜耳图像作为输入，并且使用面片稀疏先验在深度范围内对焦点处的输出彩色图像进行盲估计。我们提出了一个快速的非迭代重建算法，在定点算法中以恒定的延迟操作，并在原型FPGA实现中实现实时性能。在模拟和现实生活场景中，系统的输出在质量和数量上要比清晰光圈成像和先进的去模糊效果更好。

##### URL
[https://arxiv.org/abs/1608.01074](https://arxiv.org/abs/1608.01074)

##### PDF
[https://arxiv.org/pdf/1608.01074](https://arxiv.org/pdf/1608.01074)

