---
layout: post
title: "Deep Virtual Stereo Odometry: Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry"
date: 2018-07-06 21:14:31
categories: arXiv_CV
tags: arXiv_CV Sparse Prediction
author: Nan Yang, Rui Wang, J&#xf6;rg St&#xfc;ckler, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular visual odometry approaches that purely rely on geometric cues are prone to scale drift and require sufficient motion parallax in successive frames for motion estimation and 3D reconstruction. In this paper, we propose to leverage deep monocular depth prediction to overcome limitations of geometry-based monocular visual odometry. To this end, we incorporate deep depth predictions into Direct Sparse Odometry as direct virtual stereo measurements. For depth prediction, we design a novel deep network that refines predicted depth from a single image in a two-stage process. We train our network in a semi-supervised way on photoconsistency in stereo images and on consistency with accurate sparse depth reconstructions from Stereo DSO. Our deep predictions excel state-of-the-art approaches for monocular depth on the KITTI benchmark. Moreover, our Deep Virtual Stereo Odometry clearly exceeds previous monocular and deep-learning based methods in accuracy. It even achieves comparable performance to the state-of-the-art stereo methods, while only relying on a single camera.

##### Abstract (translated by Google)
纯粹依赖于几何线索的单目视觉测距方法易于出现尺度漂移，并且在连续帧中需要足够的运动视差以用于运动估计和3D重建。在本文中，我们建议利用深度单眼深度预测来克服基于几何的单眼视觉测距的局限性。为此，我们将直接稀疏测距的深度预测结合为直接虚拟立体测量。对于深度预测，我们设计了一种新的深度网络，在两阶段过程中从单个图像中提炼出预测深度。我们以半监督的方式训练我们的网络，用于立体图像中的光子一致性以及与立体声DSO的精确稀疏深度重建的一致性。我们的深度预测在KITTI基准测试中优于单眼深度的最先进方法。此外，我们的深度虚拟立体声测距显然超过以前的单眼和深度学习方法的准确性。它甚至可以实现与最先进的立体声方法相媲美的性能，同时仅依靠单个相机。

##### URL
[http://arxiv.org/abs/1807.02570](http://arxiv.org/abs/1807.02570)

##### PDF
[http://arxiv.org/pdf/1807.02570](http://arxiv.org/pdf/1807.02570)

