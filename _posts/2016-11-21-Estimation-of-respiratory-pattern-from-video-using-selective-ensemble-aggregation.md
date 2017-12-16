---
layout: post
title: "Estimation of respiratory pattern from video using selective ensemble aggregation"
date: 2016-11-21 08:02:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Relation
author: A. P. Prathosh, Pragathi Praveena, Lalit K. Mestha, Sanjay Bharadwaj
mathjax: true
---

* content
{:toc}

##### Abstract
Non-contact estimation of respiratory pattern (RP) and respiration rate (RR) has multiple applications. Existing methods for RP and RR measurement fall into one of the three categories - (i) estimation through nasal air flow measurement, (ii) estimation from video-based remote photoplethysmography, and (iii) estimation by measurement of motion induced by respiration using motion detectors. These methods, however, require specialized sensors, are computationally expensive and/or critically depend on selection of a region of interest (ROI) for processing. In this paper a general framework is described for estimating a periodic signal driving noisy LTI channels connected in parallel with unknown dynamics. The method is then applied to derive a computationally inexpensive method for estimating RP using 2D cameras that does not critically depend on ROI. Specifically, RP is estimated by imaging the changes in the reflected light caused by respiration-induced motion. Each spatial location in the field of view of the camera is modeled as a noise-corrupted linear time-invariant (LTI) measurement channel with unknown system dynamics, driven by a single generating respiratory signal. Estimation of RP is cast as a blind deconvolution problem and is solved through a method comprising subspace projection and statistical aggregation. Experiments are carried out on 31 healthy human subjects by generating multiple RPs and comparing the proposed estimates with simultaneously acquired ground truth from an impedance pneumograph device. The proposed estimator agrees well with the ground truth device in terms of correlation measures, despite variability in clothing pattern, angle of view and ROI.

##### Abstract (translated by Google)
呼吸模式（RP）和呼吸频率（RR）的非接触估计有多种应用。现有的RP和RR测量方法属于三类之一 - （i）通过鼻腔气流测量进行估计，（ii）基于视频的远程光电容积脉搏波测量的估计，以及（iii）通过使用运动测量由呼吸引起的运动的估计探测器。然而，这些方法需要专门的传感器，计算成本昂贵和/或严重依赖于选择感兴趣区域（ROI）进行处理。在本文中描述了一个通用的框架来估计周期性的信号驱动噪声LTI通道与未知动态并联。然后将该方法应用于导出用于使用不依赖于ROI的2D相机来估计RP的计算便宜的方法。具体而言，通过对由呼吸引起的运动引起的反射光的变化进行成像来估计RP。照相机视野中的每个空间位置被模拟为具有未知系统动态的噪声破坏的线性时不变（LTI）测量通道，由单个生成的呼吸信号驱动。 RP的估计被作为盲解卷积问题来解决，并且通过包括子空间投影和统计聚合的方法来解决。通过产生多个RP并将所提出的估计与来自阻抗呼吸器设备的同时获得的基础事实进行比较，对31个健康人类对象进行实验。所提出的估计量在相关性测量方面与地面真值装置一致，尽管服装模式，视角和投资回报率存在差异。

##### URL
[https://arxiv.org/abs/1611.06674](https://arxiv.org/abs/1611.06674)

##### PDF
[https://arxiv.org/pdf/1611.06674](https://arxiv.org/pdf/1611.06674)

