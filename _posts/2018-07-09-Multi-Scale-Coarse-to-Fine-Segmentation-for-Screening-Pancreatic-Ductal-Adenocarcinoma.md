---
layout: post
title: "Multi-Scale Coarse-to-Fine Segmentation for Screening Pancreatic Ductal Adenocarcinoma"
date: 2018-07-09 05:01:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Zhuotun Zhu, Yingda Xia, Lingxi Xie, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an intuitive approach to finding pancreatic ductal adenocarcinoma (PDAC), the most common type of pancreatic cancer, by checking abdominal CT scans. Our idea is named segmentation-for-classification (S4C), which classifies a volume by checking if at least a sufficient number of voxels is segmented as the tumor. In order to deal with tumors with different scales, we train volumetric segmentation networks with multi-scale inputs, and test them in a coarse-to-fine flowchart. A post-processing module is used to filter out outliers and reduce false alarms. We perform a case study on our dataset containing 439 CT scans, in which 136 cases were diagnosed with PDAC and 303 cases are normal. Our approach reports a sensitivity of 94.1% at a specificity of 98.5%, with an average tumor segmentation accuracy of 56.46% over all PDAC cases.

##### Abstract (translated by Google)
本文提出了一种直观的方法，通过检查腹部CT扫描来发现胰腺导管腺癌（PDAC），这是最常见的胰腺癌类型。我们的想法被命名为分类分割（S4C），其通过检查是否至少足够数量的体素被分割为肿瘤来对体积进行分类。为了处理不同尺度的肿瘤，我们使用多尺度输入训练体积分割网络，并在粗略到精细的流程图中进行测试。后处理模块用于过滤异常值并减少误报。我们对包含439例CT扫描的数据集进行了案例研究，其中136例诊断为PDAC，303例正常。我们的方法报告敏感性为94.1％，特异性为98.5％，平均肿瘤分割准确率为56.46％，超过所有PDAC病例。

##### URL
[http://arxiv.org/abs/1807.02941](http://arxiv.org/abs/1807.02941)

##### PDF
[http://arxiv.org/pdf/1807.02941](http://arxiv.org/pdf/1807.02941)

