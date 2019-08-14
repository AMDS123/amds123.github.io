---
layout: post
title: "LSTM-Based Zero-Velocity Detection for Robust Inertial Navigation"
date: 2019-08-13 17:18:50
categories: arXiv_RO
tags: arXiv_RO Object_Detection RNN Detection
author: Brandon Wagstaff, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to improve the accuracy of a zero-velocity-aided inertial navigation system (INS) by replacing the standard zero-velocity detector with a long short-term memory (LSTM) neural network. While existing threshold-based zero-velocity detectors are not robust to varying motion types, our learned model accurately detects stationary periods of the inertial measurement unit (IMU) despite changes in the motion of the user. Upon detection, zero-velocity pseudo-measurements are fused with a dead reckoning motion model in an extended Kalman filter (EKF). We demonstrate that our LSTM-based zero-velocity detector, used within a zero-velocity-aided INS, improves zero-velocity detection during human localization tasks. Consequently, localization accuracy is also improved. 
 Our system is evaluated on more than 7.5 km of indoor pedestrian locomotion data, acquired from five different subjects. We show that 3D positioning error is reduced by over 34% compared to existing fixed-threshold zero-velocity detectors for walking, running, and stair climbing motions. Additionally, we demonstrate how our learned zero-velocity detector operates effectively during crawling and ladder climbing. Our system is calibration-free (no careful threshold-tuning is required) and operates consistently with differing users, IMU placements, and shoe types, while being compatible with any generic zero-velocity-aided INS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.05275](http://arxiv.org/abs/1807.05275)

##### PDF
[http://arxiv.org/pdf/1807.05275](http://arxiv.org/pdf/1807.05275)

