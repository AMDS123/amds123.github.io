---
layout: post
title: "Nonlinear Unsupervised Clustering of Hyperspectral Images with Applications to Anomaly Detection and Active Learning"
date: 2017-09-13 06:00:02
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: James M. Murphy, Mauro Maggioni
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of unsupervised learning and segmentation of hyperspectral images is a significant challenge in remote sensing. The high dimensionality of hyperspectral data, presence of substantial noise, and overlap of classes all contribute to the difficulty of automatically clustering and segmenting hyperspectral images. In this article, we propose an unsupervised learning technique that combines a geometric estimation of class modes with a diffusion-inspired labeling that incorporates both spatial and spectral information. The mode estimation incorporates the geometry of the hyperspectral data by using diffusion distance to promote learning a unique mode from each class. These class modes are then used to label all points by a joint spatial-spectral nonlinear diffusion process. The proposed method, called spatial-spectral diffusion learning (DLSS), is shown to perform competitively against benchmark and state-of-the-art hyperspectral clustering methods on a variety of synthetic and real datasets. The proposed methods are shown to enjoy low computational complexity and fast empirical runtime. Two variations of the proposed method are also discussed. The first variation combines the proposed method of mode estimation with partial least squares regression (PLSR) to efficiently segment chemical plumes in hyperspectral images for anomaly detection. The second variation incorporates active learning to allow the user to request labels for a very small number of pixels, which can dramatically improve overall clustering results. Extensive experimental analysis demonstrate the efficacy of the proposed methods, and their robustness to choices of parameters.

##### Abstract (translated by Google)
无监督学习和高光谱图像分割的问题是遥感领域的一个重大挑战。高光谱数据的高维度，大量噪声的存在以及类别的重叠都会导致自动聚类和分割高光谱图像的困难。在本文中，我们提出了一种无监督学习技术，将类模式的几何估计与包含空间和光谱信息的扩散激发标记相结合。模式估计通过使用扩散距离将高光谱数据的几何结构合并，以促进从每个类学习独特模式。这些类模式然后被用来通过联合空间谱非线性扩散过程来标记所有点。这种被称为空间光谱扩散学习（DLSS）的方法被证明可以在各种合成和真实数据集上与基准和最先进的高光谱聚类方法进行竞争。所提出的方法被证明具有低计算复杂性和快速的经验运行时间。本文还讨论了该方法的两种变体。第一种变化将所提出的模式估计方法与偏最小二乘回归（PLSR）相结合，以有效地分割高光谱图像中的化学羽流以进行异常检测。第二种变体结合了主动学习功能，允许用户请求非常少量像素的标签，这可以显着改善整体聚类结果。广泛的实验分析证明了所提出方法的有效性，以及它们对参数选择的鲁棒性。

##### URL
[https://arxiv.org/abs/1704.07961](https://arxiv.org/abs/1704.07961)

##### PDF
[https://arxiv.org/pdf/1704.07961](https://arxiv.org/pdf/1704.07961)

