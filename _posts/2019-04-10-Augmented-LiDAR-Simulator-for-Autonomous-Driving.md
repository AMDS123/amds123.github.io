---
layout: post
title: "Augmented LiDAR Simulator for Autonomous Driving"
date: 2019-04-10 09:59:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Jin Fang, Dingfu Zhou, Feilong Yan, Tongtong Zhao, Feihu Zhang, Yu Ma, Liang Wang, Ruigang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In Autonomous Driving (AD), detection and tracking of obstacles on the roads is a critical task. Deep-learning based methods using annotated LiDAR data have been the most widely adopted approach for this. Unfortunately, annotating 3D point cloud is a very challenging, time- and money-consuming task. In this paper, we propose a novel LiDAR simulator that augments real point cloud with synthetic obstacles (e.g., cars, pedestrians, and other movable objects). Unlike previous simulators that entirely rely on CG models and game engines, our augmented simulator bypasses the requirement to create high-fidelity background CAD models. Instead, we can simply deploy a vehicle with a LiDAR scanner to sweep the street of interests to obtain the background point cloud, based on which annotated point cloud can be automatically generated. This unique "scan-and-simulate" capability makes our approach scalable and practical, ready for large-scale industrial applications. In this paper, we describe our simulator in detail, in particular the placement of obstacles that is critical for performance enhancement. We show that detectors with our simulated LiDAR point cloud alone can perform comparably (within two percentage points) with these trained with real data. Mixing real and simulated data can achieve over 95% accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07112](http://arxiv.org/abs/1811.07112)

##### PDF
[http://arxiv.org/pdf/1811.07112](http://arxiv.org/pdf/1811.07112)

