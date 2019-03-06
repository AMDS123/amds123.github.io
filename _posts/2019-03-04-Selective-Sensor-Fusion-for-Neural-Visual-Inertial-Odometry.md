---
layout: post
title: "Selective Sensor Fusion for Neural Visual-Inertial Odometry"
date: 2019-03-04 20:51:37
categories: arXiv_RO
tags: arXiv_RO Deep_Learning Relation
author: Changhao Chen, Stefano Rosa, Yishu Miao, Chris Xiaoxuan Lu, Wei Wu, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches for Visual-Inertial Odometry (VIO) have proven successful, but they rarely focus on incorporating robust fusion strategies for dealing with imperfect input sensory data. We propose a novel end-to-end selective sensor fusion framework for monocular VIO, which fuses monocular images and inertial measurements in order to estimate the trajectory whilst improving robustness to real-life issues, such as missing and corrupted data or bad sensor synchronization. In particular, we propose two fusion modalities based on different masking strategies: deterministic soft fusion and stochastic hard fusion, and we compare with previously proposed direct fusion baselines. During testing, the network is able to selectively process the features of the available sensor modalities and produce a trajectory at scale. We present a thorough investigation on the performances on three public autonomous driving, Micro Aerial Vehicle (MAV) and hand-held VIO datasets. The results demonstrate the effectiveness of the fusion strategies, which offer better performances compared to direct fusion, particularly in presence of corrupted data. In addition, we study the interpretability of the fusion networks by visualising the masking layers in different scenarios and with varying data corruption, revealing interesting correlations between the fusion networks and imperfect sensory input data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01534](http://arxiv.org/abs/1903.01534)

##### PDF
[http://arxiv.org/pdf/1903.01534](http://arxiv.org/pdf/1903.01534)

