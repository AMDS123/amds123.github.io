---
layout: post
title: "Object Detection Networks on Convolutional Feature Maps"
date: 2016-08-17 15:51:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Shaoqing Ren, Kaiming He, Ross Girshick, Xiangyu Zhang, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Most object detectors contain two important components: a feature extractor and an object classifier. The feature extractor has rapidly evolved with significant research efforts leading to better deep convolutional architectures. The object classifier, however, has not received much attention and many recent systems (like SPPnet and Fast/Faster R-CNN) use simple multi-layer perceptrons. This paper demonstrates that carefully designing deep networks for object classification is just as important. We experiment with region-wise classifier networks that use shared, region-independent convolutional features. We call them "Networks on Convolutional feature maps" (NoCs). We discover that aside from deep feature maps, a deep and convolutional per-region classifier is of particular importance for object detection, whereas latest superior image classification models (such as ResNets and GoogLeNets) do not directly lead to good detection accuracy without using such a per-region classifier. We show by experiments that despite the effective ResNets and Faster R-CNN systems, the design of NoCs is an essential element for the 1st-place winning entries in ImageNet and MS COCO challenges 2015.

##### Abstract (translated by Google)
大多数对象检测器包含两个重要的组件：一个特征提取器和一个对象分类器。特征提取器已经迅速发展，并进行了大量的研究工作，导致更好的深度卷积体系结构。然而，目标分类器并没有受到太多关注，许多最近的系统（如SPPnet和Fast / Raster R-CNN）都使用简单的多层感知器。本文表明，精心设计深度网络进行物体分类同样重要。我们尝试使用共享的区域独立卷积特征的区域分类器网络。我们称之为“卷积特征映射网络”（NoC）。我们发现，除了深度特征图之外，深度和卷积的每个区域分类器对于物体检测是特别重要的，而最新的优越图像分类模型（例如ResNets和GoogLeNets）不直接导致良好的检测精度而不使用这样的按区域分类器。我们通过实验证明，尽管有效的ResNets和更快的R-CNN系统，NoC的设计对于2015年ImageNet和MS COCO挑战中的第一名获奖作品来说是必不可少的元素。

##### URL
[https://arxiv.org/abs/1504.06066](https://arxiv.org/abs/1504.06066)

