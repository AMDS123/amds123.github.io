---
layout: post
title: "Visual Compiler: Synthesizing a Scene-Specific Pedestrian Detector and Pose Estimator"
date: 2016-12-15 20:43:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Pose_Estimation CNN Detection
author: Namhoon Lee, Xinshuo Weng, Vishnu Naresh Boddeti, Yu Zhang, Fares Beainy, Kris Kitani, Takeo Kanade
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the concept of a Visual Compiler that generates a scene specific pedestrian detector and pose estimator without any pedestrian observations. Given a single image and auxiliary scene information in the form of camera parameters and geometric layout of the scene, the Visual Compiler first infers geometrically and photometrically accurate images of humans in that scene through the use of computer graphics rendering. Using these renders we learn a scene-and-region specific spatially-varying fully convolutional neural network, for simultaneous detection, pose estimation and segmentation of pedestrians. We demonstrate that when real human annotated data is scarce or non-existent, our data generation strategy can provide an excellent solution for bootstrapping human detection and pose estimation. Experimental results show that our approach outperforms off-the-shelf state-of-the-art pedestrian detectors and pose estimators that are trained on real data.

##### Abstract (translated by Google)
我们介绍一个视觉编译器的概念，生成一个场景特定的行人检测器和姿态估计器，没有任何行人观察。通过摄像机参数和场景几何布局的形式给出单个图像和辅助场景信息，Visual Compiler首先通过使用计算机图形渲染来推断该场景中人类的几何图像和光度计精确图像。使用这些渲染，我们学习了一个场景和区域特定的空间变化完全卷积神经网络，用于行人的同时检测，姿态估计和分割。我们证明，当真实的人类注释数据稀缺或不存在时，我们的数据生成策略可以为引导人类检测和姿态估计提供出色的解决方案。实验结果表明，我们的方法胜过现成的最先进的行人检测器和姿态估计器，这些估计器在真实数据上得到了训练。

##### URL
[https://arxiv.org/abs/1612.05234](https://arxiv.org/abs/1612.05234)

##### PDF
[https://arxiv.org/pdf/1612.05234](https://arxiv.org/pdf/1612.05234)

