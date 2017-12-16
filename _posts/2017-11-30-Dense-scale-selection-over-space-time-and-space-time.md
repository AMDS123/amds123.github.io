---
layout: post
title: "Dense scale selection over space, time and space-time"
date: 2017-11-30 10:58:28
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Tony Lindeberg
mathjax: true
---

* content
{:toc}

##### Abstract
Scale selection methods based on local extrema over scale of scale-normalized derivatives have been primarily developed to be applied sparsely --- at image points where the magnitude of a scale-normalized differential expression additionally assumes local extrema over the domain where the data are defined. This paper presents a methodology for performing dense scale selection, so that hypotheses about local characteristic scales in images, temporal signals and video can be computed at every image point and every time moment. A critical problem when designing mechanisms for dense scale selection is that the scale at which scale-normalized differential entities assume local extrema over scale can be strongly dependent on the local order of the locally dominant differential structure. To address this problem, we propose a methodology where local extrema over scale are detected of a quasi quadrature measure involving scale-space derivatives up to order two and propose two independent mechanisms to reduce the phase dependency of the local scale estimates by: (i) introducing a second layer of post-smoothing prior to the detection of local extrema over scale and (ii) performing local phase compensation based on a model of the phase dependency of the local scale estimates depending on the relative strengths between first- vs. second-order differential structure. This general methodology is applied over three types of domains: (i) spatial images, (ii) temporal signals and (iii) spatio-temporal video. Experiments show that the proposed methodology leads to intuitively reasonable results with local scale estimates that reflect variations in the characteristic scales of locally dominant structures over space and time.

##### Abstract (translated by Google)
尺度选择方法基于尺度标准化衍生物尺度上的局部极值已经主要发展为稀疏应用 - 在尺度标准化差异表达的幅度另外假定数据被定义的域上的局部极值的图像点处。本文提出了一种进行密集尺度选择的方法，使得可以在每个图像点和每个时刻计算关于图像，时间信号和视频中的局部特征尺度的假设。设计密度选择机制时的一个关键问题是，尺度标准化的微分实体假定局部极值过大的规模可能强烈依赖于局部主导微分结构的局部阶数。为了解决这个问题，我们提出了一种方法，其中局部极值超尺度被检测到涉及尺度空间导数达到二阶的准正交测度，并提出了两个独立的机制来减少局部尺度估计的相位依赖性：（i）在根据比例检测局部极值之前引入第二层后平滑，以及（ii）根据第一和第二层之间的相对强度，基于局部尺度估计的相位依赖性的模型执行局部相位补偿，阶差分结构。这种通用的方法被应用于三种类型的领域：（i）空间图像，（ii）时间信号和（iii）时空视频。实验表明，所提出的方法导致了直观合理的结果，局部尺度估计反映了局部占优结构在空间和时间上的特征尺度的变化。

##### URL
[https://arxiv.org/abs/1709.08603](https://arxiv.org/abs/1709.08603)

##### PDF
[https://arxiv.org/pdf/1709.08603](https://arxiv.org/pdf/1709.08603)

