---
layout: post
title: "Adaptive foveated single-pixel imaging with dynamic super-sampling"
date: 2016-07-27 15:27:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection Relation
author: David B. Phillips, Ming-Jie Sun, Jonathan M. Taylor, Matthew P. Edgar, Stephen M. Barnett, Graham G. Gibson, Miles J. Padgett
mathjax: true
---

* content
{:toc}

##### Abstract
As an alternative to conventional multi-pixel cameras, single-pixel cameras enable images to be recorded using a single detector that measures the correlations between the scene and a set of patterns. However, to fully sample a scene in this way requires at least the same number of correlation measurements as there are pixels in the reconstructed image. Therefore single-pixel imaging systems typically exhibit low frame-rates. To mitigate this, a range of compressive sensing techniques have been developed which rely on a priori knowledge of the scene to reconstruct images from an under-sampled set of measurements. In this work we take a different approach and adopt a strategy inspired by the foveated vision systems found in the animal kingdom - a framework that exploits the spatio-temporal redundancy present in many dynamic scenes. In our single-pixel imaging system a high-resolution foveal region follows motion within the scene, but unlike a simple zoom, every frame delivers new spatial information from across the entire field-of-view. Using this approach we demonstrate a four-fold reduction in the time taken to record the detail of rapidly evolving features, whilst simultaneously accumulating detail of more slowly evolving regions over several consecutive frames. This tiered super-sampling technique enables the reconstruction of video streams in which both the resolution and the effective exposure-time spatially vary and adapt dynamically in response to the evolution of the scene. The methods described here can complement existing compressive sensing approaches and may be applied to enhance a variety of computational imagers that rely on sequential correlation measurements.

##### Abstract (translated by Google)
作为传统多像素摄像头的替代方案，单像素摄像头使用单个探测器来记录图像，该探测器可以测量场景和一组图案之间的相关性。然而，为了以这种方式完全采样场景，需要至少与重构图像中的像素相同数量的相关测量。因此，单像素成像系统通常呈现低帧率。为了减轻这一点，已经开发了一系列压缩感测技术，其依赖于场景的先验知识来重建来自欠采样测量集合的图像。在这项工作中，我们采取了一种不同的方法，并采用了动物王国中发现的动态视觉系统的灵感 - 一个利用了许多动态场景中的时空冗余的框架。在我们的单像素成像系统中，高分辨率中央凹区域遵循场景内的运动，但与简单的缩放不同，每一帧都从整个视场传递新的空间信息。使用这种方法，我们将记录快速演变特征的细节所需的时间减少了四倍，同时在几个连续的帧中累积了缓慢演变区域的细节。这种分层超级采样技术能够重建视频流，其中分辨率和有效曝光时间都在空间上变化并且响应于场景的演变而动态地适应。这里描述的方法可以补充现有的压缩感测方法，并且可以用于增强依赖于顺序相关性测量的各种计算成像器。

##### URL
[https://arxiv.org/abs/1607.08236](https://arxiv.org/abs/1607.08236)

##### PDF
[https://arxiv.org/pdf/1607.08236](https://arxiv.org/pdf/1607.08236)

