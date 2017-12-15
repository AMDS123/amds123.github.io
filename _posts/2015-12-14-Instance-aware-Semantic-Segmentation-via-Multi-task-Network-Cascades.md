---
layout: post
title: "Instance-aware Semantic Segmentation via Multi-task Network Cascades"
date: 2015-12-14 17:17:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Jifeng Dai, Kaiming He, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation research has recently witnessed rapid progress, but many leading methods are unable to identify object instances. In this paper, we present Multi-task Network Cascades for instance-aware semantic segmentation. Our model consists of three networks, respectively differentiating instances, estimating masks, and categorizing objects. These networks form a cascaded structure, and are designed to share their convolutional features. We develop an algorithm for the nontrivial end-to-end training of this causal, cascaded structure. Our solution is a clean, single-step training framework and can be generalized to cascades that have more stages. We demonstrate state-of-the-art instance-aware semantic segmentation accuracy on PASCAL VOC. Meanwhile, our method takes only 360ms testing an image using VGG-16, which is two orders of magnitude faster than previous systems for this challenging problem. As a by product, our method also achieves compelling object detection results which surpass the competitive Fast/Faster R-CNN systems. The method described in this paper is the foundation of our submissions to the MS COCO 2015 segmentation competition, where we won the 1st place.

##### Abstract (translated by Google)
语义分割研究近来有了飞速的发展，但许多领先的方法无法识别对象实例。在本文中，我们提出了多任务网络Cascades实例感知语义分割。我们的模型由三个网络组成，分别区分实例，估计掩码和对象分类。这些网络形成一个级联结构，旨在共享其卷积特征。我们为这种因果级联结构的非平凡端到端训练开发了一种算法。我们的解决方案是一个干净的一步式培训框架，可以推广到更多阶段的级联。我们在PASCAL VOC上展示了最先进的实例感知语义分割准确性。同时，我们的方法只需要360ms的测试图像使用VGG-16，这是比以前的系统快两个数量级这个具有挑战性的问题。作为副产品，我们的方法也实现了超越竞争的快速/更快的R-CNN系统的引人注目的目标检测结果。本文所述的方法是我们提交给MS COCO 2015分段比赛的基础，我们在这里赢得了第一名。

##### URL
[https://arxiv.org/abs/1512.04412](https://arxiv.org/abs/1512.04412)

##### PDF
[https://arxiv.org/pdf/1512.04412](https://arxiv.org/pdf/1512.04412)

