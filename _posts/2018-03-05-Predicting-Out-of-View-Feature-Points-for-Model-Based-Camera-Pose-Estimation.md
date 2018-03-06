---
layout: post
title: "Predicting Out-of-View Feature Points for Model-Based Camera Pose Estimation"
date: 2018-03-05 10:03:17
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Deep_Learning Prediction
author: Oliver Moolan-Feroze, Andrew Calway
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a novel framework that uses deep learning to predict object feature points that are out-of-view in the input image. This system was developed with the application of model-based tracking in mind, particularly in the case of autonomous inspection robots, where only partial views of the object are available. Out-of-view prediction is enabled by applying scaling to the feature point labels during network training. This is combined with a recurrent neural network architecture designed to provide the final prediction layers with rich feature information from across the spatial extent of the input image. To show the versatility of these out-of-view predictions, we describe how to integrate them in both a particle filter tracker and an optimisation based tracker. To evaluate our work we compared our framework with one that predicts only points inside the image. We show that as the amount of the object in view decreases, being able to predict outside the image bounds adds robustness to the final pose estimation.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新颖的框架，它使用深度学习来预测输入图像中的视点外的对象特征点。该系统是在考虑到基于模型的跟踪的情况下开发的，特别是在自动检测机器人的情况下，只有局部视图可用。通过在网络训练期间对特征点标签应用缩放来启用视野外预测。这与经常性的神经网络架构相结合，旨在为输入图像的空间范围提供具有丰富特征信息的最终预测层。为了展示这些视野预测的多功能性，我们描述如何将它们集成到粒子滤波跟踪器和基于优化的跟踪器中。为了评估我们的工作，我们将我们的框架与只预测图像内部点的框架进行了比较。我们表明，随着视图中物体的数量减少，能够在图像边界外进行预测，从而增加了对最终姿态估计的鲁棒性。

##### URL
[http://arxiv.org/abs/1803.01577](http://arxiv.org/abs/1803.01577)

##### PDF
[http://arxiv.org/pdf/1803.01577](http://arxiv.org/pdf/1803.01577)

