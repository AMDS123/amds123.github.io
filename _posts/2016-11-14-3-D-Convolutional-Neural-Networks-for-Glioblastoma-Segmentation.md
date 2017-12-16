---
layout: post
title: "3-D Convolutional Neural Networks for Glioblastoma Segmentation"
date: 2016-11-14 19:21:33
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Darvin Yi, Mu Zhou, Zhao Chen, Olivier Gevaert
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) have emerged as powerful tools for learning discriminative image features. In this paper, we propose a framework of 3-D fully CNN models for Glioblastoma segmentation from multi-modality MRI data. By generalizing CNN models to true 3-D convolutions in learning 3-D tumor MRI data, the proposed approach utilizes a unique network architecture to decouple image pixels. Specifically, we design a convolutional layer with pre-defined Difference- of-Gaussian (DoG) filters to perform true 3-D convolution incorporating local neighborhood information at each pixel. We then use three trained convolutional layers that act to decouple voxels from the initial 3-D convolution. The proposed framework allows identification of high-level tumor structures on MRI. We evaluate segmentation performance on the BRATS segmentation dataset with 274 tumor samples. Extensive experimental results demonstrate encouraging performance of the proposed approach comparing to the state-of-the-art methods. Our data-driven approach achieves a median Dice score accuracy of 89% in whole tumor glioblastoma segmentation, revealing a generalized low-bias possibility to learn from medium-size MRI datasets.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经成为学习辨别图像特征的强大工具。在本文中，我们提出了一个基于多模式MRI数据的胶质母细胞瘤分割的三维全CNN模型框架。通过将CNN模型推广到学习三维肿瘤MRI数据的真正的3-D卷积，所提出的方法利用独特的网络架构来解耦图像像素。具体来说，我们设计了一个带有预定义的高斯差分（DoG）滤波器的卷积层，以在每个像素处执行包含局部邻域信息的真正的3-D卷积。然后，我们使用三个训练卷积层，从最初的三维卷积中去除体素。所提出的框架允许在MRI上鉴定高水平的肿瘤结构。我们评估了274个肿瘤样本在BRATS分割数据集上的分割性能。与最先进的方法相比，广泛的实验结果证明了所提出方法的令人鼓舞的性能。我们的数据驱动方法在整个肿瘤胶质母细胞瘤分割中实现了89％的中位Dice评分准确性，揭示了从中等大小的MRI数据集中学习普遍低偏倚的可能性。

##### URL
[https://arxiv.org/abs/1611.04534](https://arxiv.org/abs/1611.04534)

##### PDF
[https://arxiv.org/pdf/1611.04534](https://arxiv.org/pdf/1611.04534)

