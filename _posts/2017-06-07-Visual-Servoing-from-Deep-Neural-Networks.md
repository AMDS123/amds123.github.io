---
layout: post
title: "Visual Servoing from Deep Neural Networks"
date: 2017-06-07 09:26:34
categories: arXiv_CV
tags: arXiv_CV CNN
author: Quentin Bateux, Eric Marchand, Jürgen Leitner, Francois Chaumette, Peter Corke
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep neural network-based method to perform high-precision, robust and real-time 6 DOF visual servoing. The paper describes how to create a dataset simulating various perturbations (occlusions and lighting conditions) from a single real-world image of the scene. A convolutional neural network is fine-tuned using this dataset to estimate the relative pose between two images of the same scene. The output of the network is then employed in a visual servoing control scheme. The method converges robustly even in difficult real-world settings with strong lighting variations and occlusions.A positioning error of less than one millimeter is obtained in experiments with a 6 DOF robot.

##### Abstract (translated by Google)
我们提出了一个深度神经网络的方法来执行高精度，鲁棒和实时的6自由度视觉伺服。本文描述了如何创建一个数据集，从场景的单个真实世界的图像中模拟各种扰动（遮挡和光照条件）。使用这个数据集对卷积神经网络进行微调，以估计相同场景的两幅图像之间的相对姿态。网络的输出然后被用于视觉伺服控制方案中。即使在困难的现实环境中，该方法也能稳健地收敛，并具有强烈​​的光照变化和遮挡。在6自由度机器人的实验中，获得小于1毫米的定位误差。

##### URL
[https://arxiv.org/abs/1705.08940](https://arxiv.org/abs/1705.08940)

##### PDF
[https://arxiv.org/pdf/1705.08940](https://arxiv.org/pdf/1705.08940)

