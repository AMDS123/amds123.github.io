---
layout: post
title: "MDSSD: Multi-scale Deconvolutional Single Shot Detector for small objects"
date: 2018-05-18 01:09:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Prediction Detection
author: Lisha Cui
mathjax: true
---

* content
{:toc}

##### Abstract
In order to improve the detection accuracy for objects at different scales, most of the recent works utilize the pyramidal feature hierarchy of the ConvNets from bottom to top. Nevertheless, the weak semantic information makes the bottom layers poor in detection, especially for small objects. Furthermore, most of the fine details are lost on the top layers. In this paper, we design a Multi-scale Deconvolutional Single Shot Detector for small objects (MDSSD for short). To obtain the feature maps with enriched representation power, we add the high-level layers with semantic information to the low-level layers via deconvolution Fusion Block. It is noteworthy that multiple high-level layers with different scales are upsampled simultaneously in our framework. We implement the skip connections to form more descriptive feature maps and predictions are made on these new fusion layers. Our proposed framework achieves 78.6% mAP on PASCAL VOC2007 test and 26.8% mAP on MS COCO test-dev2015 at 38.5 FPS with only 300*300 input.

##### Abstract (translated by Google)
为了提高不同尺度对象的检测精度，近期的大部分工作都是利用ConvNets从下到上的金字塔特征层次结构。然而，弱语义信息使得底层检测较差，特别是对于小物体。此外，大多数细节都丢在顶层。在本文中，我们为小物体（简称MDSSD）设计了多尺度解卷积单射检测器。为了获得具有丰富表示能力的特征映射，我们通过去卷积融合块将具有语义信息的高层图层添加到低层图层。值得注意的是，在我们的框架中同时对不同尺度的多个高级图层进行上采样。我们实现跳过连接以形成更多的描述性特征映射，并对这些新的融合层进行预测。我们提出的框架在PASCAL VOC2007测试中达到78.6％的mAP，在MS COCO test-dev2015上达到26.8％的mAP，达到38.5 FPS，仅有300 * 300的输入。

##### URL
[http://arxiv.org/abs/1805.07009](http://arxiv.org/abs/1805.07009)

##### PDF
[http://arxiv.org/pdf/1805.07009](http://arxiv.org/pdf/1805.07009)

