---
layout: post
title: "Robust Odometry using Sensor Consensus Analysis"
date: 2018-03-06 15:06:04
categories: arXiv_RO
tags: arXiv_RO
author: Andrew W. Palmer, Navid Nourani-Vatani
mathjax: true
---

* content
{:toc}

##### Abstract
Odometry forms an important component of many manned and autonomous systems. In the rail industry in particular, having precise and robust odometry is crucial for the correct operation of the Automatic Train Protection systems that ensure the safety of high-speed trains in operation around the world. Two problems commonly encountered in such odometry systems are miscalibration of the wheel encoders and slippage of the wheels under acceleration and braking, resulting in incorrect velocity estimates. This paper introduces an odometry system that addresses these problems. It comprises of an Extended Kalman Filter that tracks the calibration of the wheel encoders as state variables, and a measurement pre-processing stage called Sensor Consensus Analysis (SCA) that scales the uncertainty of a measurement based on how consistent it is with the measurements of the other sensors. SCA uses the statistical z-test to determine when an individual measurement is inconsistent with the other measurements, and scales the uncertainty until the z-test passes. This system is demonstrated on data from German Intercity-Express high-speed trains and it is shown to successfully deal with errors due to miscalibration and wheel slip.

##### Abstract (translated by Google)
Odometry是许多有人和自主系统的重要组成部分。特别是在铁路行业，具有精确和强大的测距功能对于确保全球运行的高速列车安全性的自动列车保护系统的正确运行至关重要。在这种测距系统中经常遇到的两个问题是车轮编码器的误校准和车轮在加速和制动下的滑动，导致不正确的速度估计。本文介绍了一种解决这些问题的测距系统。它包括一个扩展卡尔曼滤波器，跟踪车轮编码器的校准作为状态变量，以及称为传感器一致性分析（SCA）的测量预处理阶段，该阶段根据测量的不确定性来衡量测量的不确定性。其他传感器。 SCA使用统计z检验来确定单独的测量何时与其他测量不一致，并且在z检验通过之前缩放不确定性。该系统通过德国城际快车高速列车的数据进行演示，并且可以成功处理由于误校准和车轮打滑而导致的错误。

##### URL
[http://arxiv.org/abs/1803.02237](http://arxiv.org/abs/1803.02237)

##### PDF
[http://arxiv.org/pdf/1803.02237](http://arxiv.org/pdf/1803.02237)

