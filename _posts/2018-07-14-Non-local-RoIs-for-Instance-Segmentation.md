---
layout: post
title: "Non-local RoIs for Instance Segmentation"
date: 2018-07-14 08:58:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Detection Relation
author: Shou-Yao Roy Tseng, Hwann-Tzong Chen, Shao-Heng Tai, Tyng-Luh Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the concept of Non-Local RoI (NL-RoI) Block as a generic and flexible module that can be seamlessly adapted into different Mask R-CNN heads for various tasks. Mask R-CNN treats RoIs (Regions of Interest) independently and performs the prediction based on individual object bounding boxes. However, the correlation between objects may provide useful information for detection and segmentation. The proposed NL-RoI Block enables each RoI to refer to all other RoIs' information, and results in a simple, low-cost but effective module. Our experimental results show that generalizations with NL-RoI Blocks can improve the performance of Mask R-CNN for instance segmentation on the Robust Vision Challenge benchmarks.

##### Abstract (translated by Google)
我们将非本地RoI（NL-RoI）块的概念作为通用且灵活的模块引入，可以无缝地适应不同的Mask R-CNN头以执行各种任务。掩码R-CNN独立地处理RoI（感兴趣区域）并基于各个对象边界框执行预测。然而，对象之间的相关性可以提供用于检测和分割的有用信息。建议的NL-RoI块使每个RoI能够引用所有其他RoI的信息，从而形成一个简单，低成本但有效的模块。我们的实验结果表明，使用NL-RoI块的推广可以提高Mask R-CNN的性能，例如在Robust Vision Challenge基准测试中进行分段。

##### URL
[http://arxiv.org/abs/1807.05361](http://arxiv.org/abs/1807.05361)

##### PDF
[http://arxiv.org/pdf/1807.05361](http://arxiv.org/pdf/1807.05361)

