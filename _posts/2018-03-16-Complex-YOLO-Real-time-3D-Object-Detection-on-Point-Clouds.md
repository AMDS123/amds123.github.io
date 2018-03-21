---
layout: post
title: "Complex-YOLO: Real-time 3D Object Detection on Point Clouds"
date: 2018-03-16 12:54:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Prediction Detection
author: Martin Simon, Stefan Milz, Karl Amende, Horst-Michael Gross
mathjax: true
---

* content
{:toc}

##### Abstract
Lidar based 3D object detection is inevitable for autonomous driving, because it directly links to environmental understanding and therefore builds the base for prediction and motion planning. The capacity of inferencing highly sparse 3D data in real-time is an ill-posed problem for lots of other application areas besides automated vehicles, e.g. augmented reality, personal robotics or industrial automation. We introduce Complex-YOLO, a state of the art real-time 3D object detection network on point clouds only. In this work, we describe a network that expands YOLOv2, a fast 2D standard object detector for RGB images, by a specific complex regression strategy to estimate multi-class 3D boxes in Cartesian space. Thus, we propose a specific Euler-Region-Proposal Network (E-RPN) to estimate the pose of the object by adding an imaginary and a real fraction to the regression network. This ends up in a closed complex space and avoids singularities, which occur by single angle estimations. The E-RPN supports to generalize well during training. Our experiments on the KITTI benchmark suite show that we outperform current leading methods for 3D object detection specifically in terms of efficiency. We achieve state of the art results for cars, pedestrians and cyclists by being more than five times faster than the fastest competitor. Further, our model is capable of estimating all eight KITTI-classes, including Vans, Trucks or sitting pedestrians simultaneously with high accuracy.

##### Abstract (translated by Google)
基于激光雷达的三维物体检测对于自动驾驶是不可避免的，因为它直接与环境理解联系起来，因此为预测和运动规划奠定了基础。实时推断高度稀疏的3D数据的能力对于除了自动车辆之外的许多其他应用领域是不适合的问题，例如，增强现实，个人机器人或工业自动化。我们只介绍Complex-YOLO，这是一种最先进的点云实时三维物体检测网络。在这项工作中，我们描述了一个网络，该网络通过特定的复杂回归策略来扩展YOLOv2（一种用于RGB图像的快速2D标准物体检测器），以估计笛卡尔空间中的多类3D盒子。因此，我们提出了一个特定的欧拉区域提议网络（E-RPN），通过在回归网络中增加一个虚数和一个真实的分数来估计物体的姿态。这最终在一个封闭的复杂空间中，避免了单角度估计出现的奇点。 E-RPN支持在训练过程中进行概括。我们在KITTI基准测试套件上进行的实验表明，我们在效率方面超越了目前领先的三维物体检测方法。我们通过比最快的竞争对手快五倍的速度，为汽车，行人和骑自行车者带来最先进的成果。此外，我们的模型能够以高精度同时估算所有八个KITTI类别，包括货车，卡车或行人。

##### URL
[https://arxiv.org/abs/1803.06199](https://arxiv.org/abs/1803.06199)

##### PDF
[https://arxiv.org/pdf/1803.06199](https://arxiv.org/pdf/1803.06199)

