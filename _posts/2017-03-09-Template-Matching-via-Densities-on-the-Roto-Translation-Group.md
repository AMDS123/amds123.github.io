---
layout: post
title: "Template Matching via Densities on the Roto-Translation Group"
date: 2017-03-09 15:05:21
categories: arXiv_CV
tags: arXiv_CV Detection Relation
author: Erik J. Bekkers, Marco Loog, Bart M. ter Haar Romeny, Remco Duits
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a template matching method for the detection of 2D image objects that are characterized by orientation patterns. Our method is based on data representations via orientation scores, which are functions on the space of positions and orientations, and which are obtained via a wavelet-type transform. This new representation allows us to detect orientation patterns in an intuitive and direct way, namely via cross-correlations. Additionally, we propose a generalized linear regression framework for the construction of suitable templates using smoothing splines. Here, it is important to recognize a curved geometry on the position-orientation domain, which we identify with the Lie group SE(2): the roto-translation group. Templates are then optimized in a B-spline basis, and smoothness is defined with respect to the curved geometry. We achieve state-of-the-art results on three different applications: detection of the optic nerve head in the retina (99.83% success rate on 1737 images), of the fovea in the retina (99.32% success rate on 1616 images), and of the pupil in regular camera images (95.86% on 1521 images). The high performance is due to inclusion of both intensity and orientation features with effective geometric priors in the template matching. Moreover, our method is fast due to a cross-correlation based matching approach.

##### Abstract (translated by Google)
我们提出了一种模板匹配方法，用于检测以定位模式为特征的二维图像对象。我们的方法是基于定位分数的数据表示，这些定位分数是位置和方向空间上的函数，并且是通过小波类型变换获得的。这种新的表现形式使我们能够以直观和直接的方式检测方位模式，即通过互相关。此外，我们提出了一个广义的线性回归框架，用于使用平滑样条构建合适的模板。在这里，重要的是要识别位置定向域上的一个曲面几何，我们用李群SE（2）识别：旋转平移群。然后在B样条的基础上对模板进行优化，并且相对于曲面几何定义平滑度。我们在三种不同的应用中取得了最新的成果：视网膜视神经乳头的检测（1737张图像成功率99.83％），视网膜中央凹（1616张图像成功率99.32％），和普通摄像机图像中的瞳孔（1521张图像上的95.86％）。高性能是由于在模板匹配中包含强度和取向特征以及有效的几何先验。而且，由于基于互相关的匹配方法，我们的方法是快速的。

##### URL
[https://arxiv.org/abs/1603.03304](https://arxiv.org/abs/1603.03304)

##### PDF
[https://arxiv.org/pdf/1603.03304](https://arxiv.org/pdf/1603.03304)

