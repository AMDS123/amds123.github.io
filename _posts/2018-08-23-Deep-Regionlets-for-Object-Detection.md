---
layout: post
title: "Deep Regionlets for Object Detection"
date: 2018-08-23 01:35:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Deep_Learning Detection
author: Hongyu Xu, Xutao Lv, Xiaoyu Wang, Zhou Ren, Navaneeth Bodla, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel object detection framework named "Deep Regionlets" by establishing a bridge between deep neural networks and conventional detection schema for accurate generic object detection. Motivated by the abilities of regionlets for modeling object deformation and multiple aspect ratios, we incorporate regionlets into an end-to-end trainable deep learning framework. The deep regionlets framework consists of a region selection network and a deep regionlet learning module. Specifically, given a detection bounding box proposal, the region selection network provides guidance on where to select regions to learn the features from. The regionlet learning module focuses on local feature selection and transformation to alleviate local variations. To this end, we first realize non-rectangular region selection within the detection framework to accommodate variations in object appearance. Moreover, we design a "gating network" within the regionlet leaning module to enable soft regionlet selection and pooling. The Deep Regionlets framework is trained end-to-end without additional efforts. We perform ablation studies and conduct extensive experiments on the PASCAL VOC and Microsoft COCO datasets. The proposed framework outperforms state-of-the-art algorithms, such as RetinaNet and Mask R-CNN, even without additional segmentation labels.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.02408](https://arxiv.org/abs/1712.02408)

##### PDF
[https://arxiv.org/pdf/1712.02408](https://arxiv.org/pdf/1712.02408)

