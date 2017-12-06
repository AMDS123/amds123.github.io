---
layout: post
title: "Bayesian Scale Estimation for Monocular SLAM Based on Generic Object Detection for Correcting Scale Drift"
date: 2017-11-07 23:28:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Edgar Sucar, Jean-Bernard Hayet
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a new, online algorithm for estimating the local scale correction to apply to the output of a monocular SLAM system and obtain an as faithful as possible metric reconstruction of the 3D map and of the camera trajectory. Within a Bayesian framework, it integrates observations from a deep-learning based generic object detector and a prior on the evolution of the scale drift. For each observation class, a predefined prior on the heights of the class objects is used. This allows to define the observations likelihood. Due to the scale drift inherent to monocular SLAM systems, we integrate a rough model on the dynamics of scale drift. Quantitative evaluations of the system are presented on the KITTI dataset, and compared with different approaches. The results show a superior performance of our proposal in terms of relative translational error when compared to other monocular systems.

##### Abstract (translated by Google)
这项工作提出了一种新的在线算法，用于估计局部尺度校正，以应用于单眼SLAM系统的输出，并获得尽可能忠实的三维地图和相机轨迹的度量重建。在贝叶斯框架内，它集成了基于深度学习的通用对象检测器的观测数据和规模漂移发展的先验数据。对于每个观察类，使用类对象的高度上的预先定义的前一个。这允许定义观测可能性。由于单眼SLAM系统固有的尺度漂移，我们在尺度漂移的动力学上整合了一个粗略的模型。系统的定量评估在KITTI数据集上呈现，并与不同的方法进行比较。结果显示，与其他单眼系统相比，我们的建议在相对平移误差方面表现出色。

##### URL
[https://arxiv.org/abs/1711.02768](https://arxiv.org/abs/1711.02768)

