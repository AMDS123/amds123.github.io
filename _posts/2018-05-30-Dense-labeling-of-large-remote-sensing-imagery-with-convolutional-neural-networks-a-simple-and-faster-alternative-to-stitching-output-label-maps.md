---
layout: post
title: "Dense labeling of large remote sensing imagery with convolutional neural networks: a simple and faster alternative to stitching output label maps"
date: 2018-05-30 20:34:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Bohao Huang, Daniel Reichman, Leslie M. Collins, Kyle Bradbury, Jordan M. Malof
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we consider the application of convolutional neural networks (CNNs) for pixel-wise labeling (a.k.a., semantic segmentation) of remote sensing imagery (e.g., aerial color or hyperspectral imagery). Remote sensing imagery is usually stored in the form of very large images, referred to as "tiles", which are too large to be segmented directly using most CNNs and their associated hardware. As a result, during label inference, smaller sub-images, called "patches", are processed individually and then "stitched" (concatenated) back together to create a tile-sized label map. This approach suffers from computational ineffiency and can result in discontinuities at output boundaries. We propose a simple alternative approach in which the input size of the CNN is dramatically increased only during label inference. This does not avoid stitching altogether, but substantially mitigates its limitations. We evaluate the performance of the proposed approach against a vonventional stitching approach using two popular segmentation CNN models and two large-scale remote sensing imagery datasets. The results suggest that the proposed approach substantially reduces label inference time, while also yielding modest overall label accuracy increases. This approach contributed to our wining entry (overall performance) in the INRIA building labeling competition.

##### Abstract (translated by Google)
在这项工作中，我们考虑将卷积神经网络（CNN）应用于遥感图像（例如，航空颜色或高光谱图像）的像素方式标记（也称为语义分割）。遥感图像通常以非常大的图像形式存储，称为“图块”，这些图块太大而无法使用大多数CNN及其相关硬件直接分割。因此，在标签推理过程中，称为“补丁”的较小子图像会被单独处理，然后“缝合”（拼接）在一起以创建拼贴大小的标签贴图。这种方法遭受计算不足，并可能导致输出边界处的不连续性。我们提出了一种简单的替代方法，其中CNN的输入大小仅在标签推断期间显着增加。这并不能完全避免拼接，但可以大大减轻其局限性。我们使用两种流行的分割CNN模型和两个大规模遥感影像数据集来评估所提出的方法在针对vonventional拼接方法的性能。结果表明，所提出的方法显着减少了标签推断时间，同时也产生适度的整体标签准确度增加。这种方法有助于我们在INRIA建筑标签竞赛中获得入围（总体表现）。

##### URL
[http://arxiv.org/abs/1805.12219](http://arxiv.org/abs/1805.12219)

##### PDF
[http://arxiv.org/pdf/1805.12219](http://arxiv.org/pdf/1805.12219)

