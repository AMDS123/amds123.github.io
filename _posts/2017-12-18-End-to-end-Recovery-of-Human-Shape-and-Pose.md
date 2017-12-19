---
layout: post
title: "End-to-end Recovery of Human Shape and Pose"
date: 2017-12-18 18:57:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Detection
author: Angjoo Kanazawa, Michael J. Black, David W. Jacobs, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
We describe Human Mesh Recovery (HMR), an end-to-end framework for reconstructing a full 3D mesh of a human body from a single RGB image. In contrast to most current methods that compute 2D or 3D joint locations, we produce a richer and more useful mesh representation that is parameterized by shape and 3D joint angles. The main objective is to minimize the reprojection loss of keypoints, which allow our model to be trained using in-the-wild images that only have ground truth 2D annotations. However, reprojection loss alone is highly under constrained. In this work we address this problem by introducing an adversary trained to tell whether a human body parameter is real or not using a large database of 3D human meshes. We show that HMR can be trained with and without using any coupled 2D-to-3D supervision. We do not rely on intermediate 2D keypoint detection and infer 3D pose and shape parameters directly from image pixels. Our model runs in real-time given a bounding box containing the person. We demonstrate our approach on various images in-the-wild and out-perform previous optimizationbased methods that output 3D meshes and show competitive results on tasks such as 3D joint location estimation and part segmentation.

##### Abstract (translated by Google)
我们描述人类网格恢复（HMR），一个端到端的框架，用于从单个RGB图像重建人体的全3D网格。与目前大多数计算二维或三维关节位置的方法相反，我们生成一个更丰富和更有用的网格表示，通过形状和三维关节角度进行参数化。主要目标是最大限度地减少关键点的投影丢失，这使得我们的模型可以使用仅具有地面真实2D注释的野外图像进行训练。但是，单是投资损失高度受到限制。在这项工作中，我们通过引入一个对手来解决这个问题，训练的对手用人造三维网格的大型数据库来判断人体参数是否真实。我们表明，HMR可以训练有和没有使用任何耦合2D到3D监督。我们不依赖中间二维关键点检测，并直接从图像像素推断三维姿态和形状参数。我们的模型实时运行给定一个包含该人的边界框。我们展示了我们的方法在各种图像在野外和执行以前基于优化的方法，输出三维网格和显示任务，如三维联合位置估计和零件分割的竞争结果。

##### URL
[http://arxiv.org/abs/1712.06584](http://arxiv.org/abs/1712.06584)

##### PDF
[http://arxiv.org/pdf/1712.06584](http://arxiv.org/pdf/1712.06584)

