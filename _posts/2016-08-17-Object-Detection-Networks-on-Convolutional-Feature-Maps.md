---
layout: post
title: "Object Detection Networks on Convolutional Feature Maps"
date: 2016-08-17 15:51:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Image_Classification Classification Detection
author: Shaoqing Ren, Kaiming He, Ross Girshick, Xiangyu Zhang, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Most object detectors contain two important components: a feature extractor and an object classifier. The feature extractor has rapidly evolved with significant research efforts leading to better deep convolutional architectures. The object classifier, however, has not received much attention and many recent systems (like SPPnet and Fast/Faster R-CNN) use simple multi-layer perceptrons. This paper demonstrates that carefully designing deep networks for object classification is just as important. We experiment with region-wise classifier networks that use shared, region-independent convolutional features. We call them "Networks on Convolutional feature maps" (NoCs). We discover that aside from deep feature maps, a deep and convolutional per-region classifier is of particular importance for object detection, whereas latest superior image classification models (such as ResNets and GoogLeNets) do not directly lead to good detection accuracy without using such a per-region classifier. We show by experiments that despite the effective ResNets and Faster R-CNN systems, the design of NoCs is an essential element for the 1st-place winning entries in ImageNet and MS COCO challenges 2015.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1504.06066](https://arxiv.org/abs/1504.06066)

##### PDF
[https://arxiv.org/pdf/1504.06066](https://arxiv.org/pdf/1504.06066)

