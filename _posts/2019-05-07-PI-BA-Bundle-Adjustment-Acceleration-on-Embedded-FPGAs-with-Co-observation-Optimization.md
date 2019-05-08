---
layout: post
title: "PI-BA Bundle Adjustment Acceleration on Embedded FPGAs with Co-observation Optimization"
date: 2019-05-07 06:40:00
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Shuzhen Qin, Qiang Liu, Bo Yu, Shaoshan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Bundle adjustment (BA) is a fundamental optimization technique used in many crucial applications, including 3D scene reconstruction, robotic localization, camera calibration, autonomous driving, space exploration, street view map generation etc. Essentially, BA is a joint non-linear optimization problem, and one which can consume a significant amount of time and power, especially for large optimization problems. Previous approaches of optimizing BA performance heavily rely on parallel processing or distributed computing, which trade higher power consumption for higher performance. In this paper we propose {\pi}-BA, the first hardware-software co-designed BA engine on an embedded FPGA-SoC that exploits custom hardware for higher performance and power efficiency. Specifically, based on our key observation that not all points appear on all images in a BA problem, we designed and implemented a Co-Observation Optimization technique to accelerate BA operations with optimized usage of memory and computation resources. Experimental results confirm that {\pi}-BA outperforms the existing software implementations in terms of performance and power consumption.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02373](http://arxiv.org/abs/1905.02373)

##### PDF
[http://arxiv.org/pdf/1905.02373](http://arxiv.org/pdf/1905.02373)

