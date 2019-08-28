---
layout: post
title: "Bottom-up Higher-Resolution Networks for Multi-Person Pose Estimation"
date: 2019-08-27 17:54:08
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Bowen Cheng, Bin Xiao, Jingdong Wang, Honghui Shi, Thomas S. Huang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we are interested in bottom-up multi-person human pose estimation. A typical bottom-up pipeline consists of two main steps: heatmap prediction and keypoint grouping. We mainly focus on the first step for improving heatmap prediction accuracy. We propose Higher-Resolution Network (HigherHRNet), which is a simple extension of the High-Resolution Network (HRNet). HigherHRNet generates higher-resolution feature maps by deconvolving the high-resolution feature maps outputted by HRNet, which are spatially more accurate for small and medium persons. Then, we build high-quality multi-level features and perform multi-scale pose prediction. The extra computation overhead is marginal and negligible in comparison to existing bottom-up methods that rely on multi-scale image pyramids or large input image size to generate accurate pose heatmaps. HigherHRNet surpasses all existing bottom-up methods on the COCO dataset without using multi-scale test. The code and models will be released.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10357](http://arxiv.org/abs/1908.10357)

##### PDF
[http://arxiv.org/pdf/1908.10357](http://arxiv.org/pdf/1908.10357)

