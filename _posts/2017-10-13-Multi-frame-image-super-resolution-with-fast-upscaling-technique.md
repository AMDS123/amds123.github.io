---
layout: post
title: "Multi-frame image super-resolution with fast upscaling technique"
date: 2017-10-13 08:27:36
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Longguang Wang, Zaiping Lin, Xinpu Deng, Wei An
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-frame image super-resolution (MISR) aims to fuse information in low-resolution (LR) image sequence to compose a high-resolution (HR) one, which is applied extensively in many areas recently. Different with single image super-resolution (SISR), sub-pixel transitions between multiple frames introduce additional information, attaching more significance to fusion operator to alleviate the ill-posedness of MISR. For reconstruction-based approaches, the inevitable projection of reconstruction errors from LR space to HR space is commonly tackled by an interpolation operator, however crude interpolation may not fit the natural image and generate annoying blurring artifacts, especially after fusion operator. In this paper, we propose an end-to-end fast upscaling technique to replace the interpolation operator, design upscaling filters in LR space for periodic sub-locations respectively and shuffle the filter results to derive the final reconstruction errors in HR space. The proposed fast upscaling technique not only reduce the computational complexity of the upscaling operation by utilizing shuffling operation to avoid complex operation in HR space, but also realize superior performance with fewer blurring artifacts. Extensive experimental results demonstrate the effectiveness and efficiency of the proposed technique, whilst, combining the proposed technique with bilateral total variation (BTV) regu-larization, the MISR approach outperforms state-of-the-art methods.

##### Abstract (translated by Google)
多帧图像超分辨率（MISR）旨在融合低分辨率（LR）图像序列中的信息，构成高分辨率（HR）图像，最近在许多领域得到了广泛的应用。与单幅图像超分辨率（SISR）不同，多帧之间的子像素转换引入了附加信息，更加重要的融合算子来缓解MISR的不适应性。对于基于重建的方法，重建误差从LR空间到HR空间的不可避免的投影通常由插值算子来处理，然而粗插值可能不适合自然图像，并且产生恼人的模糊伪影，特别是在融合算子之后。在本文中，我们提出了一种端到端的快速放大技术来替代插值算子，分别在LR空间中设计放大倍数滤波器，用于周期性子位置，并对滤波结果进行混洗，得到HR空间中的最终重建误差。所提出的快速放大技术不仅通过利用混洗操作来减小放大操作的计算复杂度以避免HR空间中的复杂操作，而且还实现了具有较少模糊伪影的优异性能。广泛的实验结果证明了所提出的技术的有效性和效率，而将所提出的技术与双边总变异（BTV）调节相结合，MISR方法优于最先进的方法。

##### URL
[https://arxiv.org/abs/1706.06266](https://arxiv.org/abs/1706.06266)

##### PDF
[https://arxiv.org/pdf/1706.06266](https://arxiv.org/pdf/1706.06266)

