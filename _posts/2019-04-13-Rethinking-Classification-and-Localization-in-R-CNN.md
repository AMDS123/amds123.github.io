---
layout: post
title: "Rethinking Classification and Localization in R-CNN"
date: 2019-04-13 06:41:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Relation
author: Yue Wu, Yinpeng Chen, Lu Yuan, Zicheng Liu, Lijuan Wang, Hongzhi Li, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Modern R-CNN based detectors share the RoI feature extractor head for both classification and localization tasks, based upon the correlation between the two tasks. In contrast, we found that different head structures (i.e. fully connected head and convolution head) have opposite preferences towards these two tasks. Specifically, the fully connected head is more suitable for the classification task, while the convolution head is more suitable for the localization task. 
 Therefore, we propose a double-head method to separate these two tasks into different heads (i.e. a fully connected head for classification and a convolution head for box regression). Without bells and whistles, our method gains +3.4 and +2.7 points mAP on MS COCO dataset from Feature Pyramid Network baselines with ResNet-50 and ResNet-101 backbones, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06493](http://arxiv.org/abs/1904.06493)

##### PDF
[http://arxiv.org/pdf/1904.06493](http://arxiv.org/pdf/1904.06493)

