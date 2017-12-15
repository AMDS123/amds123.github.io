---
layout: post
title: "Accurate Urban Road Centerline Extraction from VHR Imagery via Multiscale Segmentation and Tensor Voting"
date: 2016-02-25 15:29:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Quantitative
author: Guangliang Cheng, Feiyun Zhu, Shiming Xiang, Chunhong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
It is very useful and increasingly popular to extract accurate road centerlines from very-high-resolution (VHR) re- mote sensing imagery for various applications, such as road map generation and updating etc. There are three shortcomings of current methods: (a) Due to the noise and occlusions (owing to vehicles and trees), most road extraction methods bring in heterogeneous classification results; (b) Morphological thinning algorithm is widely used to extract road centerlines, while it pro- duces small spurs around the centerlines; (c) Many methods are ineffective to extract centerlines around the road intersections. To address the above three issues, we propose a novel method to ex- tract smooth and complete road centerlines via three techniques: the multiscale joint collaborative representation (MJCR) & graph cuts (GC), tensor voting (TV) & non-maximum suppression (NMS) and fitting based connection algorithm. Specifically, a MJCR-GC based road area segmentation method is proposed by incorporating mutiscale features and spatial information. In this way, a homogenous road segmentation result is achieved. Then, to obtain a smooth and correct road centerline network, a TV-NMS based centerline extraction method is introduced. This method not only extracts smooth road centerlines, but also connects the discontinuous road centerlines. Finally, to overcome the ineffectiveness of current methods in the road intersection, a fitting based road centerline connection algorithm is proposed. As a result, we can get a complete road centerline network. Extensive experiments on two datasets demonstrate that our method achieves higher quantitative results, as well as more satisfactory visual performances by comparing with state-of-the- art methods.

##### Abstract (translated by Google)
从非常高分辨率（VHR）遥感图像中提取准确的道路中心线对于路线图生成和更新等各种应用是非常有用和日益流行的。目前的方法有三个缺点：（a）由于噪声和遮挡（由车辆和树木引起），大多数道路提取方法带来不均匀的分类结果; （b）形态细化算法被广泛用于提取道路中心线，同时在中心线周围产生小的杂散; （c）许多方法无法提取道路交叉口周围的中心线。为解决上述三个问题，我们提出了一种新的方法，通过三种技术来提取平滑和完整的道路中心线：多尺度联合协作表示（MJCR）和图割（GC），张量投票（TV）和非最大抑制（NMS）和基于拟合的连接算法。具体而言，提出了一种基于MJCR-GC的道路区域分割方法，将多尺度特征和空间信息相结合。这样就实现了均匀的道路分割结果。然后，为了获得一个平滑和正确的道路中心线网络，介绍了一个基于TV-NMS的中心线提取方法。这种方法不仅可以提取光滑的道路中心线，还可以连接不连续的道路中心线。最后，为克服现有道路交叉口方法的不足，提出了一种基于拟合的道路中心线连接算法。因此，我们可以得到一个完整的道路中心线网络。对两个数据集的大量实验表明，我们的方法通过与最先进的方法进行比较，获得了更高的定量结果以及更令人满意的视觉表现。

##### URL
[https://arxiv.org/abs/1508.06163](https://arxiv.org/abs/1508.06163)

##### PDF
[https://arxiv.org/pdf/1508.06163](https://arxiv.org/pdf/1508.06163)

