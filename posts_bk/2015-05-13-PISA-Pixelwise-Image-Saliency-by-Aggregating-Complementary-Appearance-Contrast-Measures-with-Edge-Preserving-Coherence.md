---
layout: post
title: "PISA: Pixelwise Image Saliency by Aggregating Complementary Appearance Contrast Measures with Edge-Preserving Coherence"
date: 2015-05-13 03:05:46
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Optimization Detection Recognition
author: Keze Wang, Liang Lin, Jiangbo Lu, Chenglong Li, Keyang Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Driven by recent vision and graphics applications such as image segmentation and object recognition, computing pixel-accurate saliency values to uniformly highlight foreground objects becomes increasingly important. In this paper, we propose a unified framework called PISA, which stands for Pixelwise Image Saliency Aggregating various bottom-up cues and priors. It generates spatially coherent yet detail-preserving, pixel-accurate and fine-grained saliency, and overcomes the limitations of previous methods which use homogeneous superpixel-based and color only treatment. PISA aggregates multiple saliency cues in a global context such as complementary color and structure contrast measures with their spatial priors in the image domain. The saliency confidence is further jointly modeled with a neighborhood consistence constraint into an energy minimization formulation, in which each pixel will be evaluated with multiple hypothetical saliency levels. Instead of using global discrete optimization methods, we employ the cost-volume filtering technique to solve our formulation, assigning the saliency levels smoothly while preserving the edge-aware structure details. In addition, a faster version of PISA is developed using a gradient-driven image sub-sampling strategy to greatly improve the runtime efficiency while keeping comparable detection accuracy. Extensive experiments on a number of public datasets suggest that PISA convincingly outperforms other state-of-the-art approaches. In addition, with this work we also create a new dataset containing $800$ commodity images for evaluating saliency detection. The dataset and source code of PISA can be downloaded at this http URL

##### Abstract (translated by Google)
在最近的视觉和图形应用（如图像分割和对象识别）的驱动下，计算像素精确的显着值以均匀地突出前景对象变得越来越重要。在本文中，我们提出了一个名为PISA的统一框架，它代表Pixelwise图像显着性聚合各种自下而上的线索和先验。它产生空间连贯但细节保留，像素精确和细粒度的显着性，并克服了以前使用均匀的基于超像素和彩色处理的方法的局限性。 PISA在全球背景下聚合多个显着性提示，例如互补色和结构对比度测量以及图像域中的空间先验。显着性置信度进一步与邻域一致性约束一起建模成能量最小化公式，其中将以多个假设显着性水平来评估每个像素。我们不采用全局离散优化方法，而是采用成本体积滤波技术来解决我们的公式，在保留边缘感知结构细节的同时平滑地分配显着性水平。此外，使用梯度驱动的图像子采样策略开发了更快版本的PISA，可极大地提高运行效率，同时保持可比较的检测精度。大量的公共数据集上的大量实验表明，PISA令人信服地胜过了其他最先进的方法。此外，通过这项工作，我们还创建了一个包含$ 800 $商品图像的新数据集，用于评估显着性检测。 PISA的数据集和源代码可以在这个http URL下载

##### URL
[https://arxiv.org/abs/1505.03227](https://arxiv.org/abs/1505.03227)

##### PDF
[https://arxiv.org/pdf/1505.03227](https://arxiv.org/pdf/1505.03227)

