---
layout: post
title: "Feature Selective Networks for Object Detection"
date: 2017-11-24 06:39:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Classification Detection
author: Yao Zhai, Jingjing Fu, Yan Lu, Houqiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Objects for detection usually have distinct characteristics in different sub-regions and different aspect ratios. However, in prevalent two-stage object detection methods, Region-of-Interest (RoI) features are extracted by RoI pooling with little emphasis on these translation-variant feature components. We present feature selective networks to reform the feature representations of RoIs by exploiting their disparities among sub-regions and aspect ratios. Our network produces the sub-region attention bank and aspect ratio attention bank for the whole image. The RoI-based sub-region attention map and aspect ratio attention map are selectively pooled from the banks, and then used to refine the original RoI features for RoI classification. Equipped with a light-weight detection subnetwork, our network gets a consistent boost in detection performance based on general ConvNet backbones (ResNet-101, GoogLeNet and VGG-16). Without bells and whistles, our detectors equipped with ResNet-101 achieve more than 3% mAP improvement compared to counterparts on PASCAL VOC 2007, PASCAL VOC 2012 and MS COCO datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.08879](https://arxiv.org/abs/1711.08879)

##### PDF
[https://arxiv.org/pdf/1711.08879](https://arxiv.org/pdf/1711.08879)

