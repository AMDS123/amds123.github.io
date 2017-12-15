---
layout: post
title: "Perceptually Consistent Color-to-Gray Image Conversion"
date: 2016-05-06 07:13:48
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Shaodi You, Nick Barnes, Janine Walker
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a color to grayscale image conversion algorithm (C2G) that aims to preserve the perceptual properties of the color image as much as possible. To this end, we propose measures for two perceptual properties based on contemporary research in vision science: brightness and multi-scale contrast. The brightness measurement is based on the idea that the brightness of a grayscale image will affect the perception of the probability of color information. The color contrast measurement is based on the idea that the contrast of a given pixel to its surroundings can be measured as a linear combination of color contrast at different scales. Based on these measures we propose a graph based optimization framework to balance the brightness and contrast measurements. To solve the optimization, an $\ell_1$-norm based method is provided which converts color discontinuities to brightness discontinuities. To validate our methods, we evaluate against the existing \cadik and Color250 datasets, and against NeoColor, a new dataset that improves over existing C2G datasets. NeoColor contains around 300 images from typical C2G scenarios, including: commercial photograph, printing, books, magazines, masterpiece artworks and computer designed graphics. We show improvements in metrics of performance, and further through a user study, we validate the performance of both the algorithm and the metric.

##### Abstract (translated by Google)
在本文中，我们提出了一种颜色到灰度图像转换算法（C2G），旨在尽可能地保留彩色图像的感知特性。为此，我们提出了基于当代视觉科学研究的两种感知特性的测量：亮度和多尺度对比度。亮度测量的基础是灰度图像的亮度会影响颜色信息概率的感知。颜色对比度测量是基于这样一种观点，即给定像素与其周围的对比度可以作为不同尺度下颜色对比度的线性组合来测量。基于这些措施，我们提出了一个基于图形的优化框架来平衡亮度和对比度测量。为了解决这个问题，我们提供了一个基于$ \ ell_1 $-norm的方法来将颜色不连续性转换为亮度不连续性。为了验证我们的方法，我们对现有的\ cadik和Color250数据集进行评估，并针对NeoColor进行评估，该数据集改进了现有的C2G数据集。 NeoColor包含来自典型C2G场景的大约300幅图像，包括：商业照片，印刷，书籍，杂志，杰作和计算机设计的图形。我们展示了性能指标方面的改进，并通过用户研究进一步验证算法和指标的性能。

##### URL
[https://arxiv.org/abs/1605.01843](https://arxiv.org/abs/1605.01843)

##### PDF
[https://arxiv.org/pdf/1605.01843](https://arxiv.org/pdf/1605.01843)

