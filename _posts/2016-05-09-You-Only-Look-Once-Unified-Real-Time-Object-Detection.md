---
layout: post
title: "You Only Look Once: Unified, Real-Time Object Detection"
date: 2016-05-09 22:22:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Joseph Redmon, Santosh Divvala, Ross Girshick, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
We present YOLO, a new approach to object detection. Prior work on object detection repurposes classifiers to perform detection. Instead, we frame object detection as a regression problem to spatially separated bounding boxes and associated class probabilities. A single neural network predicts bounding boxes and class probabilities directly from full images in one evaluation. Since the whole detection pipeline is a single network, it can be optimized end-to-end directly on detection performance. Our unified architecture is extremely fast. Our base YOLO model processes images in real-time at 45 frames per second. A smaller version of the network, Fast YOLO, processes an astounding 155 frames per second while still achieving double the mAP of other real-time detectors. Compared to state-of-the-art detection systems, YOLO makes more localization errors but is far less likely to predict false detections where nothing exists. Finally, YOLO learns very general representations of objects. It outperforms all other detection methods, including DPM and R-CNN, by a wide margin when generalizing from natural images to artwork on both the Picasso Dataset and the People-Art Dataset.

##### Abstract (translated by Google)
我们介绍YOLO，一种新的对象检测方法。以前的对象检测工作重新设置分类器来执行检测。相反，我们将对象检测框架作为回归问题框架空间分隔框和相关的类概率。单个神经网络在一次评估中直接从完整图像预测边界框和类概率。由于整个检测流水线是单一网络，因此可以直接对检测性能进行端到端的优化。我们的统一架构非常快。我们的基础YOLO模型以45帧/秒的速度实时处理图像。网络的一个较小的版本，快速YOLO，处理惊人的155帧每秒，同时仍然实现双倍的其他实时探测器的mAP。与最先进的检测系统相比，YOLO产生更多的定位误差，但是在没有任何东西存在的情况下，预测错误检测的可能性要小得多。最后，YOLO学习对象的非常一般的表示。在从毕加索数据集和人民艺术数据库中的自然图像到艺术作品的概括中，它大大超越了DPM和R-CNN等所有其他检测方法。

##### URL
[https://arxiv.org/abs/1506.02640](https://arxiv.org/abs/1506.02640)

