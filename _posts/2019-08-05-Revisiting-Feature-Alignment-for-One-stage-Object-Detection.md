---
layout: post
title: "Revisiting Feature Alignment for One-stage Object Detection"
date: 2019-08-05 12:00:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Detection
author: Yuntao Chen, Chenxia Han, Naiyan Wang, Zhaoxiang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, one-stage object detectors gain much attention due to their simplicity in practice. Its fully convolutional nature greatly reduces the difficulty of training and deployment compared with two-stage detectors which require NMS and sorting for the proposal stage. However, a fundamental issue lies in all one-stage detectors is the misalignment between anchor boxes and convolutional features, which significantly hinders the performance of one-stage detectors. In this work, we first reveal the deep connection between the widely used im2col operator and the RoIAlign operator. Guided by this illuminating observation, we propose a RoIConv operator which aligns the features and its corresponding anchors in one-stage detection in a principled way. We then design a fully convolutional AlignDet architecture which combines the flexibility of learned anchors and the preciseness of aligned features. Specifically, our AlignDet achieves a state-of-the-art mAP of 44.1 on the COCO test-dev with ResNeXt-101 backbone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01570](http://arxiv.org/abs/1908.01570)

##### PDF
[http://arxiv.org/pdf/1908.01570](http://arxiv.org/pdf/1908.01570)

