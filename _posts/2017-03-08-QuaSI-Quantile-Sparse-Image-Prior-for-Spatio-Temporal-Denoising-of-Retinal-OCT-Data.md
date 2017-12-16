---
layout: post
title: "QuaSI: Quantile Sparse Image Prior for Spatio-Temporal Denoising of Retinal OCT Data"
date: 2017-03-08 17:59:51
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Franziska Schirrmacher, Thomas Köhler, Lennart Husvogt, James G. Fujimoto, Joachim Hornegger, Andreas K. Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Optical coherence tomography (OCT) enables high-resolution and non-invasive 3D imaging of the human retina but is inherently impaired by speckle noise. This paper introduces a spatio-temporal denoising algorithm for OCT data on a B-scan level using a novel quantile sparse image (QuaSI) prior. To remove speckle noise while preserving image structures of diagnostic relevance, we implement our QuaSI prior via median filter regularization coupled with a Huber data fidelity model in a variational approach. For efficient energy minimization, we develop an alternating direction method of multipliers (ADMM) scheme using a linearization of median filtering. Our spatio-temporal method can handle both, denoising of single B-scans and temporally consecutive B-scans, to gain volumetric OCT data with enhanced signal-to-noise ratio. Our algorithm based on 4 B-scans only achieved comparable performance to averaging 13 B-scans and outperformed other current denoising methods.

##### Abstract (translated by Google)
光学相干断层扫描（OCT）使得人类视网膜的高分辨率和非侵入性3D成像成为可能，但是其本质上受到斑点噪声的影响。本文首先利用一种新的分位数稀疏图像（QuaSI）在B扫描水平上引入OCT数据的时空去噪算法。为了在保留诊断相关性的图像结构的同时去除斑点噪声，我们通过中值滤波正则化和Huber数据保真度模型以变分方法实现了我们的QuaSI。为了实现有效的能量最小化，我们使用中值滤波的线性化来开发乘法器（ADMM）的交替方向方法。我们的时空方法可以同时处理单个B扫描和时间上连续的B扫描的去噪，以获得具有增强的信噪比的体积OCT数据。我们基于4个B扫描的算法仅取得了与13次B扫描平均相当的性能，并且优于其他目前的去噪方法。

##### URL
[https://arxiv.org/abs/1703.02942](https://arxiv.org/abs/1703.02942)

##### PDF
[https://arxiv.org/pdf/1703.02942](https://arxiv.org/pdf/1703.02942)

