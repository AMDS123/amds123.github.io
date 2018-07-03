---
layout: post
title: "Self-supervised Sparse-to-Dense: Self-supervised Depth Completion from LiDAR and Monocular Camera"
date: 2018-07-01 06:02:48
categories: arXiv_AI
tags: arXiv_AI Sparse Face
author: Fangchang Ma, Guilherme Venturelli Cavalheiro, Sertac Karaman
mathjax: true
---

* content
{:toc}

##### Abstract
Depth completion, the technique of estimating a dense depth image from sparse depth measurements, has a variety of applications in robotics and autonomous driving. However, depth completion faces 3 main challenges: the irregularly spaced pattern in the sparse depth input, the difficulty in handling multiple sensor modalities (when color images are available), as well as the lack of dense, pixel-level ground truth depth labels. In this work, we address all these challenges. Specifically, we develop a deep regression model to learn a direct mapping from sparse depth (and color images) to dense depth. We also propose a self-supervised training framework that requires only sequences of color and sparse depth images, without the need for dense depth labels. Our experiments demonstrate that our network, when trained with semi-dense annotations, attains state-of-the- art accuracy and is the winning approach on the KITTI depth completion benchmark at the time of submission. Furthermore, the self-supervised framework outperforms a number of existing solutions trained with semi- dense annotations.

##### Abstract (translated by Google)
深度完成是从稀疏深度测量估计密集深度图像的技术，在机器人和自动驾驶中具有多种应用。然而，深度完成面临三个主要挑战：稀疏深度输入中的不规则间隔图案，处理多个传感器模态的困难（当彩色图像可用时），以及缺少密集的像素级地面实况深度标签。在这项工作中，我们解决了所有这些挑战。具体来说，我们开发了一个深度回归模型来学习从稀疏深度（和彩色图像）到密集深度的直接映射。我们还提出了一种自我监督的训练框架，它只需要一系列颜色和稀疏深度图像，而不需要密集的深度标签。我们的实验表明，我们的网络在使用半密集注释进行培训时，可以获得最先进的准确度，并且在提交时是KITTI深度完成基准测试的获胜方法。此外，自我监督的框架优于使用半密集注释训练的许多现有解决方案。

##### URL
[http://arxiv.org/abs/1807.00275](http://arxiv.org/abs/1807.00275)

##### PDF
[http://arxiv.org/pdf/1807.00275](http://arxiv.org/pdf/1807.00275)

