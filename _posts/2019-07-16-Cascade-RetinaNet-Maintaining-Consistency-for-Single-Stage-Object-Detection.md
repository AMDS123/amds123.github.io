---
layout: post
title: "Cascade RetinaNet: Maintaining Consistency for Single-Stage Object Detection"
date: 2019-07-16 08:01:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Relation
author: Hongkai Zhang, Hong Chang, Bingpeng Ma, Shiguang Shan, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent researches attempt to improve the detection performance by adopting the idea of cascade for single-stage detectors. In this paper, we analyze and discover that inconsistency is the major factor limiting the performance. The refined anchors are associated with the feature extracted from the previous location and the classifier is confused by misaligned classification and localization. Further, we point out two main designing rules for the cascade manner: improving consistency between classification confidence and localization performance, and maintaining feature consistency between different stages. A multistage object detector named Cas-RetinaNet, is then proposed for reducing the misalignments. It consists of sequential stages trained with increasing IoU thresholds for improving the correlation, and a novel Feature Consistency Module for mitigating the feature inconsistency. Experiments show that our proposed Cas-RetinaNet achieves stable performance gains across different models and input scales. Specifically, our method improves RetinaNet from 39.1 AP to 41.1 AP on the challenging MS COCO dataset without any bells or whistles.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06881](http://arxiv.org/abs/1907.06881)

##### PDF
[http://arxiv.org/pdf/1907.06881](http://arxiv.org/pdf/1907.06881)

