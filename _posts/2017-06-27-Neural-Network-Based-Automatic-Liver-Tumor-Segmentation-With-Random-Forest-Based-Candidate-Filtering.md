---
layout: post
title: "Neural Network-Based Automatic Liver Tumor Segmentation With Random Forest-Based Candidate Filtering"
date: 2017-06-27 07:07:20
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN
author: Grzegorz Chlebus, Hans Meine, Jan Hendrik Moltz, Andrea Schenk
mathjax: true
---

* content
{:toc}

##### Abstract
We present a fully automatic method employing convolutional neural networks based on the 2D U-net architecture and random forest classifier to solve the automatic liver lesion segmentation problem of the ISBI 2017 Liver Tumor Segmentation Challenge (LiTS). In order to constrain the ROI in which the tumors could be located, a liver segmentation is performed first. For the organ segmentation, an ensemble of convolutional networks is trained to segment a liver using a set of 179 liver CT datasets from liver surgery planning. Inside of the liver ROI a neural network, trained using 127 challenge training datasets, identifies tumor candidates, which are subsequently filtered with a random forest classifier yielding the final tumor segmentation. The evaluation on the 70 challenge test cases resulted in a mean Dice coefficient of 0.65, ranking our method in the second place.

##### Abstract (translated by Google)
本文提出了一种基于二维U网结构和随机森林分类器的卷积神经网络全自动方法，解决ISBI 2017肝肿瘤分割挑战（LiTS）肝脏自动分割问题。为了限制肿瘤可能位于的ROI，首先进行肝脏分割。对于器官分割，卷积网络的集合被训练以使用来自肝脏手术计划的一组179个肝脏CT数据集来分割肝脏。在肝脏ROI内部，使用127个挑战训练数据集训练的神经网络识别肿瘤候选者，随后用随机森林分类器过滤，产生最终的肿瘤分割。对70个挑战性测试案例的评估导致平均Dice系数为0.65，排名第二。

##### URL
[https://arxiv.org/abs/1706.00842](https://arxiv.org/abs/1706.00842)

##### PDF
[https://arxiv.org/pdf/1706.00842](https://arxiv.org/pdf/1706.00842)

