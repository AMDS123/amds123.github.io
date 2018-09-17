---
layout: post
title: "A Time Series Graph Cut Image Segmentation Scheme for Liver Tumors"
date: 2018-09-13 23:56:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Laramie Paxton, Yufeng Cao, Kevin R. Vixie, Yuan Wang, Brian Hobbs, Chaan Ng
mathjax: true
---

* content
{:toc}

##### Abstract
Tumor detection in biomedical imaging is a time-consuming process for medical professionals and is not without errors. Thus in recent decades, researchers have developed algorithmic techniques for image processing using a wide variety of mathematical methods, such as statistical modeling, variational techniques, and machine learning. In this paper, we propose a semi-automatic method for liver segmentation of 2D CT scans into three labels denoting healthy, vessel, or tumor tissue based on graph cuts. First, we create a feature vector for each pixel in a novel way that consists of the 59 intensity values in the time series data and propose a simplified perimeter cost term in the energy functional. We normalize the data and perimeter terms in the functional to expedite the graph cut without having to optimize the scaling parameter $\lambda$. In place of a training process, predetermined tissue means are computed based on sample regions identified by expert radiologists. The proposed method also has the advantage of being relatively simple to implement computationally. It was evaluated against the ground truth on a clinical CT dataset of 10 tumors and yielded segmentations with a mean Dice similarity coefficient (DSC) of .77 and mean volume overlap error (VOE) of 36.7%. The average processing time was 1.25 minutes per slice.

##### Abstract (translated by Google)
生物医学成像中的肿瘤检测对于医疗专业人员来说是一个耗时的过程并且没有错误。因此，近几十年来，研究人员使用各种数学方法开发了用于图像处理的算法技术，例如统计建模，变分技术和机器学习。在本文中，我们提出了一种半自动方法，用于将2D CT扫描肝脏分割成三个标签，表示基于图形切割的健康，血管或肿瘤组织。首先，我们以一种新颖的方式为每个像素创建一个特征向量，该方式由时间序列数据中的59个强度值组成，并在能量函数中提出简化的周长成本项。我们将函数中的数据和周长项标准化，以加快图形切割，而无需优化缩放参数$ \ lambda $。代替训练过程，基于由专业放射科医师识别的样本区域计算预定的组织装置。所提出的方法还具有计算实现相对简单的优点。在10个肿瘤的临床CT数据集上对照基础事实进行评估，并产生具有平均Dice相似系数（DSC）为0.77且平均体积重叠误差（VOE）为36.7％的分割。每片的平均处理时间为1.25分钟。

##### URL
[http://arxiv.org/abs/1809.05210](http://arxiv.org/abs/1809.05210)

##### PDF
[http://arxiv.org/pdf/1809.05210](http://arxiv.org/pdf/1809.05210)

