---
layout: post
title: "Inverted Residuals and Linear Bottlenecks: Mobile Networks forClassification, Detection and Segmentation"
date: 2018-01-13 04:46:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Classification Detection
author: Mark Sandler, Andrew Howard, Menglong Zhu, Andrey Zhmoginov, Liang-Chieh Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we describe a new mobile architecture, MobileNetV2, that improves the state of the art performance of mobile models on multiple tasks and benchmarks as well as across a spectrum of different model sizes. We also describe efficient ways of applying these mobile models to object detection in a novel framework we call SSDLite. Additionally, we demonstrate how to build mobile semantic segmentation models through a reduced form of DeepLabv3 which we call Mobile DeepLabv3. The MobileNetV2 architecture is based on an inverted residual structure where the input and output of the residual block are thin bottleneck layers opposite to traditional residual models which use expanded representations in the input an MobileNetV2 uses lightweight depthwise convolutions to filter features in the intermediate expansion layer. Additionally, we find that it is important to remove non-linearities in the narrow layers in order to maintain representational power. We demonstrate that this improves performance and provide an intuition that led to this design. Finally, our approach allows decoupling of the input/output domains from the expressiveness of the transformation, which provides a convenient framework for further analysis. We measure our performance on Imagenet classification, COCO object detection, VOC image segmentation. We evaluate the trade-offs between accuracy, and number of operations measured by multiply-adds (MAdd), as well as the number of parameters

##### Abstract (translated by Google)
在本文中，我们将介绍一种新的移动体系结构MobileNetV2，该体系结构改善了多个任务和基准以及不同模型大小的移动模型的性能状态。我们还描述了在一个我们称为SSDLite的新型框架中将这些移动模型应用于对象检测的有效方法。另外，我们演示了如何通过称为Mobile DeepLabv3的简化形式DeepLabv3来构建移动语义分割模型。 MobileNetV2架构基于反向残差结构，其中残差块的输入和输出是与传统残差模型相反的薄瓶颈层，在输入中使用扩展表示MobileNetV2使用轻量级深度卷积来过滤中间展开层中的特征。此外，我们发现去除窄层中的非线性以保持表示能力是重要的。我们证明，这提高了性能，并提供了导致这种设计的直觉。最后，我们的方法允许将输入/输出域与转换的表现性分离，这为进一步的分析提供了便利的框架。我们测量了Imagenet分类，COCO物体检测，VOC图像分割的性能。我们评估精度和通过乘加（MAdd）测量的操作次数之间的平衡，以及参数的数量

##### URL
[https://arxiv.org/abs/1801.04381](https://arxiv.org/abs/1801.04381)

##### PDF
[https://arxiv.org/pdf/1801.04381](https://arxiv.org/pdf/1801.04381)

