---
layout: post
title: "FPNN: Field Probing Neural Networks for 3D Data"
date: 2016-10-25 03:59:16
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Yangyan Li, Soeren Pirk, Hao Su, Charles R. Qi, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
Building discriminative representations for 3D data has been an important task in computer graphics and computer vision research. Convolutional Neural Networks (CNNs) have shown to operate on 2D images with great success for a variety of tasks. Lifting convolution operators to 3D (3DCNNs) seems like a plausible and promising next step. Unfortunately, the computational complexity of 3D CNNs grows cubically with respect to voxel resolution. Moreover, since most 3D geometry representations are boundary based, occupied regions do not increase proportionately with the size of the discretization, resulting in wasted computation. In this work, we represent 3D spaces as volumetric fields, and propose a novel design that employs field probing filters to efficiently extract features from them. Each field probing filter is a set of probing points --- sensors that perceive the space. Our learning algorithm optimizes not only the weights associated with the probing points, but also their locations, which deforms the shape of the probing filters and adaptively distributes them in 3D space. The optimized probing points sense the 3D space "intelligently", rather than operating blindly over the entire domain. We show that field probing is significantly more efficient than 3DCNNs, while providing state-of-the-art performance, on classification tasks for 3D object recognition benchmark datasets.

##### Abstract (translated by Google)
在计算机图形学和计算机视觉研究中，构建3D数据的区分表示已经是一个重要的任务。卷积神经网络（CNN）已经显示在2D图像上操作，在各种任务中取得巨大成功。将卷积运算符提升到3D（3DCNN）看起来似乎是一个合理且有前景的下一步。不幸的是，3D CNN的计算复杂度相对于体素分辨率而言是立方体增长的。而且，由于大部分3D几何表示是基于边界的，因此占用区域不会随着离散化的大小成比例地增加，导致计算浪费。在这项工作中，我们将三维空间表示为体积域，并提出了一种新颖的设计，它使用现场探测过滤器从中有效地提取特征。每个现场探测过滤器是一组探测点 - 感知空间的传感器。我们的学习算法不仅优化了与探测点相关的权重，而且还优化了它们的位置，这使得探测滤波器的形状变形，并将其自适应地分布在三维空间中。优化的探测点“智能地”感知3D空间，而不是在整个领域盲目操作。我们表明，在三维物体识别基准数据集的分类任务中，场探测比3DCNNs更有效，同时提供了最先进的性能。

##### URL
[https://arxiv.org/abs/1605.06240](https://arxiv.org/abs/1605.06240)

##### PDF
[https://arxiv.org/pdf/1605.06240](https://arxiv.org/pdf/1605.06240)

