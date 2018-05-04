---
layout: post
title: "Stacked U-Nets: A No-Frills Approach to Natural Image Segmentation"
date: 2018-04-27 05:03:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Classification Detection
author: Sohil Shah, Pallabi Ghosh, Larry S Davis, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Many imaging tasks require global information about all pixels in an image. Conventional bottom-up classification networks globalize information by decreasing resolution; features are pooled and downsampled into a single output. But for semantic segmentation and object detection tasks, a network must provide higher-resolution pixel-level outputs. To globalize information while preserving resolution, many researchers propose the inclusion of sophisticated auxiliary blocks, but these come at the cost of a considerable increase in network size and computational cost. This paper proposes stacked u-nets (SUNets), which iteratively combine features from different resolution scales while maintaining resolution. SUNets leverage the information globalization power of u-nets in a deeper network architectures that is capable of handling the complexity of natural images. SUNets perform extremely well on semantic segmentation tasks using a small number of parameters.

##### Abstract (translated by Google)
许多成像任务需要有关图像中所有像素的全局信息。常规的自下而上分类网络通过降低分辨率来全球化信息;功能汇集并缩减为单个输出。但是对于语义分割和对象检测任务，网络必须提供更高分辨率的像素级输出。为了在保持解决方案的同时全球化信息，许多研究人员提出了包含复杂的辅助模块，但这些代价是网络规模和计算成本大幅增加的代价。本文提出堆叠式网络（SUNets），它在保持分辨率的同时迭代地组合不同分辨率尺度的特征。 SUNets在能够处理自然图像复杂性的深层网络架构中充分利用了U-net的信息全球化能力。使用少量参数，SUNets在语义分割任务上表现出色。

##### URL
[https://arxiv.org/abs/1804.10343](https://arxiv.org/abs/1804.10343)

##### PDF
[https://arxiv.org/pdf/1804.10343](https://arxiv.org/pdf/1804.10343)

