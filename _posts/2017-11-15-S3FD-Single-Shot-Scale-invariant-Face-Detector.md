---
layout: post
title: "S$^3$FD: Single Shot Scale-invariant Face Detector"
date: 2017-11-15 16:22:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Shifeng Zhang, Xiangyu Zhu, Zhen Lei, Hailin Shi, Xiaobo Wang, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a real-time face detector, named Single Shot Scale-invariant Face Detector (S$^3$FD), which performs superiorly on various scales of faces with a single deep neural network, especially for small faces. Specifically, we try to solve the common problem that anchor-based detectors deteriorate dramatically as the objects become smaller. We make contributions in the following three aspects: 1) proposing a scale-equitable face detection framework to handle different scales of faces well. We tile anchors on a wide range of layers to ensure that all scales of faces have enough features for detection. Besides, we design anchor scales based on the effective receptive field and a proposed equal proportion interval principle; 2) improving the recall rate of small faces by a scale compensation anchor matching strategy; 3) reducing the false positive rate of small faces via a max-out background label. As a consequence, our method achieves state-of-the-art detection performance on all the common face detection benchmarks, including the AFW, PASCAL face, FDDB and WIDER FACE datasets, and can run at 36 FPS on a Nvidia Titan X (Pascal) for VGA-resolution images.

##### Abstract (translated by Google)
本文提出了一种实时人脸检测器，命名为单发式不变尺寸人脸检测器（S $ ^ 3 $ FD），该算法在单个深度神经网络的不同尺度上表现优异，尤其适用于小脸。具体而言，我们尝试解决锚定检测器随着对象变小而急剧恶化的常见问题。我们做了以下三方面的工作：1）提出了一个尺度公平的人脸检测框架，能很好地处理不同尺度的人脸。我们在各种各样的图层上拼贴锚点，以确保所有面的比例尺都具有足够的特征用于检测。此外，我们根据有效感受野和等比例间隔原则设计锚尺度; 2）采用尺度补偿锚点匹配策略提高小脸的召回率; 3）通过最大化背景标签减少小脸的误报率。因此，我们的方法可以在所有常见的人脸检测基准（包括AFW，PASCAL face，FDDB和WIDER FACE数据集）上实现最先进的检测性能，并且可以在Nvidia Titan X（Pascal）上以36 FPS ）VGA分辨率的图像。

##### URL
[https://arxiv.org/abs/1708.05237](https://arxiv.org/abs/1708.05237)

##### PDF
[https://arxiv.org/pdf/1708.05237](https://arxiv.org/pdf/1708.05237)

