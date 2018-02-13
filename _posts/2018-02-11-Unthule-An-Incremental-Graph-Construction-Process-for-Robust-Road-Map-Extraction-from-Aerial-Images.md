---
layout: post
title: "Unthule: An Incremental Graph Construction Process for Robust Road Map Extraction from Aerial Images"
date: 2018-02-11 02:38:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Favyen Bastani, Songtao He, Sofiane Abbar, Mohammad Alizadeh, Hari Balakrishnan, Sanjay Chawla, David DeWitt, Sam Madden
mathjax: true
---

* content
{:toc}

##### Abstract
The availability of highly accurate maps has become crucial due to the increasing importance of location-based mobile applications as well as autonomous vehicles. However, mapping roads is currently an expensive and human-intensive process. High-resolution aerial imagery provides a promising avenue to automatically infer a road network. Prior work uses convolutional neural networks (CNNs) to detect which pixels belong to a road (segmentation), and then uses complex post-processing heuristics to infer graph connectivity. We show that these segmentation methods have high error rates (poor precision) because noisy CNN outputs are difficult to correct. 
 We propose a novel approach, Unthule, to construct highly accurate road maps from aerial images. In contrast to prior work, Unthule uses an incremental search process guided by a CNN-based decision function to derive the road network graph directly from the output of the CNN. We train the CNN to output the direction of roads traversing a supplied point in the aerial imagery, and then use this CNN to incrementally construct the graph. We compare our approach with a segmentation method on fifteen cities, and find that Unthule has a 45% lower error rate in identifying junctions across these cities.

##### Abstract (translated by Google)
由于基于位置的移动应用以及自动驾驶汽车的重要性日益增加，高精度地图的可用性已变得至关重要。但是，测绘道路目前是一个耗资巨大并且人力密集的过程。高分辨率航空影像为自动推断道路网络提供了一条有希望的途径。先前的工作使用卷积神经网络（CNN）来检测哪些像素属于道路（分段），然后使用复杂的后处理启发式来推断图连通性。我们表明，这些分割方法具有较高的错误率（精度较差），因为噪声CNN输出很难纠正。
 我们提出了一种新颖的方法Unthule，从航空图像构建高精度的路线图。与之前的工作不同，Unthule使用基于CNN的决策功能指导的增量搜索过程，直接从CNN输出中导出道路网络图。我们训练CNN输出在空中影像中穿过一个提供点的道路方向，然后使用这个CNN逐步构建图形。我们将我们的方法与15个城市的分割方法进行了比较，发现Unthule在识别这些城市交叉路口时的错误率降低了45％。

##### URL
[http://arxiv.org/abs/1802.03680](http://arxiv.org/abs/1802.03680)

##### PDF
[http://arxiv.org/pdf/1802.03680](http://arxiv.org/pdf/1802.03680)

