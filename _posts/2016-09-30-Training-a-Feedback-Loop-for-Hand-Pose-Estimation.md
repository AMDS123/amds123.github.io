---
layout: post
title: "Training a Feedback Loop for Hand Pose Estimation"
date: 2016-09-30 12:35:26
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Markus Oberweger, Paul Wohlhart, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an entirely data-driven approach to estimating the 3D pose of a hand given a depth image. We show that we can correct the mistakes made by a Convolutional Neural Network trained to predict an estimate of the 3D pose by using a feedback loop. The components of this feedback loop are also Deep Networks, optimized using training data. They remove the need for fitting a 3D model to the input data, which requires both a carefully designed fitting function and algorithm. We show that our approach outperforms state-of-the-art methods, and is efficient as our implementation runs at over 400 fps on a single GPU.

##### Abstract (translated by Google)
我们提出一个完全数据驱动的方法来估计给定深度图像的手的三维姿态。我们表明，我们可以纠正一个卷积神经网络所犯的错误，通过使用一个反馈环来预测3D姿态的估计。这个反馈环路的组成部分也是深度网络，使用训练数据进行优化。它们消除了将3D模型拟合到输入数据的需要，这需要精心设计的拟合函数和算法。我们展示了我们的方法胜过了最先进的方法，并且效率很高，因为我们的实现在单GPU上以每秒400帧的速度运行。

##### URL
[https://arxiv.org/abs/1609.09698](https://arxiv.org/abs/1609.09698)

##### PDF
[https://arxiv.org/pdf/1609.09698](https://arxiv.org/pdf/1609.09698)

