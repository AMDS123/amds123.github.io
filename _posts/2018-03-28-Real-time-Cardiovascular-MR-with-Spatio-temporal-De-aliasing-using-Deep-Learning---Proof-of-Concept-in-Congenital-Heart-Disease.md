---
layout: post
title: "Real-time Cardiovascular MR with Spatio-temporal De-aliasing using Deep Learning - Proof of Concept in Congenital Heart Disease"
date: 2018-03-28 21:27:41
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Andreas Hauptmann, Simon Arridge, Felix Lucka, Vivek Muthurangu, Jennifer A. Steeden
mathjax: true
---

* content
{:toc}

##### Abstract
PURPOSE: Real-time assessment of ventricular volumes requires high acceleration factors. Residual convolutional neural networks (CNN) have shown potential for removing artifacts caused by data undersampling. In this study we investigated the effect of different radial sampling patterns on the accuracy of a CNN. We also acquired actual real-time undersampled radial data in patients with congenital heart disease (CHD), and compare CNN reconstruction to Compressed Sensing (CS). 
 METHODS: A 3D (2D plus time) CNN architecture was developed, and trained using 2276 gold-standard paired 3D data sets, with 14x radial undersampling. Four sampling schemes were tested, using 169 previously unseen 3D 'synthetic' test data sets. Actual real-time tiny Golden Angle (tGA) radial SSFP data was acquired in 10 new patients (122 3D data sets), and reconstructed using the 3D CNN as well as a CS algorithm; GRASP. 
 RESULTS: Sampling pattern was shown to be important for image quality, and accurate visualisation of cardiac structures. For actual real-time data, overall reconstruction time with CNN (including creation of aliased images) was shown to be more than 5x faster than GRASP. Additionally, CNN image quality and accuracy of biventricular volumes was observed to be superior to GRASP for the same raw data. 
 CONCLUSION: This paper has demonstrated the potential for the use of a 3D CNN for deep de-aliasing of real-time radial data, within the clinical setting. Clinical measures of ventricular volumes using real-time data with CNN reconstruction are not statistically significantly different from the gold-standard, cardiac gated, BH techniques.

##### Abstract (translated by Google)
目的：实时评估心室容积需要高加速因子。残余卷积神经网络（CNN）已经显示出去除由数据欠采样引起的伪影的潜力。在这项研究中，我们调查了不同径向采样模式对CNN精度的影响。我们还获得了先天性心脏病（CHD）患者的实际实时欠采样径向数据，并将CNN重建与压缩感测（CS）进行比较。
 方法：开发了一个3D（二维加时间）CNN架构，并使用2276个黄金标准配对3D数据集和14倍径向欠采样进行训练。使用169个以前未见过的3D“合成”测试数据集对四种采样方案进行了测试。在10名新患者（122个3D数据集）中采集实际实时微小黄金角（tGA）径向SSFP数据，并使用3D CNN和CS算法重建;把握。
 结果显示采样模式对于图像质量以及心脏结构的精确可视化非常重要。对于实际的实时数据，CNN的整体重建时间（包括创建别名图像）显示比GRASP快5倍以上。此外，对于相同的原始数据，观察到CNN图像质量和双心室体积的准确性优于GRASP。
 结论：本文展示了在临床环境中使用3D CNN进行实时径向数据的深度消除的潜力。采用CNN重建的实时数据对心室容积的临床测量与金标准心脏门控BH技术无统计学差异。

##### URL
[http://arxiv.org/abs/1803.05192](http://arxiv.org/abs/1803.05192)

##### PDF
[http://arxiv.org/pdf/1803.05192](http://arxiv.org/pdf/1803.05192)

