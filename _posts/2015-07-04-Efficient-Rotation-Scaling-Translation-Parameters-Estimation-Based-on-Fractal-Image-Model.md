---
layout: post
title: "Efficient Rotation-Scaling-Translation Parameters Estimation Based on Fractal Image Model"
date: 2015-07-04 08:59:30
categories: arXiv_CV
tags: arXiv_CV Relation
author: M. Uss, B. Vozel, V.Lukin, K. Chehdi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with area-based subpixel image registration under rotation-isometric scaling-translation transformation hypothesis. Our approach is based on a parametrical modeling of geometrically transformed textural image fragments and maximum likelihood estimation of transformation vector between them. Due to the parametrical approach based on the fractional Brownian motion modeling of the local fragments texture, the proposed estimator MLfBm (ML stands for "Maximum Likelihood" and fBm for "Fractal Brownian motion") has the ability to better adapt to real image texture content compared to other methods relying on universal similarity measures like mutual information or normalized correlation. The main benefits are observed when assumptions underlying the fBm model are fully satisfied, e.g. for isotropic normally distributed textures with stationary increments. Experiments on both simulated and real images and for high and weak correlation between registered images show that the MLfBm estimator offers significant improvement compared to other state-of-the-art methods. It reduces translation vector, rotation angle and scaling factor estimation errors by a factor of about 1.75...2 and it decreases probability of false match by up to 5 times. Besides, an accurate confidence interval for MLfBm estimates can be obtained from the Cramer-Rao lower bound on rotation-scaling-translation parameters estimation error. This bound depends on texture roughness, noise level in reference and template images, correlation between these images and geometrical transformation parameters.

##### Abstract (translated by Google)
本文研究旋转 - 等距缩放 - 平移转换假设下的基于区域的亚像素图像配准。我们的方法是基于几何变换的纹理图像片段的参数化建模以及它们之间的变换矢量的最大似然估计。由于采用基于局部碎片纹理的分数布朗运动模型的参数化方法，所提出的估计器MLfBm（ML代表“最大似然”和“分形布朗运动”的fBm）具有更好地适应实际图像纹理内容的能力与其他依赖于互信息或归一化相关性的相似性度量方法相比，当完全满足fBm模型的假设时，观察到主要益处，例如，对于具有固定增量的各向同性正态分布纹理。在模拟图像和真实图像上的实验以及注册图像之间高度和弱的相关性表明，MLfBm估计器与其他最先进的方法相比有显着的改进。它将平移向量，旋转角度和缩放因子估计误差减少了大约1.75 ... 2倍，并将错误匹配的概率降低了5倍。另外，从Cramer-Rao旋转缩放转换参数估计误差的下限可以得到MLfBm估计的准确置信区间。这个界限取决于纹理粗糙度，参考和模板图像中的噪声水平，这些图像与几何变换参数之间的相关性。

##### URL
[https://arxiv.org/abs/1501.02372](https://arxiv.org/abs/1501.02372)

##### PDF
[https://arxiv.org/pdf/1501.02372](https://arxiv.org/pdf/1501.02372)

