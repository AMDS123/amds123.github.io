---
layout: post
title: "Long Short-Term Memory Kalman Filters:Recurrent Neural Estimators for Pose Regularization"
date: 2017-08-06 13:08:56
categories: arXiv_CV
tags: arXiv_CV Regularization Pose_Estimation Tracking Object_Tracking
author: Huseyin Coskun, Felix Achilles, Robert DiPietro, Nassir Navab, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
One-shot pose estimation for tasks such as body joint localization, camera pose estimation, and object tracking are generally noisy, and temporal filters have been extensively used for regularization. One of the most widely-used methods is the Kalman filter, which is both extremely simple and general. However, Kalman filters require a motion model and measurement model to be specified a priori, which burdens the modeler and simultaneously demands that we use explicit models that are often only crude approximations of reality. For example, in the pose-estimation tasks mentioned above, it is common to use motion models that assume constant velocity or constant acceleration, and we believe that these simplified representations are severely inhibitive. In this work, we propose to instead learn rich, dynamic representations of the motion and noise models. In particular, we propose learning these models from data using long short term memory, which allows representations that depend on all previous observations and all previous states. We evaluate our method using three of the most popular pose estimation tasks in computer vision, and in all cases we obtain state-of-the-art performance.

##### Abstract (translated by Google)
诸如身体关节定位，相机姿态估计和对象跟踪之类的任务的一次性姿态估计通常是有噪声的，并且时间滤波器已被广泛地用于正则化。卡尔曼滤波器是最广泛使用的方法之一，它非常简单和普遍。然而，卡尔曼滤波器需要先验地指定运动模型和测量模型，这给建模者带来负担，同时要求我们使用通常只是现实的粗略近似的显式模型。例如，在上述的姿态估计任务中，通常使用假设恒定速度或恒定加速度的运动模型，并且我们认为这些简化表示是严重抑制性的。在这项工作中，我们建议学习运动和噪声模型的丰富，动态的表示。特别是，我们建议使用长期的短期记忆从数据中学习这些模型，这允许表示取决于所有以前的观察和所有以前的状态。我们使用计算机视觉中最流行的三种姿势估计任务来评估我们的方法，在所有情况下，我们都获得了最先进的性能。

##### URL
[https://arxiv.org/abs/1708.01885](https://arxiv.org/abs/1708.01885)

##### PDF
[https://arxiv.org/pdf/1708.01885](https://arxiv.org/pdf/1708.01885)

