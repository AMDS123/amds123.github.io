---
layout: post
title: "Double-Head RCNN: Rethinking Classification and Localization for Object Detection"
date: 2019-05-31 16:04:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Classification Detection
author: Yue Wu, Yinpeng Chen, Lu Yuan, Zicheng Liu, Lijuan Wang, Hongzhi Li, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Modern R-CNN based detectors apply a head to extract Region of Interest (RoI) features for both classification and localization tasks. In contrast, we found that these two tasks have opposite preferences towards two widely used head structures (i.e. fully connected head and convolution head). Specifically, the fully connected head is more suitable for the classification task, while the convolution head is more suitable for the localization task. Therefore, we propose a Double-Head method, which has a fully connected head focusing on classification and a convolution head to pay more attention to bounding box regression. In addition, we have two findings for the unfocused tasks (i.e. classification in the convolution head, and bounding box regression in the fully connected head): (a) adding classification to the convolution head is complementary to the classification in the fully connected head, and (b) bounding box regression provides auxiliary supervision for the fully connected head. Without bells and whistles, our method gains +3.5 and +2.8 AP on MS COCO dataset from Feature Pyramid Network (FPN) baselines with ResNet-50 and ResNet-101 backbones, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06493](http://arxiv.org/abs/1904.06493)

##### PDF
[http://arxiv.org/pdf/1904.06493](http://arxiv.org/pdf/1904.06493)

