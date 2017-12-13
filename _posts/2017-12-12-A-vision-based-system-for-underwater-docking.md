---
layout: post
title: "A vision based system for underwater docking"
date: 2017-12-12 05:59:49
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation CNN Detection
author: Shuang Liu, Mete Ozay, Takayuki Okatani, Hongli Xu, Kai Sun, Yang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous underwater vehicles (AUVs) have been deployed for underwater exploration. However, its potential is confined by its limited on-board battery energy and data storage capacity. This problem has been addressed using docking systems by underwater recharging and data transfer for AUVs. In this work, we propose a vision based framework for underwater docking following these systems. The proposed framework comprises two modules; (i) a detection module which provides location information on underwater docking stations in 2D images captured by an on-board camera, and (ii) a pose estimation module which recovers the relative 3D position and orientation between docking stations and AUVs from the 2D images. For robust and credible detection of docking stations, we propose a convolutional neural network called Docking Neural Network (DoNN). For accurate pose estimation, a perspective-n-point algorithm is integrated into our framework. In order to examine our framework in underwater docking tasks, we collected a dataset of 2D images, named Underwater Docking Images Dataset (UDID), in an experimental water pool. To the best of our knowledge, UDID is the first publicly available underwater docking dataset. In the experiments, we first evaluate performance of the proposed detection module on UDID and its deformed variations. Next, we assess the accuracy of the pose estimation module by ground experiments, since it is not feasible to obtain true relative position and orientation between docking stations and AUVs under water. Then, we examine the pose estimation module by underwater experiments in our experimental water pool. Experimental results show that the proposed framework can be used to detect docking stations and estimate their relative pose efficiently and successfully, compared to the state-of-the-art baseline systems.

##### Abstract (translated by Google)
自主水下航行器（AUV）已经被用于水下探测。然而，其潜力受限于其有限的车载电池能量和数据存储容量。这个问题已经通过水下充电和AUV数据传输的对接系统得到了解决。在这项工作中，我们提出了一个基于视觉的水下对接框架。拟议的框架包括两个模块; （i）检测模块，其在由机载照相机捕获的2D图像中提供关于水下对接站的位置信息，以及（ii）姿势估计模块，其从2D图像恢复对接站与AUV之间的相对3D位置和取向。为了稳定和可靠地检测坞站，我们提出了一个称为对接神经网络（DoNN）的卷积神经网络。为了精确的姿态估计，一个透视n点算法被整合到我们的框架中。为了检验我们在水下对接任务中的框架，我们在实验水池中收集了一个名为水下对接图像数据集（UDID）的二维图像数据集。据我们所知，UDID是第一个公开可用的水下对接数据集。在实验中，我们首先评估在UDID上提出的检测模块的性能及其变形的变化。接下来，我们通过地面实验来评估姿态估计模块的准确性，因为在水下在坞站和AUV之间获得真实的相对位置和定向是不可行的。然后，我们在实验水池中通过水下实验来检查姿态估计模块。实验结果表明，与最先进的基线系统相比，所提出的框架可以用来检测对接站并且有效并且成功地估计它们的相对位姿。

##### URL
[http://arxiv.org/abs/1712.04138](http://arxiv.org/abs/1712.04138)

##### PDF
[http://arxiv.org/pdf/1712.04138](http://arxiv.org/pdf/1712.04138)

