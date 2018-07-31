---
layout: post
title: "Learning Rigidity in Dynamic Scenes with a Moving Camera for 3D Motion Field Estimation"
date: 2018-07-30 08:11:45
categories: arXiv_CV
tags: arXiv_CV
author: Zhaoyang Lv, Kihwan Kim, Alejandro Troccoli, Deqing Sun, James M. Rehg, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Estimation of 3D motion in a dynamic scene from a temporal pair of images is a core task in many scene understanding problems. In real world applications, a dynamic scene is commonly captured by a moving camera (i.e., panning, tilting or hand-held), increasing the task complexity because the scene is observed from different view points. The main challenge is the disambiguation of the camera motion from scene motion, which becomes more difficult as the amount of rigidity observed decreases, even with successful estimation of 2D image correspondences. Compared to other state-of-the-art 3D scene flow estimation methods, in this paper we propose to \emph{learn} the rigidity of a scene in a supervised manner from a large collection of dynamic scene data, and directly infer a rigidity mask from two sequential images with depths. With the learned network, we show how we can effectively estimate camera motion and projected scene flow using computed 2D optical flow and the inferred rigidity mask. For training and testing the rigidity network, we also provide a new semi-synthetic dynamic scene dataset (synthetic foreground objects with a real background) and an evaluation split that accounts for the percentage of observed non-rigid pixels. Through our evaluation we show the proposed framework outperforms current state-of-the-art scene flow estimation methods in challenging dynamic scenes.

##### Abstract (translated by Google)
从时间对图像估计动态场景中的3D运动是许多场景理解问题中的核心任务。在现实世界的应用中，动态场景通常由移动的相机捕获（即，平移，倾斜或手持），增加了任务复杂性，因为从不同的视点观察场景。主要挑战是从场景运动中消除相机运动的歧义，即使成功估计2D图像对应，随着观察到的刚度的减少，这变得更加困难。与其他最先进的三维场景流估计方法相比，本文提出了从大量动态场景数据中以监督方式“学习”场景的刚度，并直接推断刚度从具有深度的两个连续图像中掩盖。通过学习的网络，我们展示了如何使用计算的2D光流和推断的刚性掩模有效地估计相机运动和投影场景流。为了训练和测试刚性网络，我们还提供了一个新的半合成动态场景数据集（具有真实背景的合成前景对象）和一个评估分割，它考虑了观察到的非刚性像素的百分比。通过我们的评估，我们展示了提出的框架优于当前最先进的场景流量估计方法在具有挑战性的动态场景中。

##### URL
[http://arxiv.org/abs/1804.04259](http://arxiv.org/abs/1804.04259)

##### PDF
[http://arxiv.org/pdf/1804.04259](http://arxiv.org/pdf/1804.04259)

