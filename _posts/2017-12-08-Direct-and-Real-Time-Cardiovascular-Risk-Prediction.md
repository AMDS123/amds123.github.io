---
layout: post
title: "Direct and Real-Time Cardiovascular Risk Prediction"
date: 2017-12-08 08:53:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Bob D. de Vos, Nikolas Lessmann, Pim A. de Jong, Max A. Viergever, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
Coronary artery calcium (CAC) burden quantified in low-dose chest CT is a predictor of cardiovascular events. We propose an automatic method for CAC quantification, circumventing intermediate segmentation of CAC. The method determines a bounding box around the heart using a ConvNet for localization. Subsequently, a dedicated ConvNet analyzes axial slices within the bounding boxes to determine CAC quantity by regression. A dataset of 1,546 baseline CT scans was used from the National Lung Screening Trial with manually identified CAC. The method achieved an ICC of 0.98 between manual reference and automatically obtained Agatston scores. Stratification of subjects into five cardiovascular risk categories resulted in an accuracy of 85\% and Cohen's linearly weighted $\kappa$ of 0.90. The results demonstrate that real-time quantification of CAC burden in chest CT without the need for segmentation of CAC is possible.

##### Abstract (translated by Google)
低剂量胸部CT定量冠状动脉钙（CAC）负荷是心血管事件的预测指标。我们提出一种自动CAC量化方法，规避CAC的中间分割。该方法使用ConvNet来定位心脏周围的边界框。随后，专用ConvNet分析边界框内的轴向切片以通过回归来确定CAC数量。使用来自全国肺部筛查试验的1,546基线CT扫描的数据集与手动识别的CAC。该方法在手工参考和自动获得的Agatston评分之间达到了0.98的ICC。将受试者分成5个心血管风险类别，结果精确度为85％，Cohen线性加权$κappa$为0.90。结果表明，实时量化胸部CT中的CAC负担而不需要CAC的分割是可能的。

##### URL
[http://arxiv.org/abs/1712.02982](http://arxiv.org/abs/1712.02982)

##### PDF
[http://arxiv.org/pdf/1712.02982](http://arxiv.org/pdf/1712.02982)

