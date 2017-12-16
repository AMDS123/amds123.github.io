---
layout: post
title: "3D Human Pose Estimation from a Single Image via Distance Matrix Regression"
date: 2016-11-28 07:36:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Quantitative Detection
author: Francesc Moreno-Noguer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of 3D human pose estimation from a single image. We follow a standard two-step pipeline by first detecting the 2D position of the $N$ body joints, and then using these observations to infer 3D pose. For the first step, we use a recent CNN-based detector. For the second step, most existing approaches perform 2$N$-to-3$N$ regression of the Cartesian joint coordinates. We show that more precise pose estimates can be obtained by representing both the 2D and 3D human poses using $N\times N$ distance matrices, and formulating the problem as a 2D-to-3D distance matrix regression. For learning such a regressor we leverage on simple Neural Network architectures, which by construction, enforce positivity and symmetry of the predicted matrices. The approach has also the advantage to naturally handle missing observations and allowing to hypothesize the position of non-observed joints. Quantitative results on Humaneva and Human3.6M datasets demonstrate consistent performance gains over state-of-the-art. Qualitative evaluation on the images in-the-wild of the LSP dataset, using the regressor learned on Human3.6M, reveals very promising generalization results.

##### Abstract (translated by Google)
本文从单幅图像中解决了三维人体姿态估计问题。我们遵循一个标准的两步管道，首先检测$ N $身体关节的2D位置，然后使用这些观察来推断3D姿势。第一步，我们使用最近的基于CNN的探测器。对于第二步，大多数现有的方法执行笛卡尔联合坐标的2 $ N $  - 到 -  3 $ N $回归。我们表明，更精确的姿态估计可以通过使用$ N \ times N $距离矩阵来表示二维和三维人体姿态并将该问题表示为二维到三维距离矩阵回归来获得。为了学习这样一个回归器，我们利用简单的神经网络架构，通过构建，强化预测矩阵的正性和对称性。该方法也有利于自然处理缺失的观察结果，并允许假设非观察关节的位置。 Humaneva和Human3.6M数据集的定量结果表明，与最先进的技术相比，性能得到了一致的提升。通过使用在Human3.6M上学习的回归器对LSP数据集的野外图像进行定性评估揭示了非常有希望的泛化结果。

##### URL
[https://arxiv.org/abs/1611.09010](https://arxiv.org/abs/1611.09010)

##### PDF
[https://arxiv.org/pdf/1611.09010](https://arxiv.org/pdf/1611.09010)

