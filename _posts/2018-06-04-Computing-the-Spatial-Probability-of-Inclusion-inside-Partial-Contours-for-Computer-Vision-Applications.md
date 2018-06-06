---
layout: post
title: "Computing the Spatial Probability of Inclusion inside Partial Contours for Computer Vision Applications"
date: 2018-06-04 19:26:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Optimization Detection
author: Dominique Beaini, Sofiane Achiche, Fabrice Nonez, Maxime Raison
mathjax: true
---

* content
{:toc}

##### Abstract
In Computer Vision, edge detection is one of the favored approaches for feature and object detection in images since it provides information about their objects boundaries. Other region-based approaches use probabilistic analysis such as clustering and Markov random fields, but those methods cannot be used to analyze edges and their interaction. In fact, only image segmentation can produce regions based on edges, but it requires thresholding by simply separating the regions into binary in-out information. Hence, there is currently a gap between edge-based and region-based algorithms, since edges cannot be used to study the properties of a region and vice versa. The objective of this paper is to present a novel spatial probability analysis that allows determining the probability of inclusion inside a set of partial contours (strokes). To answer this objective, we developed a new approach that uses electromagnetic convolutions and repulsion optimization to compute the required probabilities. Hence, it becomes possible to generate a continuous space of probability based only on the edge information, thus bridging the gap between the edge-based methods and the region-based methods. The developed method is consistent with the fundamental properties of inclusion probabilities and its results are validated by comparing an image with the probability-based estimation given by our algorithm. The method can also be generalized to take into consideration the intensity of the edges or to be used for 3D shapes. This is the first documented method that allows computing a space of probability based on interacting edges, which opens the path to broader applications such as image segmentation and contour completion.

##### Abstract (translated by Google)
在计算机视觉中，边缘检测是图像中特征和对象检测的首选方法之一，因为它提供了有关它们对象边界的信息。其他基于区域的方法使用概率分析，如聚类和马尔可夫随机场，但这些方法不能用于分析边缘及其相互作用。事实上，只有图像分割可以产生基于边缘的区域，但它需要通过简单地将区域分离成二进制输入输出信息来进行阈值处理。因此，目前基于边缘和基于区域的算法之间存在差距，因为边缘不能用于研究区域的属性，反之亦然。本文的目的是提出一种新颖的空间概率分析，可以确定包含在一组局部轮廓（笔划）内的概率。为了回应这个目标，我们开发了一种新的方法，使用电磁卷积和排斥优化来计算所需的概率。因此，可以仅基于边缘信息生成概率的连续空间，从而弥补了基于边缘的方法和基于区域的方法之间的差距。所开发的方法与包含概率的基本性质一致，并且其结果通过将图像与我们的算法给出的基于概率的估计进行比较来验证。该方法也可以推广到考虑边缘的强度或用于3D形状。这是第一个记录的方法，它允许基于交互边缘计算概率空间，从而为更广泛的应用（如图像分割和轮廓完成）开辟了道路。

##### URL
[http://arxiv.org/abs/1806.01339](http://arxiv.org/abs/1806.01339)

##### PDF
[http://arxiv.org/pdf/1806.01339](http://arxiv.org/pdf/1806.01339)

