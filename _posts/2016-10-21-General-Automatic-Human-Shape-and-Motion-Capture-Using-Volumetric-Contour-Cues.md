---
layout: post
title: "General Automatic Human Shape and Motion Capture Using Volumetric Contour Cues"
date: 2016-10-21 11:23:31
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Helge Rhodin, Nadia Robertini, Dan Casas, Christian Richardt, Hans-Peter Seidel, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
Markerless motion capture algorithms require a 3D body with properly personalized skeleton dimension and/or body shape and appearance to successfully track a person. Unfortunately, many tracking methods consider model personalization a different problem and use manual or semi-automatic model initialization, which greatly reduces applicability. In this paper, we propose a fully automatic algorithm that jointly creates a rigged actor model commonly used for animation - skeleton, volumetric shape, appearance, and optionally a body surface - and estimates the actor's motion from multi-view video input only. The approach is rigorously designed to work on footage of general outdoor scenes recorded with very few cameras and without background subtraction. Our method uses a new image formation model with analytic visibility and analytically differentiable alignment energy. For reconstruction, 3D body shape is approximated as Gaussian density field. For pose and shape estimation, we minimize a new edge-based alignment energy inspired by volume raycasting in an absorbing medium. We further propose a new statistical human body model that represents the body surface, volumetric Gaussian density, as well as variability in skeleton shape. Given any multi-view sequence, our method jointly optimizes the pose and shape parameters of this model fully automatically in a spatiotemporal way.

##### Abstract (translated by Google)
无标记运动捕捉算法需要具有适当个性化的骨架尺寸和/或身体形状和外观的3D身体才能成功地跟踪人。不幸的是，许多跟踪方法认为模型个性化是一个不同的问题，并且使用手动或半自动模型初始化，这大大降低了适用性。在本文中，我们提出了一种全自动算法，它们共同创建一个通常用于动画的角色扮演者模型 - 骨架，体积形状，外观以及可选的身体表面 - 并且仅从多视图视频输入中估计参与者的动作。这种方法严格地设计用于记录非常少的相机和没有背景扣除的一般室外场景的视频。我们的方法使用具有分析可见度和分析可微性对准能量的新图像形成模型。为了重建，3D体形近似为高斯密度场。对于姿态和形状估计，我们通过在吸收介质中进行体积射线投影来最小化新的基于边缘的对准能量。我们进一步提出了一个新的统计人体模型，表示身体表面，容积高斯密度，以及骨骼形状的变化。给定任何多视图序列，我们的方法以空间的方式完全自动地优化该模型的姿态和形状参数。

##### URL
[https://arxiv.org/abs/1607.08659](https://arxiv.org/abs/1607.08659)

##### PDF
[https://arxiv.org/pdf/1607.08659](https://arxiv.org/pdf/1607.08659)

