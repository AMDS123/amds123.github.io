---
layout: post
title: "Deep Learning for End-to-End Automatic Target Recognition from Synthetic Aperture Radar Imagery"
date: 2018-01-25 19:05:38
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Detection Recognition
author: Hidetoshi Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
The standard architecture of synthetic aperture radar (SAR) automatic target recognition (ATR) consists of three stages: detection, discrimination, and classification. In recent years, convolutional neural networks (CNNs) for SAR ATR have been proposed, but most of them classify target classes from a target chip extracted from SAR imagery, as a classification for the third stage of SAR ATR. In this report, we propose a novel CNN for end-to-end ATR from SAR imagery. The CNN named verification support network (VersNet) performs all three stages of SAR ATR end-to-end. VersNet inputs a SAR image of arbitrary sizes with multiple classes and multiple targets, and outputs a SAR ATR image representing the position, class, and pose of each detected target. This report describes the evaluation results of VersNet which trained to output scores of all 12 classes: 10 target classes, a target front class, and a background class, for each pixel using the moving and stationary target acquisition and recognition (MSTAR) public dataset.

##### Abstract (translated by Google)
合成孔径雷达（SAR）自动目标识别（ATR）的标准体系结构由三个阶段组成：检测，鉴别和分类。近年来，SAR ATR的卷积神经网络（CNNs）被提出，但是其中大多数从SAR图像提取的目标芯片中分类目标类别，作为SAR ATR的第三阶段的分类。在这份报告中，我们提出了一个新的CNN端到端ATR从SAR图像。名为验证支持网络（CNNet）的CNN端到端执行SAR ATR的所有三个阶段。 VersNet输入一个任意大小的SAR图像，具有多个类别和多个目标，并输出表示每个检测目标的位置，类别和姿态的SAR ATR图像。这份报告描述了VersNet的评估结果，它使用移动和静止目标获取和识别（MSTAR）公共数据集为每个像素输出所有12个类别的分数：10个目标类别，一个目标前端类别和一个背景类别。

##### URL
[http://arxiv.org/abs/1801.08558](http://arxiv.org/abs/1801.08558)

##### PDF
[http://arxiv.org/pdf/1801.08558](http://arxiv.org/pdf/1801.08558)

