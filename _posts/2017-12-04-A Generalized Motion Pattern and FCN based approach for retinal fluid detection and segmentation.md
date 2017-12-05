---
layout: post
title:  'A Generalized Motion Pattern and FCN based approach for retinal fluid detection and segmentation'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Shivin Yadav, Karthik Gopinath, Jayanthi Sivaswamy
---

* content
{:toc}

##### Abstract
SD-OCT is a non-invasive cross-sectional imaging modality used for diagnosis of macular defects. Efficient detection and segmentation of the abnormalities seen as biomarkers in OCT can help in analyzing the progression of the disease and advising effective treatment for the associated disease. In this work, we propose a fully automated Generalized Motion Pattern(GMP) based segmentation method using a cascade of fully convolutional networks for detection and segmentation of retinal fluids from SD-OCT scans. General methods for segmentation depend on domain knowledge-based feature extraction, whereas we propose a method based on Generalized Motion Pattern (GMP) which is derived by inducing motion to an image to suppress the background.The proposed method is parallelizable and handles inter-scanner variability efficiently. Our method achieves a mean Dice score of 0.61,0.70 and 0.73 during segmentation and a mean AUC of 0.85,0.84 and 0.87 during detection for the 3 types of fluids IRF, SRF and PDE respectively.

##### Abstract (translated by Google)
SD-OCT是一种用于诊断黄斑缺损的非侵入性横截面成像模式。在OCT中作为生物标志物的异常的有效检测和分割可以帮助分析疾病的进展并建议对相关疾病的有效治疗。在这项工作中，我们提出了一个完全自动化的广义运动模式（GMP）的分割方法，使用完全卷积网络级联从SD-OCT扫描检测和分割视网膜液。一般的分割方法依赖于基于领域知识的特征提取，而我们提出了一种基于广义运动模式（GMP）的方法，该方法是通过将运动引入图像来抑制背景而得到的。所提出的方法是可并行化的并且处理扫描仪可变性有效。我们的方法在分割期间获得平均Dice评分为0.61,0.70和0.73，并且在分别检测3种类型的流体IRF，SRF和PDE期间的平均AUC为0.85,0.84和0.87。

