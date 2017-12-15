---
layout: post
title: "VolumeDeform: Real-time Volumetric Non-rigid Reconstruction"
date: 2016-07-30 06:07:24
categories: arXiv_CV
tags: arXiv_CV Sparse Face Tracking Optimization
author: Matthias Innmann, Michael Zollhöfer, Matthias Nießner, Christian Theobalt, Marc Stamminger
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach for the reconstruction of dynamic geometric shapes using a single hand-held consumer-grade RGB-D sensor at real-time rates. Our method does not require a pre-defined shape template to start with and builds up the scene model from scratch during the scanning process. Geometry and motion are parameterized in a unified manner by a volumetric representation that encodes a distance field of the surface geometry as well as the non-rigid space deformation. Motion tracking is based on a set of extracted sparse color features in combination with a dense depth-based constraint formulation. This enables accurate tracking and drastically reduces drift inherent to standard model-to-depth alignment. We cast finding the optimal deformation of space as a non-linear regularized variational optimization problem by enforcing local smoothness and proximity to the input constraints. The problem is tackled in real-time at the camera's capture rate using a data-parallel flip-flop optimization strategy. Our results demonstrate robust tracking even for fast motion and scenes that lack geometric features.

##### Abstract (translated by Google)
我们提出了一个新颖的方法来重建动态几何形状，使用一个手持式消费级RGB-D传感器实时费率。我们的方法不需要预定义的形状模板，在扫描过程中从头开始构建场景模型。几何和运动通过一个统一的方式进行参数化，该体积表示编码表面几何的距离场以及非刚性空间变形。运动跟踪是基于一组提取的稀疏颜色特征，结合密集的基于深度的约束公式。这可以实现准确的跟踪，并大幅度降低标准模型到深度对齐的固有漂移。我们通过强化局部平滑性和接近输入约束来发现空间的最优变形作为非线性正则化变分优化问题。使用数据并行触发器优化策略，相机捕捉速率实时解决问题。即使对于缺少几何特征的快速运动和场景，

##### URL
[https://arxiv.org/abs/1603.08161](https://arxiv.org/abs/1603.08161)

##### PDF
[https://arxiv.org/pdf/1603.08161](https://arxiv.org/pdf/1603.08161)

