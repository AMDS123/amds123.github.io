---
layout: post
title: "A General Framework for Flexible Multi-Cue Photometric Point Cloud Registration"
date: 2017-09-13 12:36:33
categories: arXiv_CV
tags: arXiv_CV
author: Bartolomeo Della Corte, Igor Bogoslavskyi, Cyrill Stachniss, Giorgio Grisetti
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to build maps is a key functionality for the majority of mobile robots. A central ingredient to most mapping systems is the registration or alignment of the recorded sensor data. In this paper, we present a general methodology for photometric registration that can deal with multiple different cues. We provide examples for registering RGBD as well as 3D LIDAR data. In contrast to popular point cloud registration approaches such as ICP our method does not rely on explicit data association and exploits multiple modalities such as raw range and image data streams. Color, depth, and normal information are handled in an uniform manner and the registration is obtained by minimizing the pixel-wise difference between two multi-channel images. We developed a flexible and general framework and implemented our approach inside that framework. We also released our implementation as open source C++ code. The experiments show that our approach allows for an accurate registration of the sensor data without requiring an explicit data association or model-specific adaptations to datasets or sensors. Our approach exploits the different cues in a natural and consistent way and the registration can be done at framerate for a typical range or imaging sensor.

##### Abstract (translated by Google)
构建地图的能力是大多数移动机器人的关键功能。大多数测绘系统的核心要素是记录的传感器数据的登记或对齐。在本文中，我们提出了一个光度记录的一般方法，可以处理多个不同的线索。我们提供注册RGBD以及3D LIDAR数据的示例。与流行的点云注册方法（如ICP）相反，我们的方法不依赖显式数据关联，并利用多种模式（如原始范围和图像数据流）。颜色，深度和正常信息以统一的方式处理，并且通过最小化两个多通道图像之间的逐像素差异来获得配准。我们开发了一个灵活的通用框架，并在该框架内实施了我们的方法。我们还以开源C ++代码的形式发布了我们的实现。实验表明，我们的方法允许传感器数据的准确配准，而不需要明确的数据关联或针对数据集或传感器的模型特定适配。我们的方法以自然和一致的方式利用不同的线索，并且可以以典型的范围或成像传感器的帧率进行配准。

##### URL
[https://arxiv.org/abs/1709.05945](https://arxiv.org/abs/1709.05945)

##### PDF
[https://arxiv.org/pdf/1709.05945](https://arxiv.org/pdf/1709.05945)

