---
layout: post
title: "Accurate Esophageal Gross Tumor Volume Segmentation in PET/CT using Two-Stream Chained 3D Deep Network Fusion"
date: 2019-09-04 02:24:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Dakai Jin, Dazhou Guo, Tsung-Ying Ho, Adam P. Harrison, Jing Xiao, Chen-kan Tseng, Le Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Gross tumor volume (GTV) segmentation is a critical step in esophageal cancer radiotherapy treatment planning. Inconsistencies across oncologists and prohibitive labor costs motivate automated approaches for this task. However, leading approaches are only applied to radiotherapy computed tomography (RTCT) images taken prior to treatment. This limits the performance as RTCT suffers from low contrast between the esophagus, tumor, and surrounding tissues. In this paper, we aim to exploit both RTCT and positron emission tomography (PET) imaging modalities to facilitate more accurate GTV segmentation. By utilizing PET, we emulate medical professionals who frequently delineate GTV boundaries through observation of the RTCT images obtained after prescribing radiotherapy and PET/CT images acquired earlier for cancer staging. To take advantage of both modalities, we present a two-stream chained segmentation approach that effectively fuses the CT and PET modalities via early and late 3D deep-network-based fusion. Furthermore, to effect the fusion and segmentation we propose a simple yet effective progressive semantically nested network (PSNN) model that outperforms more complicated models. Extensive 5-fold cross-validation on 110 esophageal cancer patients, the largest analysis to date, demonstrates that both the proposed two-stream chained segmentation pipeline and the PSNN model can significantly improve the quantitative performance over the previous state-of-the-art work by 11% in absolute Dice score (DSC) (from 0.654 to 0.764) and, at the same time, reducing the Hausdorff distance from 129 mm to 47 mm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01524](http://arxiv.org/abs/1909.01524)

##### PDF
[http://arxiv.org/pdf/1909.01524](http://arxiv.org/pdf/1909.01524)

