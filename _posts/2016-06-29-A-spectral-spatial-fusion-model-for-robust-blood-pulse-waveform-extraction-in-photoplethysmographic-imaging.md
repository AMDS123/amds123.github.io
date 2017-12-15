---
layout: post
title: "A spectral-spatial fusion model for robust blood pulse waveform extraction in photoplethysmographic imaging"
date: 2016-06-29 14:31:09
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Robert Amelard, David A Clausi, Alexander Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Photoplethysmographic imaging is a camera-based solution for non-contact cardiovascular monitoring from a distance. This technology enables monitoring in situations where contact-based devices may be problematic or infeasible, such as ambulatory, sleep, and multi-individual monitoring. However, extracting the blood pulse waveform signal is challenging due to the unknown mixture of relevant (pulsatile) and irrelevant pixels in the scene. Here, we design and implement a signal fusion framework, FusionPPG, for extracting a blood pulse waveform signal with strong temporal fidelity from a scene without requiring anatomical priors (e.g., facial tracking). The extraction problem is posed as a Bayesian least squares fusion problem, and solved using a novel probabilistic pulsatility model that incorporates both physiologically derived spectral and spatial waveform priors to identify pulsatility characteristics in the scene. Experimental results show statistically significantly improvements compared to the FaceMeanPPG method ($p<0.001$) and DistancePPG ($p<0.001$) methods. Heart rates predicted using FusionPPG correlated strongly with ground truth measurements ($r^2=0.9952$). FusionPPG was the only method able to assess cardiac arrhythmia via temporal analysis.

##### Abstract (translated by Google)
光电容积脉搏波成像是一种基于照相机的远距离非接触式心血管监测解决方案。这种技术可以在基于接触的设备可能有问题或不可行的情况下进行监控，例如走动式，睡眠和多个人监控。然而，由于场景中的相关（脉动）和不相关像素的未知混合，提取血脉波形信号是具有挑战性的。在这里，我们设计和实现了信号融合框架FusionPPG，用于从场景中提取具有强时间保真度的血脉波形信号，而不需要解剖学先验（例如面部跟踪）。提取问题被提出为贝叶斯最小二乘融合问题，并且使用新颖的概率性脉动模型来解决，该模型包括生理学派生的光谱和空间波形先验以识别场景中的脉动特性。与FaceMeanPPG方法（$ p <0.001 $）和DistancePPG（$ p <0.001 $）方法相比，实验结果显示统计显着改善。使用FusionPPG预测的心率与地面真实测量（$ r ^ 2 = 0.9952 $）有很强的相关性。融合PPG是通过时间分析评估心律失常的唯一方法。

##### URL
[https://arxiv.org/abs/1606.09118](https://arxiv.org/abs/1606.09118)

##### PDF
[https://arxiv.org/pdf/1606.09118](https://arxiv.org/pdf/1606.09118)

