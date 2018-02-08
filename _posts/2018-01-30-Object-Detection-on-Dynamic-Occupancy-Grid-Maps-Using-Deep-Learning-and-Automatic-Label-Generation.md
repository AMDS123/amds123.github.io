---
layout: post
title: "Object Detection on Dynamic Occupancy Grid Maps Using Deep Learning and Automatic Label Generation"
date: 2018-01-30 08:18:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Deep_Learning Detection
author: Stefan Hoermann, Philipp Henzler, Martin Bach, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of object detection and pose estimation in a shared space downtown environment. For perception multiple laser scanners with 360{\deg} coverage were fused in a dynamic occupancy grid map (DOGMa). A single-stage deep convolutional neural network is trained to provide object hypotheses comprising of shape, position, orientation and an existence score from a single input DOGMa. Furthermore, an algorithm for offline object extraction was developed to automatically label several hours of training data. The algorithm is based on a two-pass trajectory extraction, forward and backward in time. Typical for engineered algorithms, the automatic label generation suffers from misdetections, which makes hard negative mining impractical. Therefore, we propose a loss function counteracting the high imbalance between mostly static background and extremely rare dynamic grid cells. Experiments indicate, that the trained network has good generalization capabilities since it detects objects occasionally lost by the label algorithm. Evaluation reaches an average precision (AP) of 75.9%

##### Abstract (translated by Google)
我们在市中心共享空间中解决物体检测和姿态估计的问题。对于感知，具有360°覆盖的多个激光扫描器被融合在动态占用网格图（DOGMa）中。训练单级深度卷积神经网络以提供包括来自单个输入DOGMa的形状，位置，方向和存在分数的对象假设。此外，开发了离线对象提取算法，自动标记几个小时的训练数据。该算法基于两次弹道提取，在时间上前后移。典型的工程算法，自动标签生成遭受错误检测，这使得硬性负面挖掘不切实际。因此，我们提出了一个抵消大多数静态背景和极其罕见的动态网格单元之间高度不平衡的损失函数。实验表明，训练好的网络具有良好的泛化能力，因为它检测到标签算法偶尔丢失的对象。评估的平均精确度（AP）为75.9％

##### URL
[https://arxiv.org/abs/1802.02202](https://arxiv.org/abs/1802.02202)

##### PDF
[https://arxiv.org/pdf/1802.02202](https://arxiv.org/pdf/1802.02202)

