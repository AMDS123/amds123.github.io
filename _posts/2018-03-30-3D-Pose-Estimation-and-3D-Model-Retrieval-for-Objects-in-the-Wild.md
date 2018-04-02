---
layout: post
title: "3D Pose Estimation and 3D Model Retrieval for Objects in the Wild"
date: 2018-03-30 14:47:49
categories: arXiv_AI
tags: arXiv_AI Pose_Estimation Quantitative
author: Alexander Grabner, Peter M. Roth, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a scalable, efficient and accurate approach to retrieve 3D models for objects in the wild. Our contribution is twofold. We first present a 3D pose estimation approach for object categories which significantly outperforms the state-of-the-art on Pascal3D+. Second, we use the estimated pose as a prior to retrieve 3D models which accurately represent the geometry of objects in RGB images. For this purpose, we render depth images from 3D models under our predicted pose and match learned image descriptors of RGB images against those of rendered depth images using a CNN-based multi-view metric learning approach. In this way, we are the first to report quantitative results for 3D model retrieval on Pascal3D+, where our method chooses the same models as human annotators for 50% of the validation images on average. In addition, we show that our method, which was trained purely on Pascal3D+, retrieves rich and accurate 3D models from ShapeNet given RGB images of objects in the wild.

##### Abstract (translated by Google)
我们提出了一种可扩展，高效且准确的方法来检索野外物体的3D模型。我们的贡献是双重的。我们首先提出了一种针对对象类别的三维姿态估计方法，该方法明显优于Pascal3D +中的最新技术。其次，我们使用估计的姿态作为先验来检索3D模型，其准确地表示RGB图像中的对象的几何形状。为此，我们在我们的预测姿态下渲染来自3D模型的深度图像，并使用基于CNN的多视图度量学习方法将RGB图像的学习图像描述符与渲染的深度图像的匹配。通过这种方式，我们率先在Pascal3D +上报告三维模型检索的定量结果，其中我们的方法平均选择与人类注释器相同的模型作为验证图像的50％。另外，我们证明我们的方法纯粹是在Pascal3D +上进行训练，通过ShapeNet从野外物体的RGB图像中检索丰富而准确的3D模型。

##### URL
[https://arxiv.org/abs/1803.11493](https://arxiv.org/abs/1803.11493)

##### PDF
[https://arxiv.org/pdf/1803.11493](https://arxiv.org/pdf/1803.11493)

