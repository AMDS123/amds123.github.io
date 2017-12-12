---
layout: post
title: "MapNet: Geometry-Aware Learning of Maps for Camera Localization"
date: 2017-12-09 05:26:57
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Optimization Inference SLAM
author: Samarth Brahmbhatt, Jinwei Gu, Kihwan Kim, James Hays, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Maps are a key component in image-based camera localization and visual SLAM systems: they are used to establish geometric constraints between images, correct drift in relative pose estimation, and relocalize cameras after lost tracking. The exact definitions of maps, however, are often application-specific and hand-crafted for different scenarios (e.g., 3D landmarks, lines, planes, bags of visual words). We propose to represent maps as a deep neural net called MapNet, which enables learning a data-driven map representation. Unlike prior work on learning maps, MapNet exploits cheap and ubiquitous sensory inputs like visual odometry and GPS in addition to images and fuses them together for camera localization. Geometric constraints expressed by these inputs, which have traditionally been used in bundle adjustment or pose-graph optimization, are formulated as loss terms in MapNet training and also used during inference. In addition to directly improving localization accuracy, this allows us to update the MapNet (i.e., maps) in a self-supervised manner using additional unlabeled video sequences from the scene. We also propose a novel parameterization for camera rotation which is better suited for deep-learning based camera pose regression. Experimental results on both the indoor 7-Scenes dataset and the outdoor Oxford RobotCar dataset show significant performance improvement over prior work.

##### Abstract (translated by Google)
地图是基于图像的摄像机定位和视觉SLAM系统中的关键组件：它们被用于在图像之间建立几何约束，校正相对姿态估计中的漂移以及在丢失跟踪之后重新定位摄像机。然而，地图的确切定义通常是针对不同场景（例如，3D地标，线条，平面，视觉单词袋）的特定应用和手工制作的。我们建议将地图表示为称为MapNet的深层神经网络，它可以学习数据驱动的地图表示。与以前在学习地图上的工作不同，MapNet利用廉价且无处不在的感官输入，例如视觉测距和GPS以及图像融合在一起进行相机定位。这些输入所表达的几何约束（传统上用于束调整或姿态图优化）在MapNet训练中被表述为损失项，并且在推理期间也被使用。除了直接提高定位精度之外，这允许我们使用来自场景的附加未标记视频序列以自监督方式更新MapNet（即，地图）。我们还提出了一种新颖的相机旋转参数化，它更适合于基于深度学习的相机姿态回归。室内7-Scenes数据集和室外Oxford RobotCar数据集的实验结果显示，与以前的工作相比，其性能有了显着的提高。

##### URL
[http://arxiv.org/abs/1712.03342](http://arxiv.org/abs/1712.03342)

##### PDF
[http://arxiv.org/pdf/1712.03342](http://arxiv.org/pdf/1712.03342)

