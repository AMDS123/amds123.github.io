---
layout: post
title: "Fully Automatic Myocardial Segmentation of Contrast Echocardiography Sequence Using Random Forests Guided by Shape Model"
date: 2018-06-19 23:18:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection Relation
author: Yuanwei Li, Chin Pang Ho, Matthieu Toulemonde, Navtej Chahal, Roxy Senior, Meng-Xing Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Myocardial contrast echocardiography (MCE) is an imaging technique that assesses left ventricle function and myocardial perfusion for the detection of coronary artery diseases. Automatic MCE perfusion quantification is challenging and requires accurate segmentation of the myocardium from noisy and time-varying images. Random forests (RF) have been successfully applied to many medical image segmentation tasks. However, the pixel-wise RF classifier ignores contextual relationships between label outputs of individual pixels. RF which only utilizes local appearance features is also susceptible to data suffering from large intensity variations. In this paper, we demonstrate how to overcome the above limitations of classic RF by presenting a fully automatic segmentation pipeline for myocardial segmentation in full-cycle 2D MCE data. Specifically, a statistical shape model is used to provide shape prior information that guide the RF segmentation in two ways. First, a novel shape model (SM) feature is incorporated into the RF framework to generate a more accurate RF probability map. Second, the shape model is fitted to the RF probability map to refine and constrain the final segmentation to plausible myocardial shapes. We further improve the performance by introducing a bounding box detection algorithm as a preprocessing step in the segmentation pipeline. Our approach on 2D image is further extended to 2D+t sequence which ensures temporal consistency in the resultant sequence segmentations. When evaluated on clinical MCE data, our proposed method achieves notable improvement in segmentation accuracy and outperforms other state-of-the-art methods including the classic RF and its variants, active shape model and image registration.

##### Abstract (translated by Google)
心肌造影超声心动图（MCE）是一种评估左心室功能和心肌灌注检测冠状动脉疾病的成像技术。自动MCE灌注量化具有挑战性，并且需要从噪声和时变图像精确分割心肌。随机森林（RF）已成功应用于许多医学图像分割任务。然而，像素方式的RF分类器忽略了各个像素的标签输出之间的上下文关系。仅利用局部外观特征的RF也容易受到大的强度变化的影响。在本文中，我们演示了如何通过在全周期二维MCE数据中提供用于心肌分割的全自动分割流水线来克服经典RF的上述限制。具体来说，使用统计形状模型来提供形状先验信息，其以两种方式指导RF分割。首先，将新颖的形状模型（SM）特征结合到RF框架中以生成更准确的RF概率图。其次，形状模型拟合到射频概率图来改进和限制最终的分割，以合理的心肌形状。通过引入边界框检测算法作为分割流水线中的预处理步骤，我们进一步提高了性能。我们在二维图像上的方法进一步扩展到2D + t序列，这确保了所得序列分割中的时间一致性。当对临床MCE数据进行评估时，我们提出的方法在分割准确性方面取得了显着的改进，并且胜过了其他最先进的方法，包括经典的RF及其变体，活动形状模型和图像配准。

##### URL
[http://arxiv.org/abs/1806.07497](http://arxiv.org/abs/1806.07497)

##### PDF
[http://arxiv.org/pdf/1806.07497](http://arxiv.org/pdf/1806.07497)

