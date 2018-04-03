---
layout: post
title: "Multi-scale Location-aware Kernel Representation for Object Detection"
date: 2018-04-02 08:27:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Hao Wang, Qilong Wang, Mingqi Gao, Peihua Li, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Although Faster R-CNN and its variants have shown promising performance in object detection, they only exploit simple first-order representation of object proposals for final classification and regression. Recent classification methods demonstrate that the integration of high-order statistics into deep convolutional neural networks can achieve impressive improvement, but their goal is to model whole images by discarding location information so that they cannot be directly adopted to object detection. In this paper, we make an attempt to exploit high-order statistics in object detection, aiming at generating more discriminative representations for proposals to enhance the performance of detectors. To this end, we propose a novel Multi-scale Location-aware Kernel Representation (MLKP) to capture high-order statistics of deep features in proposals. Our MLKP can be efficiently computed on a modified multi-scale feature map using a low-dimensional polynomial kernel approximation.Moreover, different from existing orderless global representations based on high-order statistics, our proposed MLKP is location retentive and sensitive so that it can be flexibly adopted to object detection. Through integrating into Faster R-CNN schema, the proposed MLKP achieves very competitive performance with state-of-the-art methods, and improves Faster R-CNN by 4.9% (mAP), 4.7% (mAP) and 5.0% (AP at IOU=[0.5:0.05:0.95]) on PASCAL VOC 2007, VOC 2012 and MS COCO benchmarks, respectively. Code is available at: https://github.com/Hwang64/MLKP.

##### Abstract (translated by Google)
尽管更快的R-CNN及其变体在对象检测中表现出有希望的性能，但它们仅利用对象提议的简单一阶表示来进行最终分类和回归。最近的分类方法表明，将高阶统计量集成到深度卷积神经网络中可以实现令人印象深刻的改进，但他们的目标是通过丢弃位置信息对整个图像进行建模，以便它们不能直接用于对象检测。在本文中，我们尝试利用目标检测中的高阶统计量，旨在为提高检测器性能提出更多的判别式表示。为此，我们提出了一种新颖的多尺度位置感知内核表示（MLKP）来捕获提议中深度特征的高阶统计量。我们的MLKP可以使用低维多项式核近似有效地在修改后的多尺度特征图上计算。此外，与基于高阶统计量的现有无序全局表示不同，我们提出的MLKP具有位置保持性和敏感性，因此它可以灵活采用对象检测。通过融入更快的R-CNN模式，所提出的MLKP通过最先进的方法实现了非常有竞争力的表现，并且将R-CNN更快地提高了4.9％（mAP），4.7％（mAP）和5.0％ IOU = [0.5：0.05：0.95]），分别为PASCAL VOC 2007，VOC 2012和MS COCO基准。代码位于：https：//github.com/Hwang64/MLKP。

##### URL
[http://arxiv.org/abs/1804.00428](http://arxiv.org/abs/1804.00428)

##### PDF
[http://arxiv.org/pdf/1804.00428](http://arxiv.org/pdf/1804.00428)

