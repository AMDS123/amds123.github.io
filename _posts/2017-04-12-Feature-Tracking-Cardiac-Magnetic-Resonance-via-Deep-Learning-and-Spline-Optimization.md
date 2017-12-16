---
layout: post
title: "Feature Tracking Cardiac Magnetic Resonance via Deep Learning and Spline Optimization"
date: 2017-04-12 08:43:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Optimization Deep_Learning
author: Davis M. Vigneault, Weidi Xie, David A. Bluemke, J. Alison Noble
mathjax: true
---

* content
{:toc}

##### Abstract
Feature tracking Cardiac Magnetic Resonance (CMR) has recently emerged as an area of interest for quantification of regional cardiac function from balanced, steady state free precession (SSFP) cine sequences. However, currently available techniques lack full automation, limiting reproducibility. We propose a fully automated technique whereby a CMR image sequence is first segmented with a deep, fully convolutional neural network (CNN) architecture, and quadratic basis splines are fitted simultaneously across all cardiac frames using least squares optimization. Experiments are performed using data from 42 patients with hypertrophic cardiomyopathy (HCM) and 21 healthy control subjects. In terms of segmentation, we compared state-of-the-art CNN frameworks, U-Net and dilated convolution architectures, with and without temporal context, using cross validation with three folds. Performance relative to expert manual segmentation was similar across all networks: pixel accuracy was ~97%, intersection-over-union (IoU) across all classes was ~87%, and IoU across foreground classes only was ~85%. Endocardial left ventricular circumferential strain calculated from the proposed pipeline was significantly different in control and disease subjects (-25.3% vs -29.1%, p = 0.006), in agreement with the current clinical literature.

##### Abstract (translated by Google)
特征追踪心脏磁共振（CMR）最近出现作为一个感兴趣的区域定量的区域心脏功能从平衡，稳态免费岁差（SSFP）电影序列。然而，目前可用的技术缺乏全自动化，限制了重复性。我们提出了一种全自动化技术，CMR图像序列首先用深度完全卷积神经网络（CNN）体系结构进行分割，并且使用最小二乘优化在所有心脏帧上同时拟合二次基本样条。使用来自42名肥厚型心肌病（HCM）患者和21名健康对照受试者的数据进行实验。在分割方面，我们比较了最先进的CNN框架，U-Net和扩展卷积体系结构，使用和不使用时间背景，使用三次交叉验证。相对于专家手动分割的性能在所有网络中都是相似的：像素准确度为〜97％，所有类别的交集（IoU）为〜87％，前景类中的IoU仅为〜85％。根据目前的临床文献，拟建管道计算得到的心内膜左心室周向应变在对照组和疾病组中显着不同（分别为-25.3％vs -29.1％，p = 0.006）。

##### URL
[https://arxiv.org/abs/1704.03660](https://arxiv.org/abs/1704.03660)

##### PDF
[https://arxiv.org/pdf/1704.03660](https://arxiv.org/pdf/1704.03660)

