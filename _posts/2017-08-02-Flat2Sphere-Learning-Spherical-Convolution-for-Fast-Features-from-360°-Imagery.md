---
layout: post
title: "Flat2Sphere: Learning Spherical Convolution for Fast Features from 360° Imagery"
date: 2017-08-02 20:18:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Yu-Chuan Su, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
While 360{\deg} cameras offer tremendous new possibilities in vision, graphics, and augmented reality, the spherical images they produce make core feature extraction non-trivial. Convolutional neural networks (CNNs) trained on images from perspective cameras yield "flat" filters, yet 360{\deg} images cannot be projected to a single plane without significant distortion. A naive solution that repeatedly projects the viewing sphere to all tangent planes is accurate, but much too computationally intensive for real problems. We propose to learn a spherical convolutional network that translates a planar CNN to process 360{\deg} imagery directly in its equirectangular projection. Our approach learns to reproduce the flat filter outputs on 360{\deg} data, sensitive to the varying distortion effects across the viewing sphere. The key benefits are 1) efficient feature extraction for 360{\deg} images and video, and 2) the ability to leverage powerful pre-trained networks researchers have carefully honed (together with massive labeled image training sets) for perspective images. We validate our approach compared to several alternative methods in terms of both raw CNN output accuracy as well as applying a state-of-the-art "flat" object detector to 360{\deg} data. Our method yields the most accurate results while saving orders of magnitude in computation versus the existing exact reprojection solution.

##### Abstract (translated by Google)
尽管360度相机在视觉，图形和增强现实方面提供了巨大的新的可能性，但它们所生成的球形图像使得核心特征提取变得非常重要。在来自透视相机的图像上训练的卷积神经网络（CNN）产生“平坦”滤波器，但是360度图像不能被投影到没有明显失真的单个平面。反复将观察球体投影到所有相切平面的天真的解决方案是准确的，但是对于实际问题而言计算量太大。我们建议学习一个球形卷积网络，将平面CNN转换成直接在其等矩形投影中处理360°图像。我们的方法学习在360°数据上重现平坦的滤波器输出，对整个观察球变形的影响非常敏感。其主要优点是：1）为360度图像和视频提供高效的特征提取; 2）利用强大的预先训练的网络的能力研究人员已经仔细研究了透视图像（与大量标记的图像训练集一起）。我们验证了我们的方法，与原始CNN输出精度以及将最先进的“平坦”物体检测器应用于360°数据的几种替代方法相比较。我们的方法可以产生最准确的结果，同时比现有的精确重投影解决方案节省数量级。

##### URL
[https://arxiv.org/abs/1708.00919](https://arxiv.org/abs/1708.00919)

##### PDF
[https://arxiv.org/pdf/1708.00919](https://arxiv.org/pdf/1708.00919)

