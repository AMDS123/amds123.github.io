---
layout: post
title: "Optimizing Region Selection for Weakly Supervised Object Detection"
date: 2017-08-05 07:24:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection Gradient_Descent
author: Wenhui Jiang, Thuyen Ngo, B. S. Manjunath, Zhicheng Zhao, Fei Su
mathjax: true
---

* content
{:toc}

##### Abstract
Training object detectors with only image-level annotations is very challenging because the target objects are often surrounded by a large number of background clutters. Many existing approaches tackle this problem through object proposal mining. However, the collected positive regions are either low in precision or lack of diversity, and the strategy of collecting negative regions is not carefully designed, neither. Moreover, training is often slow because region selection and object detector training are processed separately. In this context, the primary contribution of this work is to improve weakly supervised detection with an optimized region selection strategy. The proposed method collects purified positive training regions by progressively removing easy background clutters, and selects discriminative negative regions by mining class-specific hard samples. This region selection procedure is further integrated into a CNN-based weakly supervised detection (WSD) framework, and can be performed in each stochastic gradient descent mini-batch during training. Therefore, the entire model can be trained end-to-end efficiently. Extensive evaluation results on PASCAL VOC 2007, VOC 2010 and VOC 2012 datasets are presented which demonstrate that the proposed method effectively improves WSD.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.01723](https://arxiv.org/abs/1708.01723)

##### PDF
[https://arxiv.org/pdf/1708.01723](https://arxiv.org/pdf/1708.01723)

