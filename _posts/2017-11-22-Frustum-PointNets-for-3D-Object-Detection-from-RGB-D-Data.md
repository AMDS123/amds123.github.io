---
layout: post
title: "Frustum PointNets for 3D Object Detection from RGB-D Data"
date: 2017-11-22 19:52:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Deep_Learning Detection Recognition
author: Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
While object recognition on 2D images is getting more and more mature, 3D understanding is eagerly in demand yet largely underexplored. In this paper, we study the 3D object detection problem from RGB-D data captured by depth sensors in both indoor and outdoor environments. Different from previous deep learning methods that work on 2D RGB-D images or 3D voxels, which often obscure natural 3D patterns and invariances of 3D data, we directly operate on raw point clouds by popping up RGB-D scans. Although recent works such as PointNet performs well for segmentation in small-scale point clouds, one key challenge is how to efficiently detect objects in large-scale scenes. Leveraging the wisdom of dimension reduction and mature 2D object detectors, we develop a Frustum PointNet framework that addresses the challenge. Evaluated on KITTI and SUN RGB-D 3D detection benchmarks, our method outperforms state of the arts by remarkable margins with high efficiency (running at 5 fps).

##### Abstract (translated by Google)
虽然二维图像上的物体识别越来越成熟，但三维图像的理解仍然非常需要，但尚未被大量研究。在本文中，我们研究了室内和室外环境下由深度传感器捕获的RGB-D数据的三维物体检测问题。与之前深入研究2D RGB-D图像或3D体素的深层学习方法不同，后者通常会模糊3D数据的自然3D模式和不变性，直接通过弹出RGB-D扫描操作原始点云。尽管最近的工作如PointNet在小尺度点云中的分割效果很好，但是一个关键的挑战是如何在大规模的场景中有效地检测物体。利用降维和成熟的二维物体探测器的智慧，我们开发了一个应对挑战的Frustum PointNet框架。在KITTI和SUN RGB-D 3D检测基准上进行评估，我们的方法以高效率（5 fps运行）显着提高了效率。

##### URL
[https://arxiv.org/abs/1711.08488](https://arxiv.org/abs/1711.08488)

