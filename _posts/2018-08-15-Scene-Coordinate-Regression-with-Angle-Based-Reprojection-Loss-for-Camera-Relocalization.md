---
layout: post
title: "Scene Coordinate Regression with Angle-Based Reprojection Loss for Camera Relocalization"
date: 2018-08-15 08:25:15
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Xiaotian Li, Juha Ylioinas, Jakob Verbeek, Juho Kannala
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based camera relocalization is an important problem in computer vision and robotics. Recent works utilize convolutional neural networks (CNNs) to regress for pixels in a query image their corresponding 3D world coordinates in the scene. The final pose is then solved via a RANSAC-based optimization scheme using the predicted coordinates. Usually, the CNN is trained with ground truth scene coordinates, but it has also been shown that the network can discover 3D scene geometry automatically by minimizing single-view reprojection loss. However, due to the deficiencies of reprojection loss, the network needs to be carefully initialized. In this paper, we present a new angle-based reprojection loss which resolves the issues of the original reprojection loss. With this new loss function, the network can be trained without careful initialization, and the system achieves more accurate results. The new loss also enables us to utilize available multi-view constraints, which further improve performance.

##### Abstract (translated by Google)
基于图像的相机重定位是计算机视觉和机器人技术中的一个重要问题。最近的工作利用卷积神经网络（CNN）来回归查询图像中的像素，它们在场景中对应的3D世界坐标。然后使用预测的坐标通过基于RANSAC的优化方案解决最终姿势。通常，CNN使用地面实况场景坐标进行训练，但是也已经表明网络可以通过最小化单视图重投影损失来自动发现3D场景几何。但是，由于重投影损失的不足，需要仔细初始化网络。在本文中，我们提出了一种新的基于角度的重投影损失，它解决了原始重投影损失的问题。利用这种新的损耗功能，无需仔细初始化即可对网络进行训练，系统可以获得更准确的结果。新的损失还使我们能够利用可用的多视图约束，从而进一步提高性能。

##### URL
[http://arxiv.org/abs/1808.04999](http://arxiv.org/abs/1808.04999)

##### PDF
[http://arxiv.org/pdf/1808.04999](http://arxiv.org/pdf/1808.04999)

