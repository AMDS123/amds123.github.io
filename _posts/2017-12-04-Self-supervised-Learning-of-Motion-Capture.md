---
layout: post
title: "Self-supervised Learning of Motion Capture"
date: 2017-12-04 20:25:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Hsiao-Yu Fish Tung, Hsiao-Wei Tung, Ersin Yumer, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art solutions for motion capture from a single camera are optimization driven: they optimize the parameters of a 3D human model so that its re-projection matches measurements in the video (e.g. person segmentation, optical flow, keypoint detections etc.). Optimization models are susceptible to local minima. This has been the bottleneck that forced using clean green-screen like backgrounds at capture time, manual initialization, or switching to multiple cameras as input resource. In this work, we propose a learning based motion capture model for single camera input. Instead of optimizing mesh and skeleton parameters directly, our model optimizes neural network weights that predict 3D shape and skeleton configurations given a monocular RGB video. Our model is trained using a combination of strong supervision from synthetic data, and self-supervision from differentiable rendering of (a) skeletal keypoints, (b) dense 3D mesh motion, and (c) human-background segmentation, in an end-to-end framework. Empirically we show our model combines the best of both worlds of supervised learning and test-time optimization: supervised learning initializes the model parameters in the right regime, ensuring good pose and surface initialization at test time, without manual effort. Self-supervision by back-propagating through differentiable rendering allows (unsupervised) adaptation of the model to the test data, and offers much tighter fit than a pretrained fixed model. We show that the proposed model improves with experience and converges to low-error solutions where previous optimization methods fail.

##### Abstract (translated by Google)
当前最先进的解决方案是从单个摄像头进行运动捕捉，它们是优化驱动的：它们优化了3D人体模型的参数，使其重新投影与视频中的测量相匹配（例如人物分割，光流，关键点检测等等。）。优化模型容易受到局部最小值的影响。这一直是在捕获时间，手动初始化或切换到多个摄像机作为输入资源时强制使用像背景一样的干净绿屏的瓶颈。在这项工作中，我们提出了一个基于学习的单摄像头输入动作捕捉模型。我们的模型不是直接优化网格和骨架参数，而是通过优化神经网络权重来预测给定单目RGB视频的3D形状和骨架配置。我们的模型是通过结合合成数据的强大监督和来自（a）骨骼关键点，（b）密集的3D网格运动以及（c）人类背景分割的可微分渲染的自我监督结束框架。从经验上讲，我们展示了我们的模型结合了监督学习和测试时间优化两个方面的优点：监督式学习在正确的模式下初始化模型参数，确保在测试时进行良好的姿态和表面初始化，而无需手动操作。通过可微分渲染进行的反向传播的自我监视允许（无监督地）使模型适应测试数据，并且比预训练的固定模型提供更严格的适应性。我们表明，提出的模型随着经验的提高而改进，并收敛到先前优化方法失败的低错误解决方案。

##### URL
[http://arxiv.org/abs/1712.01337](http://arxiv.org/abs/1712.01337)

