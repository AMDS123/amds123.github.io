---
layout: post
title: "Spatial Aggregation of Holistically-Nested Convolutional Neural Networks for Automated Pancreas Localization and Segmentation"
date: 2017-01-31 20:22:15
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Classification Quantitative
author: Holger R. Roth, Le Lu, Nathan Lay, Adam P. Harrison, Amal Farag, Andrew Sohn, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate and automatic organ segmentation from 3D radiological scans is an important yet challenging problem for medical image analysis. Specifically, the pancreas demonstrates very high inter-patient anatomical variability in both its shape and volume. In this paper, we present an automated system using 3D computed tomography (CT) volumes via a two-stage cascaded approach: pancreas localization and segmentation. For the first step, we localize the pancreas from the entire 3D CT scan, providing a reliable bounding box for the more refined segmentation step. We introduce a fully deep-learning approach, based on an efficient application of holistically-nested convolutional networks (HNNs) on the three orthogonal axial, sagittal, and coronal views. The resulting HNN per-pixel probability maps are then fused using pooling to reliably produce a 3D bounding box of the pancreas that maximizes the recall. We show that our introduced localizer compares favorably to both a conventional non-deep-learning method and a recent hybrid approach based on spatial aggregation of superpixels using random forest classification. The second, segmentation, phase operates within the computed bounding box and integrates semantic mid-level cues of deeply-learned organ interior and boundary maps, obtained by two additional and separate realizations of HNNs. By integrating these two mid-level cues, our method is capable of generating boundary-preserving pixel-wise class label maps that result in the final pancreas segmentation. Quantitative evaluation is performed on a publicly available dataset of 82 patient CT scans using 4-fold cross-validation (CV). We achieve a Dice similarity coefficient (DSC) of 81.27+/-6.27% in validation, which significantly outperforms previous state-of-the art methods that report DSCs of 71.80+/-10.70% and 78.01+/-8.20%, respectively, using the same dataset.

##### Abstract (translated by Google)
从3D放射扫描中精确和自动的器官分割对于医学图像分析来说是一个重要且具有挑战性的问题。具体而言，胰腺在形状和体积上都表现出非常高的患者间解剖变异性。在本文中，我们提出了一个使用三维计算机断层扫描（CT）卷的自动化系统，通过两阶段级联方法：胰腺定位和分割。第一步，我们从整个三维CT扫描本地化胰腺，为更精细的分割步骤提供了一个可靠的边界框。我们在三个正交的轴向，矢状和冠状视图上基于全息嵌套卷积网络（HNN）的有效应用，引入了完全深度学习的方法。然后将所得到的每个像素的HNN概率图使用池融合以可靠地产生胰腺的三维边界框，以最大化召回。我们表明，我们引进的本地化器与传统的非深度学习方法和基于超级像素空间聚合使用随机森林分类的​​最近混合方法相比是有利的。第二，分割阶段在计算的边界框内运行，并且集成深度学习的器官内部和边界图的语义中间线索，通过HNN的两个另外的和单独的实现而获得。通过整合这两个中级线索，我们的方法能够生成边界保留像素级的标签映射，导致最终的胰腺分割。使用4倍交叉验证（CV）对82名患者CT扫描的公开可用数据集进行定量评估。在验证中，我们实现了81.27 +/- 6.27％的骰子相似性系数（DSC），其显着优于先前报导的DSC分别为71.80 +/- 10.70％和78.01 +/- 8.20％的现有技术方法，使用相同的数据集。

##### URL
[https://arxiv.org/abs/1702.00045](https://arxiv.org/abs/1702.00045)

##### PDF
[https://arxiv.org/pdf/1702.00045](https://arxiv.org/pdf/1702.00045)

