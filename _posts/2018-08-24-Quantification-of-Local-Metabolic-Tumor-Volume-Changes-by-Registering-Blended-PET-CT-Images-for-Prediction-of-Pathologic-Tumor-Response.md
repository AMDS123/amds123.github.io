---
layout: post
title: "Quantification of Local Metabolic Tumor Volume Changes by Registering Blended PET-CT Images for Prediction of Pathologic Tumor Response"
date: 2018-08-24 21:17:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Relation
author: Sadegh Riyahi, Wookjin Choi, Chia-Ju Liu, Saad Nadeem, Shan Tan, Hualiang Zhong, Wengen Chen, Abraham J. Wu, James G. Mechalakos, Joseph O. Deasy, Wei Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Quantification of local metabolic tumor volume (MTV) chan-ges after Chemo-radiotherapy would allow accurate tumor response evaluation. Currently, local MTV changes in esophageal (soft-tissue) cancer are measured by registering follow-up PET to baseline PET using the same transformation obtained by deformable registration of follow-up CT to baseline CT. Such approach is suboptimal because PET and CT capture fundamentally different properties (metabolic vs. anatomy) of a tumor. In this work we combined PET and CT images into a single blended PET-CT image and registered follow-up blended PET-CT image to baseline blended PET-CT image. B-spline regularized diffeomorphic registration was used to characterize the large MTV shrinkage. Jacobian of the resulting transformation was computed to measure the local MTV changes. Radiomic features (intensity and texture) were then extracted from the Jacobian map to predict pathologic tumor response. Local MTV changes calculated using blended PET-CT registration achieved the highest correlation with ground truth segmentation (R=0.88) compared to PET-PET (R=0.80) and CT-CT (R=0.67) registrations. Moreover, using blended PET-CT registration, the multivariate prediction model achieved the highest accuracy with only one Jacobian co-occurrence texture feature (accuracy=82.3%). This novel framework can replace the conventional approach that applies CT-CT transformation to the PET data for longitudinal evaluation of tumor response.

##### Abstract (translated by Google)
化学放疗后局部代谢肿瘤体积（MTV）变化的量化将允许准确的肿瘤反应评估。目前，食管（软组织）癌症的局部MTV变化通过使用通过随后CT的可变形登记到基线CT获得的相同变换将随访PET登记到基线PET来测量。这种方法不是最理想的，因为PET和CT从根本上捕获肿瘤的不同特性（代谢与解剖学）。在这项工作中，我们将PET和CT图像组合成单个混合PET-CT图像，并将随后混合的PET-CT图像记录到基线混合PET-CT图像。 B样条正则化微分同位素配准用于表征大的MTV收缩。计算得到的变换的雅可比行列式以测量局部MTV变化。然后从雅可比图中提取放射学特征（强度和纹理）以预测病理性肿瘤反应。与PET-PET（R = 0.80）和CT-CT（R = 0.67）配准相比，使用混合PET-CT配准计算的局部MTV变化与地面实况分割（R = 0.88）具有最高相关性。此外，使用混合PET-CT配准，多变量预测模型仅具有一个雅可比共现纹理特征（准确度= 82.3％），实现了最高精度。这种新颖的框架可以取代将CT-CT转换应用于PET数据的传统方法，用于纵向评估肿瘤反应。

##### URL
[http://arxiv.org/abs/1808.08312](http://arxiv.org/abs/1808.08312)

##### PDF
[http://arxiv.org/pdf/1808.08312](http://arxiv.org/pdf/1808.08312)

