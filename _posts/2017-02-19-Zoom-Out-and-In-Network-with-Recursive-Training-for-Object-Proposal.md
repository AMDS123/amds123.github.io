---
layout: post
title: "Zoom Out-and-In Network with Recursive Training for Object Proposal"
date: 2017-02-19 07:43:27
categories: arXiv_CV
tags: arXiv_CV Detection
author: Hongyang Li, Yu Liu, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a zoom-out-and-in network for generating object proposals. We utilize different resolutions of feature maps in the network to detect object instances of various sizes. Specifically, we divide the anchor candidates into three clusters based on the scale size and place them on feature maps of distinct strides to detect small, medium and large objects, respectively. Deeper feature maps contain region-level semantics which can help shallow counterparts to identify small objects. Therefore we design a zoom-in sub-network to increase the resolution of high level features via a deconvolution operation. The high-level features with high resolution are then combined and merged with low-level features to detect objects. Furthermore, we devise a recursive training pipeline to consecutively regress region proposals at the training stage in order to match the iterative regression at the testing stage. We demonstrate the effectiveness of the proposed method on ILSVRC DET and MS COCO datasets, where our algorithm performs better than the state-of-the-arts in various evaluation metrics. It also increases average precision by around 2% in the detection system.

##### Abstract (translated by Google)
在本文中，我们提出了一个生成对象提议的缩小和放大网络。我们利用网络中的特征映射的不同分辨率来检测各种大小的对象实例。具体而言，我们根据尺度大小将锚点候选分为三个类，并将它们放置在不同步的特征地图上，以分别检测小，中，大物体。更深的特征映射包含区域级语义，可以帮助浅层对象识别小对象。因此，我们设计一个放大子网络，通过解卷积操作来提高高级特征的分辨率。然后将高分辨率的高级特征组合并与低级特征合并以检测对象。此外，我们设计了一个递归训练管道，在训练阶段连续回归区域提议，以匹配测试阶段的迭代回归。我们在ILSVRC DET和MS COCO数据集上展示了所提出的方法的有效性，其中我们的算法在各种评估指标中比现有技术表现更好。在检测系统中，平均精度也提高了2％左右。

##### URL
[https://arxiv.org/abs/1702.05711](https://arxiv.org/abs/1702.05711)

##### PDF
[https://arxiv.org/pdf/1702.05711](https://arxiv.org/pdf/1702.05711)

