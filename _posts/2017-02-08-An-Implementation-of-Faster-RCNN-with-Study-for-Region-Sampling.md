---
layout: post
title: "An Implementation of Faster RCNN with Study for Region Sampling"
date: 2017-02-08 07:02:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Xinlei Chen, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
We adapted the join-training scheme of Faster RCNN framework from Caffe to TensorFlow as a baseline implementation for object detection. Our code is made publicly available. This report documents the simplifications made to the original pipeline, with justifications from ablation analysis on both PASCAL VOC 2007 and COCO 2014. We further investigated the role of non-maximal suppression (NMS) in selecting regions-of-interest (RoIs) for region classification, and found that a biased sampling toward small regions helps performance and can achieve on-par mAP to NMS-based sampling when converged sufficiently.

##### Abstract (translated by Google)
我们将从Caffe到TensorFlow的更快的RCNN框架的加入训练方案作为对象检测的基准实现进行了调整。我们的代码是公开的。本报告记录了对原始管道的简化，并对PASCAL VOC 2007和COCO 2014的消融分析提供了理由。我们进一步研究了非最大抑制（NMS）在区域选择区域（RoIs）中的作用分类，并发现对小区域的偏倚抽样有助于提高性能，并能够在充分收敛的情况下实现与基于NMS的抽样的一致性。

##### URL
[https://arxiv.org/abs/1702.02138](https://arxiv.org/abs/1702.02138)

##### PDF
[https://arxiv.org/pdf/1702.02138](https://arxiv.org/pdf/1702.02138)

