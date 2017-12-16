---
layout: post
title: "Hierarchical Convolutional-Deconvolutional Neural Networks for Automatic Liver and Tumor Segmentation"
date: 2017-10-12 14:32:38
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative Detection
author: Yading Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of liver and its tumors is an essential step for extracting quantitative imaging biomarkers for accurate tumor detection, diagnosis, prognosis and assessment of tumor response to treatment. MICCAI 2017 Liver Tumor Segmentation Challenge (LiTS) provides a common platform for comparing different automatic algorithms on contrast-enhanced abdominal CT images in tasks including 1) liver segmentation, 2) liver tumor segmentation, and 3) tumor burden estimation. We participate this challenge by developing a hierarchical framework based on deep fully convolutional-deconvolutional neural networks (CDNN). A simple CDNN model is firstly trained to provide a quick but coarse segmentation of the liver on the entire CT volume, then another CDNN is applied to the liver region for fine liver segmentation. At last, the segmented liver region, which is enhanced by histogram equalization, is employed as an additional input to the third CDNN for tumor segmentation. Jaccard distance is used as loss function when training CDNN models to eliminate the need of sample re-weighting. Our framework is trained using the 130 challenge training cases provided by LiTS. The evaluation on the 70 challenge testing cases resulted in a mean Dice Similarity Coefficient (DSC) of 0.963 for liver segmentation, a mean DSC of 0.657 for tumor segmentation, and a root mean square error (RMSE) of 0.017 for tumor burden estimation, which ranked our method in the first, fifth and third place, respectively

##### Abstract (translated by Google)
肝脏及其肿瘤的自动分割是提取定量成像生物标记物以准确检测肿瘤，诊断，预后和评价肿瘤对治疗的反应的关键步骤。 MICCAI 2017年肝肿瘤分割挑战赛（LiTS）提供了一个通用平台，用于比较不同的自动算法对比增强腹部CT图像的任务，包括1）肝脏分割，2）肝肿瘤分割，3）肿瘤负荷估计。我们通过开发基于深度完全卷积 - 解卷积神经网络（CDNN）的分层框架来参与这个挑战。首先训练简单的CDNN模型以在整个CT体积上提供对肝脏的快速但粗略的分割，然后将另一CDNN应用于肝脏区域以进行精细的肝脏分割。最后，通过直方图均衡增强的分割的肝脏区域被用作用于肿瘤分割的第三CDNN的附加输入。在训练CDNN模型时，Jaccard距离被用作损失函数，以消除样本重新加权的需要。我们的框架是使用由LiTS提供的130个挑战训练案例进行训练的。对70个挑战性测试病例的评估导致肝脏分割的平均Dice相似系数（DSC）为0.963，肿瘤分割的平均DSC为0.657，并且肿瘤负荷估计的均方根误差（RMSE）为0.017，其分别排在第一位，第五位和第三位

##### URL
[https://arxiv.org/abs/1710.04540](https://arxiv.org/abs/1710.04540)

##### PDF
[https://arxiv.org/pdf/1710.04540](https://arxiv.org/pdf/1710.04540)

