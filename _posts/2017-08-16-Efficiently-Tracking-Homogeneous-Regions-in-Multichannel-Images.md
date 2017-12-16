---
layout: post
title: "Efficiently Tracking Homogeneous Regions in Multichannel Images"
date: 2017-08-16 08:30:47
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Tracking Object_Tracking
author: Tobias Böttger, Christina Eisenhofer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for tracking Maximally Stable Homogeneous Regions (MSHR) in images with an arbitrary number of channels. MSHR are conceptionally very similar to Maximally Stable Extremal Regions (MSER) and Maximally Stable Color Regions (MSCR), but can also be applied to hyperspectral and color images while remaining extremely efficient. The presented approach makes use of the edge-based component-tree which can be calculated in linear time. In the tracking step, the MSHR are localized by matching them to the nodes in the component-tree. We use rotationally invariant region and gray-value features that can be calculated through first and second order moments at low computational complexity. Furthermore, we use a weighted feature vector to improve the data association in the tracking step. The algorithm is evaluated on a collection of different tracking scenes from the literature. Furthermore, we present two different applications: 2D object tracking and the 3D segmentation of organs.

##### Abstract (translated by Google)
我们提出了一种跟踪任意数量的通道的图像中的最大稳定均匀区域（MSHR）的方法。 MSHR在概念上与极大稳定极值区（MSER）和最大稳定色区（MSCR）非常相似，但也可以应用于高光谱和彩色图像，同时保持极高的效率。所提出的方法利用了可以在线性时间内计算的基于边缘的分量树。在跟踪步骤中，通过将MSHR与组件树中的节点进行匹配来定位MSHR。我们使用旋转不变区域和灰度值特征，可以通过一阶和二阶矩计算低计算复杂度。此外，我们使用加权特征向量来改善跟踪步骤中的数据关联。该算法在文献的不同跟踪场景的集合上进行评估。此外，我们提出了两种不同的应用：2D对象跟踪和器官的3D分割。

##### URL
[https://arxiv.org/abs/1708.04804](https://arxiv.org/abs/1708.04804)

##### PDF
[https://arxiv.org/pdf/1708.04804](https://arxiv.org/pdf/1708.04804)

