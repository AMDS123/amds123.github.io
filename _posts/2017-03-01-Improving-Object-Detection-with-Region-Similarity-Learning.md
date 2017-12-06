---
layout: post
title: "Improving Object Detection with Region Similarity Learning"
date: 2017-03-01 11:16:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Feng Gao, Yihang Lou, Yan Bai, Shiqi Wang, Tiejun Huang, Ling-Yu Duan
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection aims to identify instances of semantic objects of a certain class in images or videos. The success of state-of-the-art approaches is attributed to the significant progress of object proposal and convolutional neural networks (CNNs). Most promising detectors involve multi-task learning with an optimization objective of softmax loss and regression loss. The first is for multi-class categorization, while the latter is for improving localization accuracy. However, few of them attempt to further investigate the hardness of distinguishing different sorts of distracting background regions (i.e., negatives) from true object regions (i.e., positives). To improve the performance of classifying positive object regions vs. a variety of negative background regions, we propose to incorporate triplet embedding into learning objective. The triplet units are formed by assigning each negative region to a meaningful object class and establishing class- specific negatives, followed by triplets construction. Over the benchmark PASCAL VOC 2007, the proposed triplet em- bedding has improved the performance of well-known FastRCNN model with a mAP gain of 2.1%. In particular, the state-of-the-art approach OHEM can benefit from the triplet embedding and has achieved a mAP improvement of 1.2%.

##### Abstract (translated by Google)
对象检测旨在识别图像或视频中某个类的语义对象的实例。最先进方法的成功归因于目标提议和卷积神经网络（CNN）的重大进展。最有希望的检测器涉及多任务学习，具有softmax损失和回归损失的优化目标。首先是多类分类，而后者则是提高定位精度。然而，他们中很少有人尝试进一步研究区分来自真实对象区域（即，正面）的不同种类的分散背景区域（即负片）的硬度。为了提高正面对象区域与各种负面背景区域的分类性能，我们建议将三重嵌入到学习目标中。三元组单元是通过将每个负区域分配给一个有意义的对象类别并建立类别特定的负数，然后构建三元组来构建的。在PASCAL VOC 2007的基准测试中，所提出的三重空间模型提高了着名的FastRCNN模型的性能，其mAP增益为2.1％。具体而言，最先进的方法OHEM可以从三元组嵌入中受益，并且已经实现了1.2％的mAP改进。

##### URL
[https://arxiv.org/abs/1703.00234](https://arxiv.org/abs/1703.00234)

