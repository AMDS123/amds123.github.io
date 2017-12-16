---
layout: post
title: "Rotational Rectification Network: Enabling Pedestrian Detection for Mobile Vision"
date: 2017-09-12 20:54:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xinshuo Weng, Shangxuan Wu, Fares Beainy, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
Across a majority of pedestrian detection datasets, it is typically assumed that pedestrians will be standing upright with respect to the image coordinate system. This assumption, however, is not always valid for many vision-equipped mobile platforms such as mobile phones, UAVs or construction vehicles on rugged terrain. In these situations, the motion of the camera can cause images of pedestrians to be captured at extreme angles. This can lead to very poor pedestrian detection performance when using standard pedestrian detectors. To address this issue, we propose a Rotational Rectification Network (R2N) that can be inserted into any CNN-based pedestrian (or object) detector to adapt it to significant changes in camera rotation. The rotational rectification network uses a 2D rotation estimation module that passes rotational information to a spatial transformer network to undistort image features. To enable robust rotation estimation, we propose a Global Polar Pooling (GP-Pooling) operator to capture rotational shifts in convolutional features. Through our experiments, we show how our rotational rectification network can be used to improve the performance of the state-of-the-art pedestrian detector under heavy image rotation by up to 45%

##### Abstract (translated by Google)
在大多数行人检测数据集上，通常假定行人将相对于图像坐标系统直立。然而，这种假设并不总是适用于诸如移动电话，无人机或崎岖地形上的施工车辆等配备有视觉的移动平台。在这些情况下，摄像机的运动会导致行人的图像以极端的角度被捕获。当使用标准行人探测器时，这会导致行人探测性能非常差。为了解决这个问题，我们提出了一个旋转校正网络（R2N），可以插入任何基于CNN的行人（或物体）探测器，以适应相机旋转的显着变化。旋转整流网络使用2D旋转估计模块，其将旋转信息传递到空间变换器网络以使图像特征不失真。为了实现可靠的旋转估计，我们提出了一个全局极坐标（GP-Pooling）算子来捕获卷积特征中的旋转移位。通过我们的实验，我们展示了如何使用我们的旋转校正网络来改善在重像旋转下高达45％的最先进的行人探测器的性能

##### URL
[https://arxiv.org/abs/1706.08917](https://arxiv.org/abs/1706.08917)

##### PDF
[https://arxiv.org/pdf/1706.08917](https://arxiv.org/pdf/1706.08917)

