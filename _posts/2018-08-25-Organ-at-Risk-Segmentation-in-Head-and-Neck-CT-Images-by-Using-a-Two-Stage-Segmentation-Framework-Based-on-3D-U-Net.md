---
layout: post
title: "Organ at Risk Segmentation in Head and Neck CT Images by Using a Two-Stage Segmentation Framework Based on 3D U-Net"
date: 2018-08-25 14:09:28
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Yueyue Wang, Liang Zhao, Zhijian Song, Manning Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate segmentation of organ at risk (OAR) play a critical role in the treatment planning of image guided radiation treatment of head and neck cancer. This segmentation task is challenging for both human and automatic algorithms because of the relatively large number of OARs to be segmented, the large variability of the size and morphology across different OARs, and the low contrast of between some OARs and the background. In this paper, we proposed a two-stage segmentation framework based on 3D U-Net. In this framework, the segmentation of each OAR is decomposed into two sub-tasks: locating a bounding box of the OAR and segment it from a small volume within the bounding box, and each sub-tasks is fulfilled by a dedicated 3D U-Net. The decomposition makes each of the two sub-tasks much easier, so that they can be better completed. We evaluated the proposed method and compared it to state-of-the-art methods by using the MICCAI 2015 Challenge dataset. In terms of the boundary-based metric 95HD, the proposed method ranked first in eight of all nine OARs and ranked second in the other OAR. In terms of the area-based metric DSC, the proposed method ranked first in six of the nine OARs and ranked second in the other three OARs with small difference with the first one.

##### Abstract (translated by Google)
准确分割风险器官（OAR）在头颈癌图像引导放射治疗的治疗计划中起关键作用。由于要分割的OAR数量相对较多，不同OAR的大小和形态差异较大，以及某些OAR与背景之间的对比度较低，因此该分割任务对人工和自动算法都具有挑战性。在本文中，我们提出了一个基于3D U-Net的两阶段分割框架。在此框架中，每个OAR的分段被分解为两个子任务：定位OAR的边界框并从边界框内的小体积中对其进行分割，每个子任务由专用的3D U-Net完成。 。分解使得两个子任务中的每一个都更容易，因此可以更好地完成它们。我们评估了所提出的方法，并使用MICCAI 2015 Challenge数据集将其与最先进的方法进行了比较。在基于边界的度量95HD方面，所提出的方法在所有9个OAR中的8个中排名第一，在另一个OAR中排名第二。在基于面积的度量DSC方面，所提出的方法在9个OAR中的6个中排名第一，在其他3个OAR中排名第二，与第一个OAR的差异很小。

##### URL
[http://arxiv.org/abs/1809.00960](http://arxiv.org/abs/1809.00960)

##### PDF
[http://arxiv.org/pdf/1809.00960](http://arxiv.org/pdf/1809.00960)

