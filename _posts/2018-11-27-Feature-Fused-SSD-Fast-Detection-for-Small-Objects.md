---
layout: post
title: "Feature-Fused SSD: Fast Detection for Small Objects"
date: 2018-11-27 03:54:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Guimei Cao, Xuemei Xie, Wenzhe Yang, Quan Liao, Guangming Shi, Jinjian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Small objects detection is a challenging task in computer vision due to its limited resolution and information. In order to solve this problem, the majority of existing methods sacrifice speed for improvement in accuracy. In this paper, we aim to detect small objects at a fast speed, using the best object detector Single Shot Multibox Detector (SSD) with respect to accuracy-vs-speed trade-off as base architecture. We propose a multi-level feature fusion method for introducing contextual information in SSD, in order to improve the accuracy for small objects. In detailed fusion operation, we design two feature fusion modules, concatenation module and element-sum module, different in the way of adding contextual information. Experimental results show that these two fusion modules obtain higher mAP on PASCALVOC2007 than baseline SSD by 1.6 and 1.7 points respectively, especially with 2-3 points improvement on some smallobjects categories. The testing speed of them is 43 and 40 FPS respectively, superior to the state of the art Deconvolutional single shot detector (DSSD) by 29.4 and 26.4 FPS. Code is available at https://github.com/wnzhyee/Feature-Fused-SSD. Keywords: small object detection, feature fusion, real-time, single shot multi-box detector

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.05054](http://arxiv.org/abs/1709.05054)

##### PDF
[http://arxiv.org/pdf/1709.05054](http://arxiv.org/pdf/1709.05054)

