---
layout: post
title: "Automated non-mass enhancing lesion detection and segmentation in breast DCE-MRI"
date: 2018-03-12 11:26:43
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Ignacio Alvarez Illan, Javier Ramirez, Juan M. Gorriz, Katja Pinker, Anke Meyer-Baese
mathjax: true
---

* content
{:toc}

##### Abstract
Non-mass enhancing lesions (NME) constitute a diagnostic challenge in dynamic contrast enhanced magnetic resonance imaging (DCE-MRI) of the breast. Computer Aided Diagnosis (CAD) systems provide physicians with advanced tools for analysis, assessment and evaluation that have a significant impact on the diagnostic performance. Here, we propose a new approach for the specific problem of NME detection and segmentation, by taking advantage of independent component analysis (ICA) to extract a data-driven dynamic characterization of tissue. A set of independent sources was obtained from a dataset of patients, and the dynamic behavior of the different tissues was described by multiple dynamic curves, together with a set of eigenimages describing the scores for each voxel. A new test image is projected onto the independent source space using the unmixing matrix, and each voxel is classified by a support vector machine (SVM) that has already been trained with manually delineated data. A solution to the high false positive rate problem is proposed by controlling the SVM hyperplane location. The CAD system is trained and validated, reaching a DSC coefficient of 0.7215 for NME segmentation.

##### Abstract (translated by Google)
非肿块增强性病变（NME）在乳房的动态对比增强磁共振成像（DCE-MRI）中构成诊断挑战。计算机辅助诊断（CAD）系统为医生提供了先进的分析，评估和评估工具，对诊断性能有重大影响。在这里，我们通过利用独立分量分析（ICA）来提取组织的数据驱动的动态表征，提出了针对NME检测和分割的特定问题的新方法。从患者的数据集中获得一组独立的来源，并且通过多条动态曲线描述不同组织的动态行为，以及描述每个体素的得分的一组本征图像。使用解混矩阵将新测试图像投影到独立源空间上，并且每个体素由已经用手动描绘的数据训练的支持向量机（SVM）分类。通过控制SVM超平面位置来解决高误报率问题。 CAD系统经过训练和验证，NME分割的DSC系数达到0.7215。

##### URL
[https://arxiv.org/abs/1803.04200](https://arxiv.org/abs/1803.04200)

##### PDF
[https://arxiv.org/pdf/1803.04200](https://arxiv.org/pdf/1803.04200)

