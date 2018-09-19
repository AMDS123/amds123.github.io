---
layout: post
title: "Deep Textured 3D Reconstruction of Human Bodies"
date: 2018-09-18 06:19:55
categories: arXiv_CV
tags: arXiv_CV Sparse Face Deep_Learning Quantitative
author: Abbhinav Venkat, Sai Sagar Jinka, Avinash Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
Recovering textured 3D models of non-rigid human body shapes is challenging due to self-occlusions caused by complex body poses and shapes, clothing obstructions, lack of surface texture, background clutter, sparse set of cameras with non-overlapping fields of view, etc. Further, a calibration-free environment adds additional complexity to both - reconstruction and texture recovery. In this paper, we propose a deep learning based solution for textured 3D reconstruction of human body shapes from a single view RGB image. This is achieved by first recovering the volumetric grid of the non-rigid human body given a single view RGB image followed by orthographic texture view synthesis using the respective depth projection of the reconstructed (volumetric) shape and input RGB image. We propose to co-learn the depth information readily available with affordable RGBD sensors (e.g., Kinect) while showing multiple views of the same object during the training phase. We show superior reconstruction performance in terms of quantitative and qualitative results, on both, publicly available datasets (by simulating the depth channel with virtual Kinect) as well as real RGBD data collected with our calibrated multi Kinect setup.

##### Abstract (translated by Google)
由于复杂的身体姿势和形状，衣服障碍物，缺乏表面纹理，背景杂乱，具有非重叠视野的稀疏相机等引起的自我遮挡，恢复非刚性人体形状的纹理3D模型具有挑战性。此外，无校准环境增加了复制和纹理恢复的额外复杂性。在本文中，我们提出了一种基于深度学习的解决方案，用于从单视图RGB图像中对人体形状进行纹理化3D重建。这是通过首先在给定单视图RGB图像的情况下恢复非刚性人体的体积网格，然后使用重建（体积）形状和输入RGB图像的相应深度投影进行正交纹理视图合成来实现的。我们建议与经济实惠的RGBD传感器（例如，Kinect）共同学习现有的深度信息，同时在训练阶段显示同一物体的多个视图。我们在公开可用的数据集（通过使用虚拟Kinect模拟深度通道）以及使用我们校准的多Kinect设置收集的真实RGBD数据的定量和定性结果方面表现出卓越的重建性能。

##### URL
[https://arxiv.org/abs/1809.06547](https://arxiv.org/abs/1809.06547)

##### PDF
[https://arxiv.org/pdf/1809.06547](https://arxiv.org/pdf/1809.06547)

