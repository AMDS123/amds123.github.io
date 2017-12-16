---
layout: post
title: "Automatic Segmentation and Disease Classification Using Cardiac Cine MR Images"
date: 2017-08-03 13:55:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Jelmer M. Wolterink, Tim Leiner, Max A. Viergever, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of the heart in cardiac cine MR is clinically used to quantify cardiac function. We propose a fully automatic method for segmentation and disease classification using cardiac cine MR images. A convolutional neural network (CNN) was designed to simultaneously segment the left ventricle (LV), right ventricle (RV) and myocardium in end-diastole (ED) and end-systole (ES) images. Features derived from the obtained segmentations were used in a Random Forest classifier to label patients as suffering from dilated cardiomyopathy, hypertrophic cardiomyopathy, heart failure following myocardial infarction, right ventricular abnormality, or no cardiac disease. The method was developed and evaluated using a balanced dataset containing images of 100 patients, which was provided in the MICCAI 2017 automated cardiac diagnosis challenge (ACDC). The segmentation and classification pipeline were evaluated in a four-fold stratified cross-validation. Average Dice scores between reference and automatically obtained segmentations were 0.94, 0.88 and 0.87 for the LV, RV and myocardium. The classifier assigned 91% of patients to the correct disease category. Segmentation and disease classification took 5 s per patient. The results of our study suggest that image-based diagnosis using cine MR cardiac scans can be performed automatically with high accuracy.

##### Abstract (translated by Google)
心脏电影MR中的心脏的分割被临床用于量化心脏功能。我们提出了一个全自动的方法分割和疾病分类使用心脏电影磁共振图像。卷积神经网络（CNN）被设计用于同时分割心室舒张末期（ED）和收缩末期（ES）图像中的左心室（LV），右心室（RV）和心肌。来自所获得的分割的特征用于随机森林分类器中，以将患者标记为患有扩张型心肌病，肥厚型心肌病，心肌梗塞后的心力衰竭，右心室异常或无心脏疾病。该方法的开发和评估使用包含100名患者的图像的平衡数据集，其在MICCAI 2017自动化心脏诊断挑战（ACDC）中提供。分割和分类管道在四重分层交叉验证中进行评估。参考和自动获得的分割之间的平均骰子分数对于LV，RV和心肌是0.94,0.88和0.87。分类器将91％的患者分配到正确的疾病类别。分割和疾病分类每个病人需要5秒。我们的研究结果表明，使用电影MR心脏扫描的图像诊断可以高精度地自动执行。

##### URL
[https://arxiv.org/abs/1708.01141](https://arxiv.org/abs/1708.01141)

##### PDF
[https://arxiv.org/pdf/1708.01141](https://arxiv.org/pdf/1708.01141)

