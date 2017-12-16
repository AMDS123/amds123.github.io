---
layout: post
title: "Edge-based Component-Trees for Multi-Channel Image Segmentation"
date: 2017-05-04 16:51:33
categories: arXiv_CV
tags: arXiv_CV OCR Segmentation
author: Tobias Böttger, Dominik Gutermuth
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the concept of edge-based component-trees for images with an arbitrary number of channels. The approach is a natural extension of the classical component-tree devoted to gray-scale images. The similar structure enables the translation of many gray-level image processing techniques based on the component-tree to hyperspectral and color images. As an example application, we present an image segmentation approach that extracts Maximally Stable Homogeneous Regions (MSHR). The approach very similar to MSER but can be applied to images with an arbitrary number of channels. As opposed to MSER, our approach implicitly segments regions with are both lighter and darker than their background for gray-scale images and can be used in OCR applications where MSER will fail. We introduce a local flooding-based immersion for the edge-based component-tree construction which is linear in the number of pixels. In the experiments, we show that the runtime scales favorably with an increasing number of channels and may improve algorithms which build on MSER.

##### Abstract (translated by Google)
我们介绍了任意数量的通道的图像的基于边缘的组件树的概念。该方法是专门用于灰度图像的经典组件树的自然延伸。类似的结构使得能够将基于分量树的许多灰度级图像处理技术转换为高光谱和彩色图像。作为一个应用实例，我们提出了一种提取最大稳定均匀区域（MSHR）的图像分割方法。该方法非常类似于MSER，但可应用于具有任意数量通道的图像。与MSER相反，我们的方法隐含地将区域分割为灰度图像比背景更亮和更暗的区域，并可用于MSER将失败的OCR应用程序。我们引入了一种基于边缘的组件树构造的局部泛洪沉浸，其在像素数量上是线性的。在实验中，我们显示运行时间随着通道数目的增加而增长，并且可以改进基于MSER的算法。

##### URL
[https://arxiv.org/abs/1705.01906](https://arxiv.org/abs/1705.01906)

##### PDF
[https://arxiv.org/pdf/1705.01906](https://arxiv.org/pdf/1705.01906)

