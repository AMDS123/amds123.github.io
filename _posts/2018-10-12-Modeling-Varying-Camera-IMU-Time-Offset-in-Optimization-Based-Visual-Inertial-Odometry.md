---
layout: post
title: "Modeling Varying Camera-IMU Time Offset in Optimization-Based Visual-Inertial Odometry"
date: 2018-10-12 11:35:27
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Yonggen Ling, Linchao Bao, Zequn Jie, Fengming Zhu, Ziyang Li, Shanmin Tang, Yongsheng Liu, Wei Liu, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Combining cameras and inertial measurement units (IMUs) has been proven effective in motion tracking, as these two sensing modalities offer complementary characteristics that are suitable for fusion. While most works focus on global-shutter cameras and synchronized sensor measurements, consumer-grade devices are mostly equipped with rolling-shutter cameras and suffer from imperfect sensor synchronization. In this work, we propose a nonlinear optimization-based monocular visual inertial odometry (VIO) with varying camera-IMU time offset modeled as an unknown variable. Our approach is able to handle the rolling-shutter effects and imperfect sensor synchronization in a unified way. Additionally, we introduce an efficient algorithm based on dynamic programming and red-black tree to speed up IMU integration over variable-length time intervals during the optimization. An uncertainty-aware initialization is also presented to launch the VIO robustly. Comparisons with state-of-the-art methods on the Euroc dataset and mobile phone data are shown to validate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05456](https://arxiv.org/abs/1810.05456)

##### PDF
[https://arxiv.org/pdf/1810.05456](https://arxiv.org/pdf/1810.05456)

