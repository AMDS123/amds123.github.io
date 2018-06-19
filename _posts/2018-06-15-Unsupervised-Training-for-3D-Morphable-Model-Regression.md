---
layout: post
title: "Unsupervised Training for 3D Morphable Model Regression"
date: 2018-06-15 19:31:20
categories: arXiv_CV
tags: arXiv_CV Face Recognition
author: Kyle Genova, Forrester Cole, Aaron Maschinot, Aaron Sarna, Daniel Vlasic, William T. Freeman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for training a regression network from image pixels to 3D morphable model coordinates using only unlabeled photographs. The training loss is based on features from a facial recognition network, computed on-the-fly by rendering the predicted faces with a differentiable renderer. To make training from features feasible and avoid network fooling effects, we introduce three objectives: a batch distribution loss that encourages the output distribution to match the distribution of the morphable model, a loopback loss that ensures the network can correctly reinterpret its own output, and a multi-view identity loss that compares the features of the predicted 3D face and the input photograph from multiple viewing angles. We train a regression network using these objectives, a set of unlabeled photographs, and the morphable model itself, and demonstrate state-of-the-art results.

##### Abstract (translated by Google)
我们提出了一种仅使用未标记的照片来训练从图像像素到3D形变模型坐标的回归网络的方法。训练损失基于来自面部识别网络的特征，通过使用可微分渲染器渲染预测面部而实时计算。为了使功能训练可行并避免网络愚弄效应，我们引入了三个目标：鼓励输出分布匹配形变模型分布的批量分布损失，确保网络能够正确地重新解释其自身输出的环回损耗，以及多视角识别损失，其比较预测3D脸部和来自多个视角的输入照片的特征。我们使用这些目标训练回归网络，一组未标记的照片和形变模型本身，并展示最新的结果。

##### URL
[http://arxiv.org/abs/1806.06098](http://arxiv.org/abs/1806.06098)

##### PDF
[http://arxiv.org/pdf/1806.06098](http://arxiv.org/pdf/1806.06098)

