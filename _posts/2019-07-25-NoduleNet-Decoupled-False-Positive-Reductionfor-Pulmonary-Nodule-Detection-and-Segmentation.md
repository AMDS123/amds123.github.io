---
layout: post
title: "NoduleNet: Decoupled False Positive Reductionfor Pulmonary Nodule Detection and Segmentation"
date: 2019-07-25 22:05:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Detection
author: Hao Tang, Chupeng Zhang, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Pulmonary nodule detection, false positive reduction and segmentation represent three of the most common tasks in the computeraided analysis of chest CT images. Methods have been proposed for eachtask with deep learning based methods heavily favored recently. However training deep learning models to solve each task separately may be sub-optimal - resource intensive and without the benefit of feature sharing. Here, we propose a new end-to-end 3D deep convolutional neural net (DCNN), called NoduleNet, to solve nodule detection, false positive reduction and nodule segmentation jointly in a multi-task fashion. To avoid friction between different tasks and encourage feature diversification, we incorporate two major design tricks: 1) decoupled feature maps for nodule detection and false positive reduction, and 2) a segmentation refinement subnet for increasing the precision of nodule segmentation. Extensive experiments on the large-scale LIDC dataset demonstrate that the multi-task training is highly beneficial, improving the nodule detection accuracy by 10.27%, compared to the baseline model trained to only solve the nodule detection task. We also carry out systematic ablation studies to highlight contributions from each of the added components. Code is available at https://github.com/uci-cbcl/NoduleNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11320](http://arxiv.org/abs/1907.11320)

##### PDF
[http://arxiv.org/pdf/1907.11320](http://arxiv.org/pdf/1907.11320)

