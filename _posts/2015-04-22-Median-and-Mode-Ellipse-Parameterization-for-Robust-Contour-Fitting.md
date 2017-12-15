---
layout: post
title: "Median and Mode Ellipse Parameterization for Robust Contour Fitting"
date: 2015-04-22 00:12:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Michael A. Greminger
mathjax: true
---

* content
{:toc}

##### Abstract
Problems that require the parameterization of closed contours arise frequently in computer vision applications. This article introduces a new curve parameterization algorithm that is able to fit a closed curve to a set of points while being robust to the presence of outliers and occlusions in the data. This robustness property makes this algorithm applicable to computer vision applications where misclassification of features may lead to outliers. The algorithm starts by fitting ellipses to numerous five point subsets from the source data. The closed curve is parameterized by determining the median perimeter of the set of ellipses. The resulting curve is not an ellipse, allowing arbitrary closed contours to be parameterized. The use of the modal perimeter rather than the median perimeter is also explored. A detailed comparison is made between the proposed curve fitting algorithm and existing robust ellipse fitting algorithms. Finally, the utility of the algorithm for computer vision applications is demonstrated through the parameterization of the boundary of fuel droplets during combustion. The performance of the proposed algorithm and the performance of existing algorithms are compared to a ground truth segmentation of the fuel droplet images, which demonstrates improved performance for both area quantification and edge deviation.

##### Abstract (translated by Google)
计算机视觉应用中经常出现需要封闭轮廓参数化的问题。本文介绍了一种新的曲线参数化算法，该算法能够将闭合曲线拟合到一组点上，同时对数据中异常值和遮挡的存在具有鲁棒性。这种鲁棒特性使得该算法适用于计算机视觉应用，其中特征的错误分类可能导致异常值。该算法通过将椭圆拟合来自源数据的多个五点子集开始。闭合曲线通过确定椭圆集合的中值周长来参数化。生成的曲线不是椭圆，可以对任意闭合轮廓进行参数化。还探讨了使用模态周长而不是中值周长。提出的曲线拟合算法与现有的鲁棒椭圆拟合算法进行了详细的比较。最后，通过燃烧过程中燃料液滴边界的参数化，证明了该算法在计算机视觉应用中的实用性。所提出的算法的性能和现有算法的性能与燃料液滴图像的地面真实分割进行比较，这证明了对于面积量化和边缘偏差的改善的性能。

##### URL
[https://arxiv.org/abs/1504.05623](https://arxiv.org/abs/1504.05623)

##### PDF
[https://arxiv.org/pdf/1504.05623](https://arxiv.org/pdf/1504.05623)

