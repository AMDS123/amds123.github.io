---
layout: post
title: "Real-time image-based instrument classification for laparoscopic surgery"
date: 2018-08-01 06:08:16
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Face Classification Recognition
author: Sebastian Bodenstedt, Antonia Ohnemus, Darko Katic, Anna-Laura Wekerle, Martin Wagner, Hannes Kenngott, Beat Müller-Stich, Rüdiger Dillmann, Stefanie Speidel
mathjax: true
---

* content
{:toc}

##### Abstract
During laparoscopic surgery, context-aware assistance systems aim to alleviate some of the difficulties the surgeon faces. To ensure that the right information is provided at the right time, the current phase of the intervention has to be known. Real-time locating and classification the surgical tools currently in use are key components of both an activity-based phase recognition and assistance generation. In this paper, we present an image-based approach that detects and classifies tools during laparoscopic interventions in real-time. First, potential instrument bounding boxes are detected using a pixel-wise random forest segmentation. Each of these bounding boxes is then classified using a cascade of random forest. For this, multiple features, such as histograms over hue and saturation, gradients and SURF feature, are extracted from each detected bounding box. We evaluated our approach on five different videos from two different types of procedures. We distinguished between the four most common classes of instruments (LigaSure, atraumatic grasper, aspirator, clip applier) and background. Our method succesfully located up to 86% of all instruments respectively. On manually provided bounding boxes, we achieve a instrument type recognition rate of up to 58% and on automatically detected bounding boxes up to 49%. To our knowledge, this is the first approach that allows an image-based classification of surgical tools in a laparoscopic setting in real-time.

##### Abstract (translated by Google)
在腹腔镜手术期间，情境感知辅助系统旨在减轻外科医生面临的一些困难。为确保在适当的时间提供正确的信息，必须了解干预的当前阶段。对当前使用的手术工具进行实时定位和分类是基于活动的阶段识别和辅助生成的关键组成部分。在本文中，我们提出了一种基于图像的方法，可以在腹腔镜介入实时检测和分类工具。首先，使用逐像素随机森林分割来检测潜在的仪器边界框。然后使用级联随机森林对这些边界框中的每一个进行分类。为此，从每个检测到的边界框中提取多个特征，例如色调和饱和度上的直方图，梯度和SURF特征。我们根据两种不同类型的程序对五种不同视频的方法进行了评估。我们区分了四种最常见的器械类型（LigaSure，无创伤抓取器，吸气器，施夹器）和背景。我们的方法成功地分别占所有仪器的86％。在手动提供的边界框上，我们实现了高达58％的仪器类型识别率，并且自动检测到的边界框高达49％。据我们所知，这是第一种允许在腹腔镜设置中实时对手术工具进行基于图像分类的方法。

##### URL
[https://arxiv.org/abs/1808.00178](https://arxiv.org/abs/1808.00178)

##### PDF
[https://arxiv.org/pdf/1808.00178](https://arxiv.org/pdf/1808.00178)

