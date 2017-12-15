---
layout: post
title: "Multimodal Remote Sensing Image Registration with Accuracy Estimation at Local and Global Scales"
date: 2016-05-25 20:16:54
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: M.L. Uss, B. Vozel, V.V. Lukin, K. Chehdi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on potential accuracy of remote sensing images registration. We investigate how this accuracy can be estimated without ground truth available and used to improve registration quality of mono- and multi-modal pair of images. At the local scale of image fragments, the Cramer-Rao lower bound (CRLB) on registration error is estimated for each local correspondence between coarsely registered pair of images. This CRLB is defined by local image texture and noise properties. Opposite to the standard approach, where registration accuracy is only evaluated at the output of the registration process, such valuable information is used by us as an additional input knowledge. It greatly helps detecting and discarding outliers and refining the estimation of geometrical transformation model parameters. Based on these ideas, a new area-based registration method called RAE (Registration with Accuracy Estimation) is proposed. In addition to its ability to automatically register very complex multimodal image pairs with high accuracy, the RAE method provides registration accuracy at the global scale as covariance matrix of estimation error of geometrical transformation model parameters or as point-wise registration Standard Deviation. This accuracy does not depend on any ground truth availability and characterizes each pair of registered images individually. Thus, the RAE method can identify image areas for which a predefined registration accuracy is guaranteed. The RAE method is proved successful with reaching subpixel accuracy while registering eight complex mono/multimodal and multitemporal image pairs including optical to optical, optical to radar, optical to Digital Elevation Model (DEM) images and DEM to radar cases. Other methods employed in comparisons fail to provide in a stable manner accurate results on the same test cases.

##### Abstract (translated by Google)
本文重点介绍了遥感图像配准的潜在精度。我们研究如何在没有可用的基本事实的情况下估计这种精度，并用于改善单模和多模图像对的配准质量。在图像片段的局部尺度上，对于粗配准图像对之间的每个局部对应关系，估计配准误差上的Cramer-Rao下界（CRLB）。该CRLB由局部图像纹理和噪声属性定义。与注册准确性仅在注册过程的输出中进行评估的标准方法相反，这些有价值的信息被我们用作额外的输入知识。它极大地帮助检测和丢弃异常值，并提炼几何转换模型参数的估计值。基于这些思想，提出了一种新的基于区域的注册方法RAE（Registration with Accuracy Estimation）。 RAE方法除了具有高精度自动配准非常复杂的多模态图像对的能力之外，还提供全球尺度上的配准精度作为几何转换模型参数的估计误差的协方差矩阵或作为逐点配准标准偏差。这种精确度不取决于任何地面实际可用性，并且单独表征每对登记的图像。因此，RAE方法可以识别预定义配准精度被保证的图像区域。 RAE方法被证明是成功的，达到了亚像素精度，同时记录了八个复杂的单/多模式和多时相图像对，包括光学到光学，光学到雷达，光学到数字高程模型（DEM）图像以及DEM到雷达情况。在比较中使用的其他方法不能在相同的测试案例中以稳定的方式提供准确的结果。

##### URL
[https://arxiv.org/abs/1602.02720](https://arxiv.org/abs/1602.02720)

##### PDF
[https://arxiv.org/pdf/1602.02720](https://arxiv.org/pdf/1602.02720)

