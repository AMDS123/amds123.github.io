---
layout: post
title: "Spiking Optical Flow for Event-based Sensors Using IBM's TrueNorth Neurosynaptic System"
date: 2017-10-26 17:33:34
categories: arXiv_CV
tags: arXiv_CV
author: Germain Haessig, Andrew Cassidy, Rodrigo Alvarez, Ryad Benosman, Garrick Orchard
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a fully spike-based neural network for optical flow estimation from Dynamic Vision Sensor data. A low power embedded implementation of the method which combines the Asynchronous Time-based Image Sensor with IBM's TrueNorth Neurosynaptic System is presented. The sensor generates spikes with sub-millisecond resolution in response to scene illumination changes. These spike are processed by a spiking neural network running on TrueNorth with a 1 millisecond resolution to accurately determine the order and time difference of spikes from neighboring pixels, and therefore infer the velocity. The spiking neural network is a variant of the Barlow Levick method for optical flow estimation. The system is evaluated on two recordings for which ground truth motion is available, and achieves an Average Endpoint Error of 11% at an estimated power budget of under 80mW for the sensor and computation.

##### Abstract (translated by Google)
本文描述了一个完全基于尖峰的神经网络，用于从动态视觉传感器数据中进行光流估计。介绍了一种将基于异步时间的图像传感器与IBM的TrueNorth神经突触系统相结合的低功耗嵌入式实现。传感器响应场景照明变化产生亚毫秒分辨率的尖峰。这些尖峰由在TrueNorth上运行的峰值神经网络以1毫秒的分辨率来处理，以准确地确定来自相邻像素的尖峰的顺序和时间差，并且因此推断速度。峰值神经网络是用于光流估计的Barlow Levick方法的变体。系统在两个记录上进行评估，其中可以得到地面真实运动，并且在传感器和计算的估计功率预算低于80mW时达到11％的平均终点误差。

##### URL
[https://arxiv.org/abs/1710.09820](https://arxiv.org/abs/1710.09820)

##### PDF
[https://arxiv.org/pdf/1710.09820](https://arxiv.org/pdf/1710.09820)

