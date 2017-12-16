---
layout: post
title: "Flight Dynamics-based Recovery of a UAV Trajectory using Ground Cameras"
date: 2017-11-21 11:25:44
categories: arXiv_CV
tags: arXiv_CV Tracking Quantitative Detection
author: Artem Rozantsev, Sudipta N. Sinha, Debadeepta Dey, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method to estimate the 6-dof trajectory of a flying object such as a quadrotor UAV within a 3D airspace monitored using multiple fixed ground cameras. It is based on a new structure from motion formulation for the 3D reconstruction of a single moving point with known motion dynamics. Our main contribution is a new bundle adjustment procedure which in addition to optimizing the camera poses, regularizes the point trajectory using a prior based on motion dynamics (or specifically flight dynamics). Furthermore, we can infer the underlying control input sent to the UAV's autopilot that determined its flight trajectory. Our method requires neither perfect single-view tracking nor appearance matching across views. For robustness, we allow the tracker to generate multiple detections per frame in each video. The true detections and the data association across videos is estimated using robust multi-view triangulation and subsequently refined during our bundle adjustment procedure. Quantitative evaluation on simulated data and experiments on real videos from indoor and outdoor scenes demonstrates the effectiveness of our method.

##### Abstract (translated by Google)
我们提出了一种新的方法来估计飞行物体的四自由度飞行轨迹，例如在使用多个固定的地面相机监视的三维空域内的四旋翼无人机。它基于运动公式的新结构，用于已知运动动力学的单个运动点的三维重建。我们的主要贡献是一个新的束调整过程，除了优化摄像机姿态之外，使用基于运动动力学（或者特别是飞行动力学）的先验来调整点轨迹。此外，我们可以推断发送给无人机的自动驾驶仪的基础控制输入，确定其飞行轨迹。我们的方法既不需要完美的单视图跟踪，也不需要在视图之间匹配。为了鲁棒性，我们允许跟踪器在每个视频中生成每帧多次检测。跨视频的真实检测和数据关联使用稳健的多视图三角测量进行估计，并随后在我们的束调整过程中进行细化。模拟数据的定量评估和室内外场景实景的实验证明了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1612.00192](https://arxiv.org/abs/1612.00192)

##### PDF
[https://arxiv.org/pdf/1612.00192](https://arxiv.org/pdf/1612.00192)

