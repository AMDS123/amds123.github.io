---
layout: post
title: "Rotation Invariant Convolutions for 3D Point Clouds Deep Learning"
date: 2019-08-17 12:31:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Zhiyuan Zhang, Binh-Son Hua, David W. Rosen, Sai-Kit Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progresses in 3D deep learning has shown that it is possible to design special convolution operators to consume point cloud data. However, a typical drawback is that rotation invariance is often not guaranteed, resulting in networks being trained with data augmented with rotations. In this paper, we introduce a novel convolution operator for point clouds that achieves rotation invariance. Our core idea is to use low-level rotation invariant geometric features such as distances and angles to design a convolution operator for point cloud learning. The well-known point ordering problem is also addressed by a binning approach seamlessly built into the convolution. This convolution operator then serves as the basic building block of a neural network that is robust to point clouds under 6DoF transformations such as translation and rotation. Our experiment shows that our method performs with high accuracy in common scene understanding tasks such as object classification and segmentation. Compared to previous works, most importantly, our method is able to generalize and achieve consistent results across different scenarios in which training and testing can contain arbitrary rotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06297](http://arxiv.org/abs/1908.06297)

##### PDF
[http://arxiv.org/pdf/1908.06297](http://arxiv.org/pdf/1908.06297)

