---
layout: post
title: "A new stereo formulation not using pixel and disparity models"
date: 2018-03-05 06:50:23
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Kiyoshi Oguri, Yuichiro Shibata
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new stereo formulation which does not use pixel and disparity models. Many problems in vision are treated as assigning each pixel a label. Disparities are labels for stereo. Such pixel-labeling problems are naturally represented in terms of energy minimization, where the energy function has two terms: one term penalizes solutions that inconsistent with the observed data, the other term enforces spatial smoothness. Graph cuts are one of the effi- cient methods for solving energy minimization. However, exact minimization of multi labeling problems can be performed by graph cuts only for the case with convex smoothness terms. In pixel-disparity formulation, convex smoothness terms do not generate well reconstructed 3D results. Thus, truncated linear or quadratic smoothness terms, etc. are used, where approximate energy minimization is necessary. In this paper, we introduce a new site-labeling formulation, where the sites are not pixels but lines in 3D space, labels are not disparities but depth numbers. For this formulation, visibility reasoning is naturally included in the energy function. In addition, this formulation allows us to use a small smoothness term, which does not affect the 3D results much. This makes the optimization step very simple, so we could develop an approximation method for graph cut itself (not for energy minimization) and a high performance GPU graph cut program. For Tsukuba stereo pair in Middlebury data set, we got the result in 5ms using GTX1080GPU, 19ms using GTX660GPU.

##### Abstract (translated by Google)
我们介绍一种不使用像素和视差模型的新立体配方。视觉中的许多问题被视为为每个像素分配一个标签。差异是立体声的标签。这样的像素标签问题自然地以能量最小化的方式表示，其中能量函数有两个项：一个项惩罚与观察数据不一致的解，另一个项强制空间平滑度。图形切割是解决能量最小化的有效方法之一。然而，只有对于具有凸平滑项的情况，可以通过图形切割来执行多标签问题的精确最小化。在像素视差公式中，凸平滑项不能很好地生成重建的3D结果。因此，使用截短的线性或二次平滑项等，其中近似能量最小化是必要的。在本文中，我们介绍了一种新的站点标注公式，其中站点不是像素，而是三维空间中的线，标注不是视差而是深度数字。对于这个公式，能见度推理自然包含在能量函数中。另外，这个公式允许我们使用一个小的平滑项，这对3D结果没有太大的影响。这使得优化步骤变得非常简单，所以我们可以开发一种近似方法（本身不是用于能量最小化）和高性能GPU图形切割程序。对于Middlebury数据集中的筑波立体声对，我们使用GTX1080GPU获得了5ms的结果，使用GTX660GPU获得了19ms的结果。

##### URL
[http://arxiv.org/abs/1803.01516](http://arxiv.org/abs/1803.01516)

##### PDF
[http://arxiv.org/pdf/1803.01516](http://arxiv.org/pdf/1803.01516)

