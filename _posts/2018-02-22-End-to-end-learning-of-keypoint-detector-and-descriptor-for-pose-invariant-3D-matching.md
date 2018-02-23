---
layout: post
title: "End-to-end learning of keypoint detector and descriptor for pose invariant 3D matching"
date: 2018-02-22 01:58:43
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Detection
author: Georgios Georgakis, Srikrishna Karanam, Ziyan Wu, Jan Ernst, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
Finding correspondences between images or 3D scans is at the heart of many computer vision and image retrieval applications and is often enabled by matching local keypoint descriptors. Various learning approaches have been applied in the past to different stages of the matching pipeline, considering detector, descriptor, or metric learning objectives. These objectives were typically addressed separately and most previous work has focused on image data. This paper proposes an end-to-end learning framework for keypoint detection and its representation (descriptor) for 3D depth maps or 3D scans, where the two can be jointly optimized towards task-specific objectives without a need for separate annotations. We employ a Siamese architecture augmented by a sampling layer and a novel score loss function which in turn affects the selection of region proposals. The positive and negative examples are obtained automatically by sampling corresponding region proposals based on their consistency with known 3D pose labels. Matching experiments with depth data on multiple benchmark datasets demonstrate the efficacy of the proposed approach, showing significant improvements over state-of-the-art methods.

##### Abstract (translated by Google)
查找图像或3D扫描之间的对应关系是许多计算机视觉和图像检索应用的核心，并且通常通过匹配本地关键点描述符来启用。考虑到检测器，描述符或度量学习目标，过去已将各种学习方法应用于匹配流水线的不同阶段。这些目标通常是分开处理的，大部分以前的工作都集中在图像数据上。本文提出了关键点检测的端到端学习框架及其3D深度图或3D扫描的表示（描述符），其中两者可以针对任务特定目标进行联合优化，而不需要单独的注释。我们采用了一种由抽样层和一种新颖的分数损失函数增强的连体建筑，这又反过来影响了区域建议的选择。通过根据与已知3D姿态标签的一致性对相应区域提议进行抽样，自动获得正面和负面示例。与多个基准数据集上的深度数据进行匹配实验证明了所提出的方法的有效性，显示出相对于最先进方法的显着改进。

##### URL
[http://arxiv.org/abs/1802.07869](http://arxiv.org/abs/1802.07869)

##### PDF
[http://arxiv.org/pdf/1802.07869](http://arxiv.org/pdf/1802.07869)

