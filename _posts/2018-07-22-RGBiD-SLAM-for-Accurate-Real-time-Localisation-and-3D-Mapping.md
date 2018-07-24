---
layout: post
title: "RGBiD-SLAM for Accurate Real-time Localisation and 3D Mapping"
date: 2018-07-22 11:05:24
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Daniel Gutierrez-Gomez, Jose J. Guerrero
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a complete SLAM system for RGB-D cameras, namely RGB-iD SLAM. The presented approach is a dense direct SLAM method with the main characteristic of working with the depth maps in inverse depth parametrisation for the routines of dense alignment or keyframe fusion. The system consists in 2 CPU threads working in parallel, which share the use of the GPU for dense alignment and keyframe fusion routines. The first thread is a front-end operating at frame rate, which processes every incoming frame from the RGB-D sensor to compute the incremental odometry and integrate it in a keyframe which is changed periodically following a covisibility-based strategy. The second thread is a back-end which receives keyframes from the front-end. This thread is in charge of segmenting the keyframes based on their structure, describing them using Bags of Words, trying to find potential loop closures with previous keyframes, and in such case perform pose-graph optimisation for trajectory correction. In addition, our system allows is able to compute the odometry both with unregistered and registered depth maps, allowing to use customised calibrations of the RGB-D sensor. As a consequence in the paper we also propose a detailed calibration pipeline to compute customised calibrations for particular RGB-D cameras. The experiments with our approach in the TUM RGB-D benchmark datasets show results superior in accuracy to the state-of-the-art in many of the sequences. The code has been made available on-line for research purposes https://github.com/dangut/RGBiD-SLAM.

##### Abstract (translated by Google)
在本文中，我们提出了一个完整的RGB-D摄像机SLAM系统，即RGB-iD SLAM。所提出的方法是密集的直接SLAM方法，其主要特征是在深度参数化中使用深度图来进行密集对齐或关键帧融合的例程。该系统包含2个并行工作的CPU线程，它们共享GPU用于密集对齐和关键帧融合例程。第一个线程是以帧速率运行的前端，它处理来自RGB-D传感器的每个输入帧以计算增量测距并将其集成到关键帧中，该关键帧根据基于可见性的策略定期更改。第二个线程是后端，它从前端接收关键帧。该线程负责根据关键帧的结构对关键帧进行分段，使用包词来描述它们，试图找到具有先前关键帧的潜在循环闭包，并且在这种情况下执行用于轨迹校正的姿势图优化。此外，我们的系统允许使用未注册和注册的深度图计算测距，允许使用RGB-D传感器的定制校准。因此，本文还提出了一个详细的校准管道，用于计算特定RGB-D摄像机的定制校准。在TUM RGB-D基准数据集中使用我们的方法进行的实验显示，在许多序列中，结果的准确性优于现有技术。该代码已在线提供用于研究目的https://github.com/dangut/RGBiD-SLAM。

##### URL
[http://arxiv.org/abs/1807.08271](http://arxiv.org/abs/1807.08271)

##### PDF
[http://arxiv.org/pdf/1807.08271](http://arxiv.org/pdf/1807.08271)

