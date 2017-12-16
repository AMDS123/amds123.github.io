---
layout: post
title: "Locating 3D Object Proposals: A Depth-Based Online Approach"
date: 2017-09-08 11:24:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Drone Detection SLAM
author: Ramanpreet Singh Pahwa, Jiangbo Lu, Nianjuan Jiang, Tian Tsong Ng, Minh N. Do
mathjax: true
---

* content
{:toc}

##### Abstract
2D object proposals, quickly detected regions in an image that likely contain an object of interest, are an effective approach for improving the computational efficiency and accuracy of object detection in color images. In this work, we propose a novel online method that generates 3D object proposals in a RGB-D video sequence. Our main observation is that depth images provide important information about the geometry of the scene. Diverging from the traditional goal of 2D object proposals to provide a high recall (lots of 2D bounding boxes near potential objects), we aim for precise 3D proposals. We leverage on depth information per frame and multi-view scene information to obtain accurate 3D object proposals. Using efficient but robust registration enables us to combine multiple frames of a scene in near real time and generate 3D bounding boxes for potential 3D regions of interest. Using standard metrics, such as Precision-Recall curves and F-measure, we show that the proposed approach is significantly more accurate than the current state-of-the-art techniques. Our online approach can be integrated into SLAM based video processing for quick 3D object localization. Our method takes less than a second in MATLAB on the UW-RGBD scene dataset on a single thread CPU and thus, has potential to be used in low-power chips in Unmanned Aerial Vehicles (UAVs), quadcopters, and drones.

##### Abstract (translated by Google)
2D对象提议，在图像中可能包含感兴趣对象的快速检测区域是提高彩色图像中的对象检测的计算效率和准确度的有效方法。在这项工作中，我们提出了一种新颖的在线方法，可以在RGB-D视频序列中生成3D对象提议。我们主要观察的是深度图像提供了有关场景几何的重要信息。为了提供高回忆率（大量的潜在物体附近的二维边界框），我们瞄准精确的3D建议。我们利用每帧深度信息和多视点场景信息来获得准确的3D对象建议。使用高效但稳健的配准使我们能够近乎实时地组合多个场景的帧，并为潜在的感兴趣3D区域生成三维边界框。使用标准度量标准，例如Precision-Recall曲线和F-measure，我们表明，所提出的方法比当前的最新技术显着更准确。我们的在线方法可以集成到基于SLAM的视频处理中，以快速进行3D对象定位。在单线程CPU上，我们的方法在UW-RGBD场景数据集上花费不到一秒钟的时间，因此可用于无人机（UAV），四轴飞行器和无人机中的低功耗芯片。

##### URL
[https://arxiv.org/abs/1709.02653](https://arxiv.org/abs/1709.02653)

##### PDF
[https://arxiv.org/pdf/1709.02653](https://arxiv.org/pdf/1709.02653)

