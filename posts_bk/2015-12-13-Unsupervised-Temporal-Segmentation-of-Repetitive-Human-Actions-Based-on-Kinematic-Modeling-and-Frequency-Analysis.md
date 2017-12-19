---
layout: post
title: "Unsupervised Temporal Segmentation of Repetitive Human Actions Based on Kinematic Modeling and Frequency Analysis"
date: 2015-12-13 20:08:43
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Qifei Wang, Gregorij Kurillo, Ferda Ofli, Ruzena Bajcsy
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for temporal segmentation of human repetitive actions based on frequency analysis of kinematic parameters, zero-velocity crossing detection, and adaptive k-means clustering. Since the human motion data may be captured with different modalities which have different temporal sampling rate and accuracy (e.g., optical motion capture systems vs. Microsoft Kinect), we first apply a generic full-body kinematic model with an unscented Kalman filter to convert the motion data into a unified representation that is robust to noise. Furthermore, we extract the most representative kinematic parameters via the primary frequency analysis. The sequences are segmented based on zero-velocity crossing of the selected parameters followed by an adaptive k-means clustering to identify the repetition segments. Experimental results demonstrate that for the motion data captured by both the motion capture system and the Microsoft Kinect, our proposed algorithm obtains robust segmentation of repetitive action sequences.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于运动参数频率分析，零速度交叉检测和自适应k均值聚类的人体重复动作时间分割方法。由于人体运动数据可以采用具有不同时间采样率和精确度的不同模态来捕捉（例如，光学运动捕捉系统与微软Kinect相比），所以我们首先应用具有无迹卡尔曼滤波器的通用全身运动学模型来将运动数据转换成对噪声强健的统一表示。此外，我们通过主频分析提取最具代表性的运动学参数。基于所选参数的零速度交叉来分割序列，接着是自适应k均值聚类以识别重复段。实验结果表明，对于运动捕捉系统和Mi​​crosoft Kinect捕捉的运动数据，我们提出的算法获得了重复动作序列的鲁棒分割。

##### URL
[https://arxiv.org/abs/1512.04115](https://arxiv.org/abs/1512.04115)

##### PDF
[https://arxiv.org/pdf/1512.04115](https://arxiv.org/pdf/1512.04115)

