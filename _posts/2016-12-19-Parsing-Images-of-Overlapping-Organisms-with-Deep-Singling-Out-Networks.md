---
layout: post
title: "Parsing Images of Overlapping Organisms with Deep Singling-Out Networks"
date: 2016-12-19 00:59:30
categories: arXiv_CV
tags: arXiv_CV GAN Optimization
author: Victor Yurchenko, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
This work is motivated by the mostly unsolved task of parsing biological images with multiple overlapping articulated model organisms (such as worms or larvae). We present a general approach that separates the two main challenges associated with such data, individual object shape estimation and object groups disentangling. At the core of the approach is a deep feed-forward singling-out network (SON) that is trained to map each local patch to a vectorial descriptor that is sensitive to the characteristics (e.g. shape) of a central object, while being invariant to the variability of all other surrounding elements. Given a SON, a local image patch can be matched to a gallery of isolated elements using their SON-descriptors, thus producing a hypothesis about the shape of the central element in that patch. The image-level optimization based on integer programming can then pick a subset of the hypotheses to explain (parse) the whole image and disentangle groups of organisms. While sharing many similarities with existing "analysis-by-synthesis" approaches, our method avoids the need for stochastic search in the high-dimensional configuration space and numerous rendering operations at test-time. We show that our approach can parse microscopy images of three popular model organisms (the C.Elegans roundworms, the Drosophila larvae, and the E.Coli bacteria) even under significant crowding and overlaps between organisms. We speculate that the overall approach is applicable to a wider class of image parsing problems concerned with crowded articulated objects, for which rendering training images is possible.

##### Abstract (translated by Google)
这项工作的动机是解析生物图像与多重叠关节模型生物（如蠕虫或幼虫）的最基本未解决的任务。我们提出了一个通用的方法来分离与这些数据相关的两个主要挑战，单个对象形状估计和对象组的解构。该方法的核心是深度前馈单出网络（SON），训练用于将每个本地补丁映射到对中心对象的特征（例如形状）敏感的矢量描述符，同时不变所有其他周围元素的可变性。给定一个SON，一个局部图像补丁可以使用它们的SON描述符与一个孤立元素库相匹配，从而产生一个关于该补丁中的中心元素形状的假设。然后基于整数规划的图像级优化可以选择假设的子集来解释（解析）整个图像并分解生物体组。虽然与现有的“综合分析”方法有许多相似之处，但我们的方法避免了在高维配置空间中进行随机搜索以及在测试时进行大量渲染操作的需要。我们表明，我们的方法可以解析三个流行的模式生物（C.Elegans蛔虫，果蝇幼虫和大肠杆菌细菌）的显微镜图像，甚至在生物之间的重大拥挤和重叠。我们推测整体方法适用于涉及拥挤的铰接物体的较宽泛类别的图像分析问题，为此可能提供训练图像。

##### URL
[https://arxiv.org/abs/1612.06017](https://arxiv.org/abs/1612.06017)

##### PDF
[https://arxiv.org/pdf/1612.06017](https://arxiv.org/pdf/1612.06017)

