---
layout: post
title: "Instance-sensitive Fully Convolutional Networks"
date: 2016-03-29 08:37:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Jifeng Dai, Kaiming He, Yi Li, Shaoqing Ren, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional networks (FCNs) have been proven very successful for semantic segmentation, but the FCN outputs are unaware of object instances. In this paper, we develop FCNs that are capable of proposing instance-level segment candidates. In contrast to the previous FCN that generates one score map, our FCN is designed to compute a small set of instance-sensitive score maps, each of which is the outcome of a pixel-wise classifier of a relative position to instances. On top of these instance-sensitive score maps, a simple assembling module is able to output instance candidate at each position. In contrast to the recent DeepMask method for segmenting instances, our method does not have any high-dimensional layer related to the mask resolution, but instead exploits image local coherence for estimating instances. We present competitive results of instance segment proposal on both PASCAL VOC and MS COCO.

##### Abstract (translated by Google)
完全卷积网络（FCN）已经被证明在语义分割方面非常成功，但是FCN输出并不知道对象实例。在本文中，我们开发了能够提出实例级别候选人的FCN。与前一个生成一个分数图的FCN相比，我们的FCN被设计用于计算一组小的实例敏感分数图，每个分数图都是一个像素相对于实例相对位置的分类器的结果。在这些实例敏感的分数图之上，一个简单的组装模块能够在每个位置输出实例候选。与最近用于分割实例的DeepMask方法相比，我们的方法没有任何与掩模分辨率有关的高维层，而是利用图像局部相干性来估计实例。我们在PASCAL VOC和MS COCO上展示实例分部提案的竞争结果。

##### URL
[https://arxiv.org/abs/1603.08678](https://arxiv.org/abs/1603.08678)

##### PDF
[https://arxiv.org/pdf/1603.08678](https://arxiv.org/pdf/1603.08678)

