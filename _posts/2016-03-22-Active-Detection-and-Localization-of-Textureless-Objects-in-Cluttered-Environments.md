---
layout: post
title: "Active Detection and Localization of Textureless Objects in Cluttered Environments"
date: 2016-03-22 22:55:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Pose_Estimation Detection
author: Marco Imperoli, Alberto Pretto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces an active object detection and localization framework that combines a robust untextured object detection and 3D pose estimation algorithm with a novel next-best-view selection strategy. We address the detection and localization problems by proposing an edge-based registration algorithm that refines the object position by minimizing a cost directly extracted from a 3D image tensor that encodes the minimum distance to an edge point in a joint direction/location space. We face the next-best-view problem by exploiting a sequential decision process that, for each step, selects the next camera position which maximizes the mutual information between the state and the next observations. We solve the intrinsic intractability of this solution by generating observations that represent scene realizations, i.e. combination samples of object hypothesis provided by the object detector, while modeling the state by means of a set of constantly resampled particles. Experiments performed on different real world, challenging datasets confirm the effectiveness of the proposed methods.

##### Abstract (translated by Google)
本文介绍了一个主动对象检测和定位框架，结合了鲁棒的无纹理对象检测和三维姿态估计算法与一种新颖的次优选择策略。我们通过提出基于边缘的配准算法来解决检测和定位问题，该配准算法通过最小化直接从3D图像张量中提取的成本来优化对象位置，所述3D图像张量编码到联合方向/位置空间中的边缘点的最小距离。我们通过利用一个连续的决策过程来面对下一个最佳观点问题，在每个步骤中，选择下一个摄像机位置，使状态和下一个观察之间的相互信息最大化。我们通过产生表示场景实现的观察值，即由对象检测器提供的对象假设的组合样本，同时通过一组经常重新采样的粒子对状态进行建模来解决该解决方案的内在难处理性。在不同的真实世界，具有挑战性的数据集上进行的实验证实了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1603.07022](https://arxiv.org/abs/1603.07022)

##### PDF
[https://arxiv.org/pdf/1603.07022](https://arxiv.org/pdf/1603.07022)

