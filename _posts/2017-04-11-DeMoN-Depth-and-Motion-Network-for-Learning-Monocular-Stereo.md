---
layout: post
title: "DeMoN: Depth and Motion Network for Learning Monocular Stereo"
date: 2017-04-11 09:14:10
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Benjamin Ummenhofer, Huizhong Zhou, Jonas Uhrig, Nikolaus Mayer, Eddy Ilg, Alexey Dosovitskiy, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we formulate structure from motion as a learning problem. We train a convolutional network end-to-end to compute depth and camera motion from successive, unconstrained image pairs. The architecture is composed of multiple stacked encoder-decoder networks, the core part being an iterative network that is able to improve its own predictions. The network estimates not only depth and motion, but additionally surface normals, optical flow between the images and confidence of the matching. A crucial component of the approach is a training loss based on spatial relative differences. Compared to traditional two-frame structure from motion methods, results are more accurate and more robust. In contrast to the popular depth-from-single-image networks, DeMoN learns the concept of matching and, thus, better generalizes to structures not seen during training.

##### Abstract (translated by Google)
在本文中，我们将动作结构作为一个学习问题。我们对卷积网络进行端到端的训练，从连续的，不受约束的图像对计算深度和相机运动。该架构由多个堆叠的编码器 - 解码器网络组成，核心部分是能够改进其自身预测的迭代网络。网络不仅估计深度和运动，还估计表面法线，图像之间的光流和匹配的可信度。该方法的一个重要组成部分是基于空间相对差异的训练损失。与运动方法中的传统双帧结构相比，结果更精确，更稳健。与流行的深度单图形网络相反，DeMoN学习了匹配的概念，因此更好地概括了训练期间看不到的结构。

##### URL
[https://arxiv.org/abs/1612.02401](https://arxiv.org/abs/1612.02401)

##### PDF
[https://arxiv.org/pdf/1612.02401](https://arxiv.org/pdf/1612.02401)

