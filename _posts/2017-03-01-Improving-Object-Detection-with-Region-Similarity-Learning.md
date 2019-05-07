---
layout: post
title: "Improving Object Detection with Region Similarity Learning"
date: 2017-03-01 11:16:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding CNN Optimization Detection
author: Feng Gao, Yihang Lou, Yan Bai, Shiqi Wang, Tiejun Huang, Ling-Yu Duan
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection aims to identify instances of semantic objects of a certain class in images or videos. The success of state-of-the-art approaches is attributed to the significant progress of object proposal and convolutional neural networks (CNNs). Most promising detectors involve multi-task learning with an optimization objective of softmax loss and regression loss. The first is for multi-class categorization, while the latter is for improving localization accuracy. However, few of them attempt to further investigate the hardness of distinguishing different sorts of distracting background regions (i.e., negatives) from true object regions (i.e., positives). To improve the performance of classifying positive object regions vs. a variety of negative background regions, we propose to incorporate triplet embedding into learning objective. The triplet units are formed by assigning each negative region to a meaningful object class and establishing class- specific negatives, followed by triplets construction. Over the benchmark PASCAL VOC 2007, the proposed triplet em- bedding has improved the performance of well-known FastRCNN model with a mAP gain of 2.1%. In particular, the state-of-the-art approach OHEM can benefit from the triplet embedding and has achieved a mAP improvement of 1.2%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.00234](https://arxiv.org/abs/1703.00234)

##### PDF
[https://arxiv.org/pdf/1703.00234](https://arxiv.org/pdf/1703.00234)

