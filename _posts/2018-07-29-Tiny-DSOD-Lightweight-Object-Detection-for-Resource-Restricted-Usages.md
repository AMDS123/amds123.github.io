---
layout: post
title: "Tiny-DSOD: Lightweight Object Detection for Resource-Restricted Usages"
date: 2018-07-29 06:58:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Yuxi Li, Jiuwei Li, Weiyao Lin, Jianguo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection has made great progress in the past few years along with the development of deep learning. However, most current object detection methods are resource hungry, which hinders their wide deployment to many resource restricted usages such as usages on always-on devices, battery-powered low-end devices, etc. This paper considers the resource and accuracy trade-off for resource-restricted usages during designing the whole object detection framework. Based on the deeply supervised object detection (DSOD) framework, we propose Tiny-DSOD dedicating to resource-restricted usages. Tiny-DSOD introduces two innovative and ultra-efficient architecture blocks: depthwise dense block (DDB) based backbone and depthwise feature-pyramid-network (D-FPN) based front-end. We conduct extensive experiments on three famous benchmarks (PASCAL VOC 2007, KITTI, and COCO), and compare Tiny-DSOD to the state-of-the-art ultra-efficient object detection solutions such as Tiny-YOLO, MobileNet-SSD (v1 & v2), SqueezeDet, Pelee, etc. Results show that Tiny-DSOD outperforms these solutions in all the three metrics (parameter-size, FLOPs, accuracy) in each comparison. For instance, Tiny-DSOD achieves 72.1% mAP with only 0.95M parameters and 1.06B FLOPs, which is by far the state-of-the-arts result with such a low resource requirement.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.11013](https://arxiv.org/abs/1807.11013)

##### PDF
[https://arxiv.org/pdf/1807.11013](https://arxiv.org/pdf/1807.11013)

