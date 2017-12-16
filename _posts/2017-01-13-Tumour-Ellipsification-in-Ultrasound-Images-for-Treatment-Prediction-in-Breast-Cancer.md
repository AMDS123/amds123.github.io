---
layout: post
title: "Tumour Ellipsification in Ultrasound Images for Treatment Prediction in Breast Cancer"
date: 2017-01-13 18:53:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Quantitative
author: Mehrdad J. Gangeh, Hamid R. Tizhoosh, Kan Wu, Dun Huang, Hadi Tadayyon, Gregory J. Czarnota
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in using quantitative ultrasound (QUS) methods have provided a promising framework to non-invasively and inexpensively monitor or predict the effectiveness of therapeutic cancer responses. One of the earliest steps in using QUS methods is contouring a region of interest (ROI) inside the tumour in ultrasound B-mode images. While manual segmentation is a very time-consuming and tedious task for human experts, auto-contouring is also an extremely difficult task for computers due to the poor quality of ultrasound B-mode images. However, for the purpose of cancer response prediction, a rough boundary of the tumour as an ROI is only needed. In this research, a semi-automated tumour localization approach is proposed for ROI estimation in ultrasound B-mode images acquired from patients with locally advanced breast cancer (LABC). The proposed approach comprised several modules, including 1) feature extraction using keypoint descriptors, 2) augmenting the feature descriptors with the distance of the keypoints to the user-input pixel as the centre of the tumour, 3) supervised learning using a support vector machine (SVM) to classify keypoints as "tumour" or "non-tumour", and 4) computation of an ellipse as an outline of the ROI representing the tumour. Experiments with 33 B-mode images from 10 LABC patients yielded promising results with an accuracy of 76.7% based on the Dice coefficient performance measure. The results demonstrated that the proposed method can potentially be used as the first stage in a computer-assisted cancer response prediction system for semi-automated contouring of breast tumours.

##### Abstract (translated by Google)
使用定量超声（QUS）方法的最新进展为非侵入性且廉价地监测或预测治疗性癌症反应的有效性提供了有希望的框架。使用QUS方法的最早步骤之一是在超声B模式图像中对肿瘤内的感兴趣区域（ROI）进行轮廓绘制。虽然手动分割对于人类专家而言是非常耗时和繁琐的任务，但由于超声波B模式图像的质量差，对于计算机而言，自动轮廓绘制也是非常困难的任务。然而，为了预测癌症反应的目的，仅需要肿瘤的粗糙边界作为ROI。在这项研究中，提出了一种半自动的肿瘤定位方法，用于从局部晚期乳腺癌患者（LABC）获取的超声B型图像的ROI估计。所提出的方法包括几个模块，包括1）使用关键点描述符进行特征提取，2）以关键点到作为肿瘤中心的用户输入像素的距离来增强特征描述符，3）使用支持向量机（SVM）将关键点分类为“肿瘤”或“非肿瘤”，以及4）椭圆的计算作为代表肿瘤的ROI的轮廓。基于Dice系数性能测量，来自10个LABC患者的33个B模式图像的实验产生了有希望的结果，具有76.7％的准确度。结果表明，所提出的方法可能被用作计算机辅助癌症反应预测系统中的第一阶段，用于乳腺肿瘤的半自动化轮廓处理。

##### URL
[https://arxiv.org/abs/1701.03779](https://arxiv.org/abs/1701.03779)

##### PDF
[https://arxiv.org/pdf/1701.03779](https://arxiv.org/pdf/1701.03779)

