---
layout: post
title: "Experimental comparison of single-pixel imaging algorithms"
date: 2017-10-24 07:51:10
categories: arXiv_CV
tags: arXiv_CV Regularization Review Gradient_Descent Relation
author: Liheng Bian, Jinli Suo, Qionghai Dai, Feng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Single-pixel imaging (SPI) is a novel technique capturing 2D images using a photodiode, instead of conventional 2D array sensors. SPI owns high signal-to-noise ratio, wide spectrum range, low cost, and robustness to light scattering. Various algorithms have been proposed for SPI reconstruction, including the linear correlation methods, the alternating projection method (AP), and the compressive sensing based methods. However, there has been no comprehensive review discussing respective advantages, which is important for SPI's further applications and development. In this paper, we reviewed and compared these algorithms in a unified reconstruction framework. Besides, we proposed two other SPI algorithms including a conjugate gradient descent based method (CGD) and a Poisson maximum likelihood based method. Both simulations and experiments validate the following conclusions: to obtain comparable reconstruction accuracy, the compressive sensing based total variation regularization method (TV) requires the least measurements and consumes the least running time for small-scale reconstruction; the CGD and AP methods run fastest in large-scale cases; the TV and AP methods are the most robust to measurement noise. In a word, there are trade-offs between capture efficiency, computational complexity and robustness to noise among different SPI algorithms. We have released our source code for non-commercial use.

##### Abstract (translated by Google)
单像素成像（SPI）是一种利用光电二极管捕获二维图像的新技术，而不是传统的二维阵列传感器。 SPI具有高信噪比，宽光谱范围，低成本和对光散射的稳健性。已经提出了用于SPI重建的各种算法，包括线性相关方法，交替投影方法（AP）和基于压缩感测的方法。然而，目前还没有全面的评论来讨论各自的优势，这对于SPI的进一步应用和发展是非常重要的。在本文中，我们在统一的重构框架中对这些算法进行了回顾和比较。此外，我们还提出了另外两种SPI算法，包括基于共轭梯度下降的方法（CGD）和基于泊松最大似然的方法。仿真和实验验证了以下结论：为获得可比较的重构精度，基于压缩感知的全变分正则化方法（TV）需要的测量次数最少，耗时最少; CGD和AP方法在大规模案例中运行速度最快;电视和AP方法对测量噪声最为稳健。总之，在不同的SPI算法中，捕获效率，计算复杂性和噪声的鲁棒性之间存在权衡。我们发布了非商业用途的源代码。

##### URL
[https://arxiv.org/abs/1707.03164](https://arxiv.org/abs/1707.03164)

##### PDF
[https://arxiv.org/pdf/1707.03164](https://arxiv.org/pdf/1707.03164)

