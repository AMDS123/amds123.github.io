---
layout: post
title: "Multiresolution Approach to Acceleration of Iterative Image Reconstruction for X-Ray Imaging for Security Applications"
date: 2015-06-24 22:03:28
categories: arXiv_CV
tags: arXiv_CV Quantitative Detection
author: S. Degirmenci, Joseph A. O'Sullivan, David G. Politte
mathjax: true
---

* content
{:toc}

##### Abstract
Three-dimensional x-ray CT image reconstruction in baggage scanning in security applications is an important research field. The variety of materials to be reconstructed is broader than medical x-ray imaging. Presence of high attenuating materials such as metal may cause artifacts if analytical reconstruction methods are used. Statistical modeling and the resultant iterative algorithms are known to reduce these artifacts and present good quantitative accuracy in estimates of linear attenuation coefficients. However, iterative algorithms may require computations in order to achieve quantitatively accurate results. For the case of baggage scanning, in order to provide fast accurate inspection throughput, they must be accelerated drastically. There are many approaches proposed in the literature to increase speed of convergence. This paper presents a new method that estimates the wavelet coefficients of the images in the discrete wavelet transform domain instead of the image space itself. Initially, surrogate functions are created around approximation coefficients only. As the iterations proceed, the wavelet tree on which the updates are made is expanded based on a criterion and detail coefficients at each level are updated and the tree is expanded this way. For example, in the smooth regions of the image the detail coefficients are not updated while the coefficients that represent the high-frequency component around edges are being updated, thus saving time by focusing computations where they are needed. This approach is implemented on real data from a SureScan (TM) x1000 Explosive Detection System and compared to straightforward implementation of the unregularized alternating minimization of O'Sullivan and Benac [1].

##### Abstract (translated by Google)
行李扫描在安全应用中的三维X射线CT图像重建是一个重要的研究领域。要重建的材料的种类比医用X射线成像更广泛。如果使用分析重建方法，高度衰减材料（如金属）的存在可能会造成伪影。统计建模和由此产生的迭代算法已知可以减少这些伪影，并在线性衰减系数的估计中呈现出良好的定量精度。但是，迭代算法可能需要计算以实现定量准确的结果。对于行李扫描的情况，为了提供快速准确的检查吞吐量，必须大幅加速。文献中提出了许多方法来提高收敛速度。本文提出了一种新的方法来估计离散小波变换域中图像的小波系数，而不是图像空间本身。最初，替代函数仅在逼近系数周围创建。随着迭代的进行，基于标准对进行更新的小波树进行扩展，并且更新每一级的细节系数，并且以这种方式扩展树。例如，在图像的平滑区域中，不更新细节系数，而代表边缘周围的高频分量的系数正被更新，从而通过在需要的地方聚焦计算来节省时间。这种方法是通过SureScan（TM）x1000爆炸物检测系统的实际数据来实现的，与直接实施O'Sullivan和Benac [1]的非规则交替最小化方法相比。

##### URL
[https://arxiv.org/abs/1508.04458](https://arxiv.org/abs/1508.04458)

##### PDF
[https://arxiv.org/pdf/1508.04458](https://arxiv.org/pdf/1508.04458)

