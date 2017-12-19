---
layout: post
title: "Radon-Nikodym approximation in application to image analysis"
date: 2015-12-15 19:20:17
categories: arXiv_CV
tags: arXiv_CV
author: Vladislav Gennadievich Malyshkin
mathjax: true
---

* content
{:toc}

##### Abstract
For an image pixel information can be converted to the moments of some basis $Q_k$, e.g. Fourier-Mellin, Zernike, monomials, etc. Given sufficient number of moments pixel information can be completely recovered, for insufficient number of moments only partial information can be recovered and the image reconstruction is, at best, of interpolatory type. Standard approach is to present interpolated value as a linear combination of basis functions, what is equivalent to least squares expansion. However, recent progress in numerical stability of moments estimation allows image information to be recovered from moments in a completely different manner, applying Radon-Nikodym type of expansion, what gives the result as a ratio of two quadratic forms of basis functions. In contrast with least squares the Radon-Nikodym approach has oscillation near the boundaries very much suppressed and does not diverge outside of basis support. While least squares theory operate with vectors $<fQ_k>$, Radon-Nikodym theory operates with matrices $<fQ_jQ_k>$, what make the approach much more suitable to image transforms and statistical property estimation.

##### Abstract (translated by Google)
对于图像，像素信息可以被转换为某些基础的时刻，例如$ Q_k $。 Fourier-Mellin，Zernike，单项式等。给定足够的时刻像素信息可以被完全恢复，对于不足的时刻数量，只有部分信息可以被恢复，并且图像重构最好是插值类型的。标准方法是将内插值呈现为基函数的线性组合，相当于最小二乘展开。然而，矩量估计的数值稳定性的最新进展允许以完全不同的方式从时刻恢复图像信息，应用Radon-Nikodym类型的展开，其结果是以两个二次形式的基函数的比例给出结果。与最小二乘相比，氡 - 尼可德姆方法在边界附近的振荡非常受到抑制，并且在基础支持之外不发散。尽管最小二乘理论在向量$ <fQ_k> $的情况下运行，但是Radon-Nikodym理论在矩阵$ <fQ_jQ_k> $下运行，这使得该方法更适合于图像变换和统计特性估计。

##### URL
[https://arxiv.org/abs/1511.01887](https://arxiv.org/abs/1511.01887)

##### PDF
[https://arxiv.org/pdf/1511.01887](https://arxiv.org/pdf/1511.01887)

