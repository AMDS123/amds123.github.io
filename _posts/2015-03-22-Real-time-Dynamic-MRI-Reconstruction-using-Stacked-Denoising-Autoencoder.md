---
layout: post
title: "Real-time Dynamic MRI Reconstruction using Stacked Denoising Autoencoder"
date: 2015-03-22 04:09:31
categories: arXiv_CV
tags: arXiv_CV
author: Angshul Majumdar
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the problem of real-time dynamic MRI reconstruction. There are a handful of studies on this topic; these techniques are either based on compressed sensing or employ Kalman Filtering. These techniques cannot achieve the reconstruction speed necessary for real-time reconstruction. In this work, we propose a new approach to MRI reconstruction. We learn a non-linear mapping from the unstructured aliased images to the corresponding clean images using a stacked denoising autoencoder (SDAE). The training for SDAE is slow, but the reconstruction is very fast - only requiring a few matrix vector multiplications. In this work, we have shown that using SDAE one can reconstruct the MRI frame faster than the data acquisition rate, thereby achieving real-time reconstruction. The quality of reconstruction is of the same order as a previous compressed sensing based online reconstruction technique.

##### Abstract (translated by Google)
在这项工作中，我们解决了实时动态MRI重建的问题。关于这个话题有一些研究。这些技术要么基于压缩感测，要么采用卡尔曼滤波。这些技术无法达到实时重建所需的重建速度。在这项工作中，我们提出了一种新的MRI重建方法。我们学习使用堆叠去噪自动编码器（SDAE）从非结构化别名图像到相应的干净图像的非线性映射。 SDAE的训练速度很慢，但重建速度非常快 - 只需要几次矩阵向量乘法。在这项工作中，我们已经表明使用SDAE可以比数据采集速率更快地重建MRI帧，从而实现实时重建。重建的质量与先前基于压缩感测的在线重建技术具有相同的顺序。

##### URL
[https://arxiv.org/abs/1503.06383](https://arxiv.org/abs/1503.06383)

##### PDF
[https://arxiv.org/pdf/1503.06383](https://arxiv.org/pdf/1503.06383)

