---
layout: post
title: "DeepLesion: Automated Deep Mining, Categorization and Detection of Significant Radiology Image Findings using Large-Scale Clinical Lesion Annotations"
date: 2017-10-10 17:49:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Deep_Learning Detection
author: Ke Yan, Xiaosong Wang, Le Lu, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting, harvesting and building large-scale annotated radiological image datasets is a greatly important yet challenging problem. It is also the bottleneck to designing more effective data-hungry computing paradigms (e.g., deep learning) for medical image analysis. Yet, vast amounts of clinical annotations (usually associated with disease image findings and marked using arrows, lines, lesion diameters, segmentation, etc.) have been collected over several decades and stored in hospitals' Picture Archiving and Communication Systems. In this paper, we mine and harvest one major type of clinical annotation data - lesion diameters annotated on bookmarked images - to learn an effective multi-class lesion detector via unsupervised and supervised deep Convolutional Neural Networks (CNN). Our dataset is composed of 33,688 bookmarked radiology images from 10,825 studies of 4,477 unique patients. For every bookmarked image, a bounding box is created to cover the target lesion based on its measured diameters. We categorize the collection of lesions using an unsupervised deep mining scheme to generate clustered pseudo lesion labels. Next, we adopt a regional-CNN method to detect lesions of multiple categories, regardless of missing annotations (normally only one lesion is annotated, despite the presence of multiple co-existing findings). Our integrated mining, categorization and detection framework is validated with promising empirical results, as a scalable, universal or multi-purpose CAD paradigm built upon abundant retrospective medical data. Furthermore, we demonstrate that detection accuracy can be significantly improved by incorporating pseudo lesion labels (e.g., Liver lesion/tumor, Lung nodule/tumor, Abdomen lesions, Chest lymph node and others). This dataset will be made publicly available (under the open science initiative).

##### Abstract (translated by Google)
提取，收集和构建大规模注释的放射影像数据集是一个非常重要而又具有挑战性的问题。这也是设计更有效的数据饥饿计算范例（例如深度学习）用于医学图像分析的瓶颈。然而，数十年来已经收集了大量临床注释（通常与疾病图像发现相关，并且使用箭头，线条，病灶直径，分割等标记）并存储在医院的图像存档和通信系统中。在本文中，我们挖掘和收集一种主要类型的临床注释数据 - 在书签图像上注释的病变直径 - 通过无监督和有监督的深度卷积神经网络（CNN）来学习有效的多级病变检测器。我们的数据集由来自10825个4477名独特患者的研究中的33,688个书签放射图像组成。对于每个加书签的图像，创建一个边界框，以根据其测量的直径覆盖目标病变。我们使用无监督的深度挖掘方案对病变集合进行分类，以生成聚类的伪病灶标签。接下来，我们采用区域CNN方法来检测多个类别的病变，而不管缺失注释（通常只有一个病变被注释，尽管存在多个共同存在的发现）。我们的综合性挖掘，分类和检测框架经过验证，具有良好的实证结果，是一个建立在大量回顾性医学数据基础上的可扩展，通用或多用途的CAD范例。此外，我们证明，通过整合假病变标记（例如，肝脏病变/肿瘤，肺结节/肿瘤，腹部病变，胸部淋巴结等），可以显着提高检测准确度。这个数据集将公开（在公开的科学计划下）。

##### URL
[https://arxiv.org/abs/1710.01766](https://arxiv.org/abs/1710.01766)

##### PDF
[https://arxiv.org/pdf/1710.01766](https://arxiv.org/pdf/1710.01766)

