---
layout: post
title: "Feature-Fused SSD: Fast Detection for Small Objects"
date: 2017-10-18 13:00:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Guimei Cao, Xuemei Xie, Wenzhe Yang, Quan Liao, Guangming Shi, Jinjian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Small objects detection is a challenging task in computer vision due to its limited resolution and information. In order to solve this problem, the majority of existing methods sacrifice speed for improvement in accuracy. In this paper, we aim to detect small objects at a fast speed, using the best object detector Single Shot Multibox Detector (SSD) with respect to accuracy-vs-speed trade-off as base architecture. We propose a multi-level feature fusion method for introducing contextual information in SSD, in order to improve the accuracy for small objects. In detailed fusion operation, we design two feature fusion modules, concatenation module and element-sum module, different in the way of adding contextual information. Experimental results show that these two fusion modules obtain higher mAP on PASCALVOC2007 than baseline SSD by 1.6 and 1.7 points respectively, especially with 2-3 points improvement on some smallobjects categories. The testing speed of them is 43 and 40 FPS respectively, superior to the state of the art Deconvolutional single shot detector (DSSD) by 29.4 and 26.4 FPS. Keywords: small object detection, feature fusion, real-time, single shot multi-box detector

##### Abstract (translated by Google)
由于分辨率和信息有限，小物体检测在计算机视觉领域是一项具有挑战性的任务。为了解决这个问题，大多数现有的方法牺牲了速度以提高准确性。在本文中，我们的目标是快速检测小物体，使用最佳的物体检测器Single Shot Multibox Detector（SSD）作为基准体系结构的精度与速度之间的折衷。我们提出了一种在SSD中引入上下文信息的多级特征融合方法，以提高小物体的准确性。在详细的融合操作中，我们设计了两个特征融合模块，连接模块和元素和模块，不同之处在于添加上下文信息。实验结果表明，这两种融合模块在PASCALVOC2007上得到的基线SSD比基线SSD分别提高了1.6和1.7个点，尤其是对于一些小对象类别，提高了2-3个点。它们的测试速度分别为43和40 FPS，优于目前最先进的解卷积单探测器（DSSD），达到29.4和26.4 FPS。关键词：小目标检测，特征融合，实时单射多盒探测器

##### URL
[https://arxiv.org/abs/1709.05054](https://arxiv.org/abs/1709.05054)

