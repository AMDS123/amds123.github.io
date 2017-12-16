---
layout: post
title: "Bayer Demosaicking Using Optimized Mean Curvature over RGB channels"
date: 2017-05-17 18:17:17
categories: arXiv_CV
tags: arXiv_CV Face
author: Rui Chen, Huizhu Jia, Xiange Wen, Xiaodong Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Color artifacts of demosaicked images are often found at contours due to interpolation across edges and cross-channel aliasing. To tackle this problem, we propose a novel demosaicking method to reliably reconstruct color channels of a Bayer image based on two different optimized mean-curvature (MC) models. The missing pixel values in green (G) channel are first estimated by minimizing a variational MC model. The curvatures of restored G-image surface are approximated as a linear MC model which guides the initial reconstruction of red (R) and blue (B) channels. Then a refinement process is performed to interpolate accurate full-resolution R and B images. Experiments on benchmark images have testified to the superiority of the proposed method in terms of both the objective and subjective quality.

##### Abstract (translated by Google)
由于跨边界的内插和跨通道混叠，经常在等值线处发现去马赛克图像的颜色伪像。为了解决这个问题，我们提出了一种基于两种不同的优化平均曲率（MC）模型来可靠地重构拜耳图像的颜色通道的新颖的去马赛克方法。绿色（G）通道中的缺失像素值首先通过最小化变分MC模型来估计。恢复的G图像表面的曲率近似为指导红（R）和蓝（B）通道的初始重建的线性MC模型。然后进行细化处理以插入精确的全分辨率R和B图像。基准图像的实验验证了所提方法在客观质量和主观质量上的优越性。

##### URL
[https://arxiv.org/abs/1705.06300](https://arxiv.org/abs/1705.06300)

##### PDF
[https://arxiv.org/pdf/1705.06300](https://arxiv.org/pdf/1705.06300)

