---
layout: post
title: "Learning Human Optical Flow"
date: 2018-06-14 17:50:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Anurag Ranjan, Javier Romero, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
The optical flow of humans is well known to be useful for the analysis of human action. Given this, we devise an optical flow algorithm specifically for human motion and show that it is superior to generic flow methods. Designing a method by hand is impractical, so we develop a new training database of image sequences with ground truth optical flow. For this we use a 3D model of the human body and motion capture data to synthesize realistic flow fields. We then train a convolutional neural network to estimate human flow fields from pairs of images. Since many applications in human motion analysis depend on speed, and we anticipate mobile applications, we base our method on SpyNet with several modifications. We demonstrate that our trained network is more accurate than a wide range of top methods on held-out test data and that it generalizes well to real image sequences. When combined with a person detector/tracker, the approach provides a full solution to the problem of 2D human flow estimation. Both the code and the dataset are available for research.

##### Abstract (translated by Google)
众所周知，人类的光流对分析人类行为是有用的。鉴于此，我们设计了专门用于人体运动的光流算法，并表明它优于通用流方法。手工设计方法是不切实际的，因此我们开发了一个新的带有地面光流的图像序列训练数据库。为此，我们使用人体三维模型和运动捕捉数据来合成逼真的流场。然后，我们训练一个卷积神经网络来估计来自图像对的人流场。由于人体运动分析中的许多应用程序都依赖于速度，并且我们预计移动应用程序，所以我们的方法基于SpyNet进行了多处修改。我们证明，我们的训练网络比支持测试数据的各种顶级方法更精确，并且它能很好地适用于真实图像序列。当与人体探测器/跟踪器结合使用时，该方法为二维人体流量估算问题提供了完整的解决方案。代码和数据集都可用于研究。

##### URL
[http://arxiv.org/abs/1806.05666](http://arxiv.org/abs/1806.05666)

##### PDF
[http://arxiv.org/pdf/1806.05666](http://arxiv.org/pdf/1806.05666)

