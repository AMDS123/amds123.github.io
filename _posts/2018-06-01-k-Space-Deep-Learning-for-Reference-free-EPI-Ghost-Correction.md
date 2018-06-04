---
layout: post
title: "k-Space Deep Learning for Reference-free EPI Ghost Correction"
date: 2018-06-01 01:01:27
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning
author: Juyoung Lee, Yoseob Han, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Nyquist ghost artifacts in EPI images are originated from phase mismatch between the even and odd echoes. However, conventional correction methods using reference scans often produce erroneous results especially in high-field MRI due to the non-linear and time-varying local magnetic field changes. It has been shown that the problem of ghost correction can be transformed into k-space data interpolation problem that can be solved using the annihilating filter-based low-rank Hankel structured matrix completion approach (ALOHA). Another recent discovery has shown that the deep convolutional neural network is closely related to the data-driven Hankel matrix decomposition. By synergistically combining these findings, here we propose a k-space deep learning approach that immediately corrects the k- space phase mismatch without a reference scan. Reconstruction results using 7T in vivo data showed that the proposed reference-free k-space deep learning approach for EPI ghost correction significantly improves the image quality compared to the existing methods and the computing time is several orders of magnitude faster.

##### Abstract (translated by Google)
奈奎斯特鬼影伪影在EPI图像中起源于偶数和奇数回波之间的相位失配。然而，由于非线性和随时间变化的局部磁场变化，使用参考扫描的传统校正方法经常产生错误的结果，尤其是在高场MRI中。已经证明，可以将重影校正问题转化为可以使用基于消除滤波器的低秩汉克尔结构化矩阵完成方法（ALOHA）来解决的k空间数据内插问题。最近的另一个发现表明深度卷积神经网络与数据驱动的汉克尔矩阵分解密切相关。通过协同结合这些研究结果，我们在这里提出了一种k空间深度学习方法，可以在没有参考扫描的情况下立即纠正k空间相位失配。使用7T体内数据的重建结果表明，与现有方法相比，提出的用于EPI鬼影校正的无参考k空间深度学习方法显着改善了图像质量，并且计算时间快几个数量级。

##### URL
[http://arxiv.org/abs/1806.00153](http://arxiv.org/abs/1806.00153)

##### PDF
[http://arxiv.org/pdf/1806.00153](http://arxiv.org/pdf/1806.00153)

