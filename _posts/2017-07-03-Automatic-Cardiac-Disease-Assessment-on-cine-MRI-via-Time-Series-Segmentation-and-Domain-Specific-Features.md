---
layout: post
title: "Automatic Cardiac Disease Assessment on cine-MRI via Time-Series Segmentation and Domain Specific Features"
date: 2017-07-03 15:10:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Fabian Isensee, Paul Jaeger, Peter M. Full, Ivo Wolf, Sandy Engelhardt, Klaus H. Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac magnetic resonance imaging improves on diagnosis of cardiovascular diseases by providing images at high spatiotemporal resolution. Manual evaluation of these time-series, however, is expensive and prone to biased and non-reproducible outcomes. In this paper, we present a method that addresses named limitations by integrating seg- mentation and disease classification into a fully automatic processing pipeline. We use a UNet inspired architecture for segmentation of car- diac structures such as the left and right ventricular cavity (LVC, RVC) and the left ventricular myocardium (LVM) on each time instance of the cardiac cycle. For the classification task, information is extracted from the segmented time-series in form of comprehensive features handcrafted to reflect diagnostic clinical procedures. Based on these features we train an ensemble of heavily regularized multilayer perceptrons (MLP) and a random forest classifier to predict the pathologic target class. We evalu- ated our method on the ACDC training dataset (4 pathology groups, 1 healthy group, 20 patients per group). We achieved dice scores of 0.930 (LVC), 0.879 (RVC) and 0.873 (LVM) and a classification accuracy of 94% in a 5-fold cross-validation. Our results underpin the potential of machine learning methods for accurate, fast and reproducible segmenta- tion and computer-assisted diagnosis (CAD).

##### Abstract (translated by Google)
心脏磁共振成像通过以高时空分辨率提供图像来改善心血管疾病的诊断。然而，手动评估这些时间序列是昂贵的，并且容易产生偏差和不可重复的结果。在本文中，我们提出了一种方法，通过将分割和疾病分类整合到全自动处理流程中来解决命名限制。我们使用UNet灵感结构来分割心脏周期的每个时刻的心脏结构，例如左心室腔和右心室腔（LVC，RVC）和左心室心肌（LVM）。对于分类任务，信息从分段的时间序列中提取，以手工反映诊断临床程序的综合特征的形式提取。基于这些特征，我们训练一套严格正则化的多层感知器（MLP）和一个随机森林分类器来预测病理目标类别。我们评估ACDC训练数据集（4个病理组，1个健康组，每组20个病人）的方法。在5倍交叉验证中，我们实现了0.930（LVC），0.879（RVC）和0.873（LVM）的骰子评分和94％的分类准确性。我们的研究结果支持了机器学习方法的准确，快速和可重复性的分割和计算机辅助诊断（CAD）的潜力。

##### URL
[https://arxiv.org/abs/1707.00587](https://arxiv.org/abs/1707.00587)

##### PDF
[https://arxiv.org/pdf/1707.00587](https://arxiv.org/pdf/1707.00587)

