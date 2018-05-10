---
layout: post
title: "Sparse Blind Deconvolution for Distributed Radar Autofocus Imaging"
date: 2018-05-08 20:30:31
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Hassan Mansour, Dehong Liu, Ulugbek S. Kamilov, Petros T. Boufounos
mathjax: true
---

* content
{:toc}

##### Abstract
A common problem that arises in radar imaging systems, especially those mounted on mobile platforms, is antenna position ambiguity. Approaches to resolve this ambiguity and correct position errors are generally known as radar autofocus. Common techniques that attempt to resolve the antenna ambiguity generally assume an unknown gain and phase error afflicting the radar measurements. However, ensuring identifiability and tractability of the unknown error imposes strict restrictions on the allowable antenna perturbations. Furthermore, these techniques are often not applicable in near-field imaging, where mapping the position ambiguity to phase errors breaks down. 
 In this paper, we propose an alternate formulation where the position error of each antenna is mapped to a spatial shift operator in the image-domain. Thus, the radar autofocus problem becomes a multichannel blind deconvolution problem, in which the radar measurements correspond to observations of a static radar image that is convolved with the spatial shift kernel associated with each antenna. To solve the reformulated problem, we also develop a block coordinate descent framework that leverages the sparsity and piece-wise smoothness of the radar scene, as well as the one-sparse property of the two dimensional shift kernels. We evaluate the performance of our approach using both simulated and experimental radar measurements, and demonstrate its superior performance compared to state-of-the-art methods.

##### Abstract (translated by Google)
雷达成像系统中出现的一个常见问题，特别是那些安装在移动平台上的问题是天线位置模糊。解决这种模糊性和正确位置误差的方法通常被称为雷达自动对焦。试图解决天线不确定性的常用技术通常假定影响雷达测量的未知增益和相位误差。然而，确保未知误差的可识别性和易处理性对可允许的天线扰动施加了严格的限制。此外，这些技术通常不适用于近场成像，其中将位置模糊度映射为相位误差。
 在本文中，我们提出了一种替代公式，其中每个天线的位置误差被映射到图像域中的空间移位算子。因此，雷达自动聚焦问题变成了多通道盲解卷积问题，其中雷达测量结果对应于静态雷达图像的观测结果，该静态雷达图像与与每个天线相关联的空间移位内核进行卷积。为了解决重构问题，我们还开发了一个块坐标下降框架，该框架利用了雷达场景的稀疏性和分段平滑性，以及二维移位核的单稀疏性质。我们使用模拟雷达测量和实验雷达测量来评估我们方法的性能，并与最先进的方法相比，展示其优越的性能。

##### URL
[http://arxiv.org/abs/1805.03269](http://arxiv.org/abs/1805.03269)

##### PDF
[http://arxiv.org/pdf/1805.03269](http://arxiv.org/pdf/1805.03269)

