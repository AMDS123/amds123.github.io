---
layout: post
title: "S-OHEM: Stratified Online Hard Example Mining for Object Detection"
date: 2017-08-15 08:41:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Recognition
author: Minne Li, Zhaoning Zhang, Hao Yu, Xinyuan Chen, Dongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major challenges in object detection is to propose detectors with highly accurate localization of objects. The online sampling of high-loss region proposals (hard examples) uses the multitask loss with equal weight settings across all loss types (e.g, classification and localization, rigid and non-rigid categories) and ignores the influence of different loss distributions throughout the training process, which we find essential to the training efficacy. In this paper, we present the Stratified Online Hard Example Mining (S-OHEM) algorithm for training higher efficiency and accuracy detectors. S-OHEM exploits OHEM with stratified sampling, a widely-adopted sampling technique, to choose the training examples according to this influence during hard example mining, and thus enhance the performance of object detectors. We show through systematic experiments that S-OHEM yields an average precision (AP) improvement of 0.5% on rigid categories of PASCAL VOC 2007 for both the IoU threshold of 0.6 and 0.7. For KITTI 2012, both results of the same metric are 1.6%. Regarding the mean average precision (mAP), a relative increase of 0.3% and 0.5% (1% and 0.5%) is observed for VOC07 (KITTI12) using the same set of IoU threshold. Also, S-OHEM is easy to integrate with existing region-based detectors and is capable of acting with post-recognition level regressors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.02233](https://arxiv.org/abs/1705.02233)

##### PDF
[https://arxiv.org/pdf/1705.02233](https://arxiv.org/pdf/1705.02233)

