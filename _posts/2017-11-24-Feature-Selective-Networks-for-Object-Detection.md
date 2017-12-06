---
layout: post
title: "Feature Selective Networks for Object Detection"
date: 2017-11-24 06:39:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yao Zhai, Jingjing Fu, Yan Lu, Houqiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Objects for detection usually have distinct characteristics in different sub-regions and different aspect ratios. However, in prevalent two-stage object detection methods, Region-of-Interest (RoI) features are extracted by RoI pooling with little emphasis on these translation-variant feature components. We present feature selective networks to reform the feature representations of RoIs by exploiting their disparities among sub-regions and aspect ratios. Our network produces the sub-region attention bank and aspect ratio attention bank for the whole image. The RoI-based sub-region attention map and aspect ratio attention map are selectively pooled from the banks, and then used to refine the original RoI features for RoI classification. Equipped with a light-weight detection subnetwork, our network gets a consistent boost in detection performance based on general ConvNet backbones (ResNet-101, GoogLeNet and VGG-16). Without bells and whistles, our detectors equipped with ResNet-101 achieve more than 3% mAP improvement compared to counterparts on PASCAL VOC 2007, PASCAL VOC 2012 and MS COCO datasets.

##### Abstract (translated by Google)
用于检测的对象通常在不同的子区域和不同的长宽比中具有不同的特征。然而，在流行的两阶段对象检测方法中，通过RoI池提取兴趣区域（RoI）特征，而不重视这些变换特征分量。我们提出特征选择性网络，通过利用它们在不同子区域和纵横比上的差异，来改变ROI的特征表示。我们的网络为整个图像产生子区域注意组和长宽比注意组。基于RoI的子区域注意图和长宽比注意图从这些存储体中选择性地汇集，然后用于细化用于RoI分类的原始的RoI特征。基于通用ConvNet骨干网（ResNet-101，GoogLeNet和VGG-16），我们的网络配备了一个轻量级检测子网络，在检测性能方面获得了持续的提升。与PASCAL VOC 2007，PASCAL VOC 2012和MS COCO数据集相比，我们配备ResNet-101的探测器无需花时间就能实现3％以上的mAP改进。

##### URL
[https://arxiv.org/abs/1711.08879](https://arxiv.org/abs/1711.08879)

