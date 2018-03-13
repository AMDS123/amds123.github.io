---
layout: post
title: "Super-Resolution of Sentinel-2 Images: Learning a Globally Applicable Deep Neural Network"
date: 2018-03-12 14:15:07
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Quantitative
author: Charis Lanaras, José Bioucas-Dias, Silvano Galliani, Emmanuel Baltsavias, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
The Sentinel-2 satellite mission delivers multi-spectral imagery with 13 spectral bands, acquired at three different spatial resolutions. The aim of this research is to super-resolve the lower-resolution (20 m and 60 m Ground Sampling Distance - GSD) bands to 10 m GSD, so as to obtain a complete data cube at the maximal sensor resolution. We employ a state-of-the-art convolutional neural network (CNN) to perform end-to-end upsampling, which is trained with data at lower resolution, i.e., from 40->20 m, respectively 360->60 m GSD. In this way, one has access to a virtually infinite amount of training data, by downsampling real Sentinel-2 images. We use data sampled globally over a wide range of geographical locations, to obtain a network that generalises across different climate zones and land-cover types, and can super-resolve arbitrary Sentinel-2 images without the need of retraining. In quantitative evaluations (at lower scale, where ground truth is available), our network outperforms the best competing approach by almost 50% in RMSE, while better preserving the spectral characteristics. It also delivers visually convincing results at the full 10 m GSD.

##### Abstract (translated by Google)
哨兵-2卫星任务提供13个光谱波段的多光谱图像，以三种不同的空间分辨率采集。本研究的目的是将较低分辨率（20 m和60 m地面采样距离-GSD）波段超分辨率达到10 m GSD，从而以最大传感器分辨率获得完整的数据立方体。我们采用先进的卷积神经网络（CNN）来执行端到端上采样，该采样以较低分辨率，即从40-> 20米，分别为360-> 60米GSD 。通过这种方式，人们可以通过下采样真实的Sentinel-2图像来获得几乎无限量的训练数据。我们使用全球范围内广泛地理位置采集的数据，以获得在不同气候带和地形覆盖类型之间概括的网络，并且可以在不需要再培训的情况下超级解析任意Sentinel-2图像。在量化评估中（在较低的范围内，在地面实况可用的情况下），我们的网络在RMSE中胜过最佳竞争方法几乎50％，同时更好地保留了频谱特性。它还在全长10米的GSD上提供视觉上令人信服的结果。

##### URL
[https://arxiv.org/abs/1803.04271](https://arxiv.org/abs/1803.04271)

##### PDF
[https://arxiv.org/pdf/1803.04271](https://arxiv.org/pdf/1803.04271)

