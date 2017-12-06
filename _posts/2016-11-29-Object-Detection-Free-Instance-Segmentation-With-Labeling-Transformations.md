---
layout: post
title: "Object Detection Free Instance Segmentation With Labeling Transformations"
date: 2016-11-29 05:42:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Long Jin, Zeyu Chen, Zhuowen Tu
mathjax: true
---

* content
{:toc}

##### Abstract
Instance segmentation has attracted recent attention in computer vision and existing methods in this domain mostly have an object detection stage. In this paper, we study the intrinsic challenge of the instance segmentation problem, the presence of a quotient space (swapping the labels of different instances leads to the same result), and propose new methods that are object proposal- and object detection- free. We propose three alternative methods, namely pixel-based affinity mapping, superpixel-based affinity learning, and boundary-based component segmentation, all focusing on performing labeling transformations to cope with the quotient space problem. By adopting fully convolutional neural networks (FCN) like models, our framework attains competitive results on both the PASCAL dataset (object-centric) and the Gland dataset (texture-centric), which the existing methods are not able to do. Our work also has the advantages in its transparency, simplicity, and being all segmentation based.

##### Abstract (translated by Google)
实例分割在计算机视觉领域引起了人们的广泛关注，现有的方法主要有对象检测阶段。在本文中，我们研究了实例分割问题的内在挑战，商空间的存在（交换不同实例的标签导致相同的结果），并提出了新的方法，即对象建议和对象检测自由。我们提出了三种替代方法，即基于像素的亲和度映射，基于超像素的亲和度学习和基于边界的组件分割，所有这些方法都集中在执行标记变换以应付商空间问题。通过采用像模型一样的完全卷积神经网络（FCN），我们的框架在PASCAL数据集（以对象为中心）和Gland数据集（以纹理为中心）上都获得了竞争结果，而现有方法无法做到。我们的工作也具有透明度，简单性和全部分段的优点。

##### URL
[https://arxiv.org/abs/1611.08991](https://arxiv.org/abs/1611.08991)

