---
layout: post
title: "QuadricSLAM: Constrained Dual Quadrics from Object Detections as Landmarks in Semantic SLAM"
date: 2018-04-10 06:55:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection SLAM
author: Lachlan Nicholson, Michael Milford, Niko Sünderhauf
mathjax: true
---

* content
{:toc}

##### Abstract
Research in Simultaneous Localization And Mapping (SLAM) is increasingly moving towards richer world representations involving objects and high level features that enable a semantic model of the world for robots, potentially leading to a more meaningful set of robot-world interactions. Many of these advances are grounded in state-of-the-art computer vision techniques primarily developed in the context of image-based benchmark datasets, leaving several challenges to be addressed in adapting them for use in robotics. In this paper, we derive a SLAM formulation that uses dual quadrics as 3D landmark representations, exploiting their ability to compactly represent the size, position and orientation of an object, and show how 2D bounding boxes (such as those typically obtained from visual object detection systems) can directly constrain the quadric parameters via a novel geometric error formulation. We develop a sensor model for deep-learned object detectors that addresses the challenge of partial object detections often encountered in robotics applications, and demonstrate how to jointly estimate the camera pose and constrained dual quadric parameters in factor graph based SLAM with a general perspective camera.

##### Abstract (translated by Google)
同步定位和映射研究（SLAM）越来越趋向于更丰富的世界表征，涉及对象和高级特征，使机器人世界的语义模型成为可能，从而导致更有意义的机器人世界交互。这些进步中的许多都基于先进的计算机视觉技术，这些技术主要是在基于图像的基准数据集的背景下开发的，留下了几个挑战，以便使它们适用于机器人技术。在本文中，我们推导出一种SLAM公式，该公式使用双二次函数作为3D地标表示，利用它们紧凑地表示一个对象的大小，位置和方向的能力，并展示2D边界框（例如通常从视觉对象检测系统）可以通过新的几何误差公式直接约束二次参数。我们开发了深度学习物体探测器的传感器模型，解决了机器人应用中经常遇到的部分物体探测难题，并演示了如何在基于因子图的SLAM中使用通用透视相机联合估计相机姿态和约束双二次参数。

##### URL
[https://arxiv.org/abs/1804.04011](https://arxiv.org/abs/1804.04011)

##### PDF
[https://arxiv.org/pdf/1804.04011](https://arxiv.org/pdf/1804.04011)

