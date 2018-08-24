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
在本文中，我们通过建立深度神经网络和传统检测模式之间的桥梁，提出了一种名为“Deep Regionlets”的新型目标检测框架，用于精确的通用对象检测。受区域小组建模对象变形和多纵横比的能力的启发，我们将区域小组纳入端到端可训练的深度学习框架。深度regionlets框架由区域选择网络和深度regionlet学习模块组成。具体地，给定检测边界框提议，区域选择网络提供关于从何处选择区域以从中学习特征的指导。 regionlet学习模块侧重于局部特征选择和转换，以减轻局部变化。为此，我们首先在检测框架内实现非矩形区域选择以适应对象外观的变化。此外，我们在regionlet倾斜模块中设计了一个“门控网络”，以实现软区域选择和池化。 Deep Regionlets框架是端到端的培训，无需额外的努力。我们进行消融研究并对PASCAL VOC和Microsoft COCO数据集进行大量实验。即使没有额外的分段标签，所提出的框架也优于RetinaNet和Mask R-CNN等最先进的算法。

##### URL
[http://arxiv.org/abs/1712.02408](http://arxiv.org/abs/1712.02408)

##### PDF
[http://arxiv.org/pdf/1712.02408](http://arxiv.org/pdf/1712.02408)

