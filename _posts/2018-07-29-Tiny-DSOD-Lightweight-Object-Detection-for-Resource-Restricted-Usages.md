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
Object detection has made great progress in the past few years along with the development of deep learning. However, most current object detection methods are resource hungry, which hinders their wide deployment to many resource restricted usages such as usages on always-on devices, battery-powered low-end devices, etc. This paper considers the resource and accuracy trade-off for resource-restricted usages during designing the whole object detection framework. Based on the deeply supervised object detection (DSOD) framework, we propose Tiny-DSOD dedicating to resource-restricted usages. Tiny-DSOD introduces two innovative and ultra-efficient architecture blocks: depthwise dense block (DDB) based backbone and depthwise feature-pyramid-network (D-FPN) based front-end. We conduct extensive experiments on three famous benchmarks (PASCAL VOC 2007, KITTI, and COCO), and compare Tiny-DSOD to the state-of-the-art ultra-efficient object detection solutions such as Tiny-YOLO, MobileNet-SSD (v1 &amp; v2), SqueezeDet, Pelee, etc. Results show that Tiny-DSOD outperforms these solutions in all the three metrics (parameter-size, FLOPs, accuracy) in each comparison. For instance, Tiny-DSOD achieves 72.1% mAP with only 0.95M parameters and 1.06B FLOPs, which is by far the state-of-the-arts result with such a low resource requirement.

##### Abstract (translated by Google)
随着深度学习的发展，物体检测在过去几年取得了很大进展。然而，大多数当前的对象检测方法都是资源匮乏的，这妨碍了它们广泛部署到许多资源受限的用途，例如常用设备，电池供电的低端设备等的使用。本文考虑资源和准确性的权衡在设计整个对象检测框架期间用于资源限制的用法。基于深度监督对象检测（DSOD）框架，我们提出了Tiny-DSOD专用于资源受限的用法。 Tiny-DSOD引入了两个创新和超高效的架构模块：基于深度密集块（DDB）的主干和基于深度特征 - 金字塔网络（D-FPN）的前端。我们在三个着名的基准测试（PASCAL VOC 2007，KITTI和COCO）上进行了大量实验，并将Tiny-DSOD与最先进的超高效物体检测解决方案（如Tiny-YOLO，MobileNet-SSD（v1）进行了比较＆amp; v2），SqueezeDet，Pelee等。结果表明，Tiny-DSOD在每次比较的所有三个指标（参数大小，FLOP，准确度）中都优于这些解决方案。例如，Tiny-DSOD实现了72.1％的mAP，只有0.95M参数和1.06B FLOP，这是迄今为止具有如此低资源要求的最新结果。

##### URL
[http://arxiv.org/abs/1807.11013](http://arxiv.org/abs/1807.11013)

##### PDF
[http://arxiv.org/pdf/1807.11013](http://arxiv.org/pdf/1807.11013)

