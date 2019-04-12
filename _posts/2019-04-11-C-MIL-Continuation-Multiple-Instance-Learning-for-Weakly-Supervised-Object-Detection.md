---
layout: post
title: "C-MIL: Continuation Multiple Instance Learning for Weakly Supervised Object Detection"
date: 2019-04-11 11:59:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Optimization Detection
author: Fang Wan, Chang Liu, Wei Ke, Xiangyang Ji, Jianbin Jiao, Qixiang Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object detection (WSOD) is a challenging task when provided with image category supervision but required to simultaneously learn object locations and object detectors. Many WSOD approaches adopt multiple instance learning (MIL) and have non-convex loss functions which are prone to get stuck into local minima (falsely localize object parts) while missing full object extent during training. In this paper, we introduce a continuation optimization method into MIL and thereby creating continuation multiple instance learning (C-MIL), with the intention of alleviating the non-convexity problem in a systematic way. We partition instances into spatially related and class related subsets, and approximate the original loss function with a series of smoothed loss functions defined within the subsets. Optimizing smoothed loss functions prevents the training procedure falling prematurely into local minima and facilitates the discovery of Stable Semantic Extremal Regions (SSERs) which indicate full object extent. On the PASCAL VOC 2007 and 2012 datasets, C-MIL improves the state-of-the-art of weakly supervised object detection and weakly supervised object localization with large margins.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05647](http://arxiv.org/abs/1904.05647)

##### PDF
[http://arxiv.org/pdf/1904.05647](http://arxiv.org/pdf/1904.05647)

