---
layout: post
title: "3D-DETNet: a Single Stage Video-Based Vehicle Detector"
date: 2018-01-05 14:38:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Deep_Learning Detection
author: Suichan Li
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based vehicle detection has received considerable attention over the last ten years and there are many deep learning based detection methods which can be utilized to solve the problem. However, these methods are devised for still images and applying them for video vehicle detection directly always obtains poor performance. In this work, we propose a new one-stage video-based vehicle detector combined with 3DCovNet and focal loss, called 3D-DETNet. Draw support from 3D Convolution and focal loss, our method has ability to capture motion information and is more suitable to detect vehicle in video than other one-stage methods devised for static images. The multiple video frames are initially fed to 3D-DETNet to generate multiple spatial feature maps, then sub-model 3DConvNet takes spatial feature maps as input to capture temporal information which is fed to final fully convolution model for predicting locations of vehicles in video frames. We evaluate our method on UA-DETAC vehicle detection dataset and our 3D-DETNet yields best performance and keeps a higher detection speed of 26 fps compared with other competing methods.

##### Abstract (translated by Google)
基于视频的车辆检测在过去的十年中受到了相当的关注，并且有许多基于深度学习的检测方法可以用来解决这个问题。然而，这些方法是针对静止图像而设计的，并且将其应用于视频车辆检测直接总是获得较差的性能。在这项工作中，我们提出了一个新的一阶段基于视频的车辆检测器结合3DCovNet和焦点损失，称为3D-DETNet。借助3D卷积和焦点损失的支持，我们的方法具有捕获运动信息的能力，比用于静态图像的其他一阶段方法更适合在视频中检测车辆。多个视频帧首先被馈送到3D-DETNet以生成多个空间特征图，然后子模型3DConvNet将空间特征图作为输入来捕获时间信息，该时间信息被馈送到最终的完全卷积模型以预测视频帧中车辆的位置。我们在UA-DETAC车辆检测数据集上评估我们的方法，与其他竞争方法相比，我们的3D-DETNet产生最佳性能并保持26 fps的更高检测速度。

##### URL
[http://arxiv.org/abs/1801.01769](http://arxiv.org/abs/1801.01769)

##### PDF
[http://arxiv.org/pdf/1801.01769](http://arxiv.org/pdf/1801.01769)

