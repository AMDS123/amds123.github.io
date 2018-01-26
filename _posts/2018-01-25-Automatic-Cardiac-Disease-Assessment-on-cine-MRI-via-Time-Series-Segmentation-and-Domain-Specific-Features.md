---
layout: post
title: "Automatic Cardiac Disease Assessment on cine-MRI via Time-Series Segmentation and Domain Specific Features"
date: 2018-01-25 08:15:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Fabian Isensee, Paul Jaeger, Peter M. Full, Ivo Wolf, Sandy Engelhardt, Klaus H. Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac magnetic resonance imaging improves on diagnosis of cardiovascular diseases by providing images at high spatiotemporal resolution. Manual evaluation of these time-series, however, is expensive and prone to biased and non-reproducible outcomes. In this paper, we present a method that addresses named limitations by integrating segmentation and disease classification into a fully automatic processing pipeline. We use an ensemble of UNet inspired architectures for segmentation of cardiac structures such as the left and right ventricular cavity (LVC, RVC) and the left ventricular myocardium (LVM) on each time instance of the cardiac cycle. For the classification task, information is extracted from the segmented time-series in form of comprehensive features handcrafted to reflect diagnostic clinical procedures. Based on these features we train an ensemble of heavily regularized multilayer perceptrons (MLP) and a random forest classifier to predict the pathologic target class. We evaluated our method on the ACDC dataset (4 pathology groups, 1 healthy group) and achieve dice scores of 0.945 (LVC), 0.908 (RVC) and 0.905 (LVM) in a cross-validation over the training set (100 cases) and 0.950 (LVC), 0.923 (RVC) and 0.911 (LVM) on the test set (50 cases). We report a classification accuracy of 94% on a training set cross-validation and 92% on the test set. Our results underpin the potential of machine learning methods for accurate, fast and reproducible segmentation and computer-assisted diagnosis (CAD).

##### Abstract (translated by Google)
心脏磁共振成像通过以高时空分辨率提供图像来改善心血管疾病的诊断。然而，手动评估这些时间序列是昂贵的，并且容易产生偏差和不可重复的结果。在本文中，我们提出了一种方法，通过将分割和疾病分类整合到全自动处理流程中来解决命名限制。我们使用UNet灵感体系结构来分割心脏周期的每个时间点的心脏结构，例如左心室腔和右心室腔（LVC，RVC）和左心室心肌（LVM）。对于分类任务，信息从分段的时间序列中提取，以手工反映临床诊断程序的综合特征的形式提取。基于这些特征，我们训练一套严格正则化的多层感知器（MLP）和一个随机森林分类器来预测病理目标类别。我们在ACDC数据集（4个病理组，1个健康组）上评估了我们的方法，并且在训练组（100例）交叉验证中获得了0.945（LVC），0.908（RVC）和0.905（LVM）在测试集（50例）中为0.950（LVC），0.923（RVC）和0.911（LVM）。我们报告的训练集交叉验证的分类准确率为94％，测试集的分类准确率为92％。我们的研究结果支持了机器学习方法的准确，快速和可重复性分割和计算机辅助诊断（CAD）的潜力。

##### URL
[http://arxiv.org/abs/1707.00587](http://arxiv.org/abs/1707.00587)

##### PDF
[http://arxiv.org/pdf/1707.00587](http://arxiv.org/pdf/1707.00587)

