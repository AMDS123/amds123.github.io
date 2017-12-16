---
layout: post
title: "Residual Features and Unified Prediction Network for Single Stage Detection"
date: 2017-11-29 07:17:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Kyoungmin Lee, Jaeseok Choi, Jisoo Jeong, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, a lot of single stage detectors using multi-scale features have been actively proposed. They are much faster than two stage detectors that use region proposal networks (RPN) without much degradation in the detection performances. However, the feature maps in the lower layers close to the input which are responsible for detecting small objects in a single stage detector have a problem of insufficient representation power because they are too shallow. There is also a structural contradiction that the feature maps have to deliver low-level information to next layers as well as contain high-level abstraction for prediction. In this paper, we propose a method to enrich the representation power of feature maps using Resblock and deconvolution layers. In addition, a unified prediction module is applied to generalize output results and boost earlier layers' representation power for prediction. The proposed method enables more precise prediction, which achieved higher score than SSD on PASCAL VOC and MS COCO. In addition, it maintains the advantage of fast computation of a single stage detector, which requires much less computation than other detectors with similar performance. Code is available at this https URL

##### Abstract (translated by Google)
近来，已经积极提出了许多使用多尺度特征的单级探测器。它们比使用区域提议网络（RPN）的两级检测器快得多，检测性能没有太大的降低。然而，在单级检测器中负责检测小物体的靠近输入的下层中的特征图由于太浅而具有不充分的表示能力的问题。还有一个结构性矛盾，即要素图必须向下一层提供低层信息，并且要包含高层次的抽象预测。在本文中，我们提出了一种使用Resblock和去卷积层来丰富特征映射的表示能力的方法。另外，统一预测模块用于推广输出结果，提高早期层次的预测代表能力。所提出的方法能够实现更精确的预测，在PASCAL VOC和MS COCO上得分高于SSD。此外，它保持了单级探测器快速计算的优点，与其他性能相近的探测器相比，这种方法的计算量要少得多。代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1707.05031](https://arxiv.org/abs/1707.05031)

##### PDF
[https://arxiv.org/pdf/1707.05031](https://arxiv.org/pdf/1707.05031)

