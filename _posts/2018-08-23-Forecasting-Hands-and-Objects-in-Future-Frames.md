---
layout: post
title: "Forecasting Hands and Objects in Future Frames"
date: 2018-08-23 04:17:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Recognition
author: Chenyou Fan, Jangwon Lee, Michael S. Ryoo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an approach to forecast future presence and location of human hands and objects. Given an image frame, the goal is to predict what objects will appear in the future frame (e.g., 5 seconds later) and where they will be located at, even when they are not visible in the current frame. The key idea is that (1) an intermediate representation of a convolutional object recognition model abstracts scene information in its frame and that (2) we can predict (i.e., regress) such representations corresponding to the future frames based on that of the current frame. We design a new two-stream convolutional neural network (CNN) architecture for videos by extending the state-of-the-art convolutional object detection network, and present a new fully convolutional regression network for predicting future scene representations. Our experiments confirm that combining the regressed future representation with our detection network allows reliable estimation of future hands and objects in videos. We obtain much higher accuracy compared to the state-of-the-art future object presence forecast method on a public dataset.

##### Abstract (translated by Google)
本文介绍了一种预测人类手和物体未来存在和位置的方法。给定图像帧，目标是预测哪些对象将出现在未来帧中（例如，5秒后）以及它们将位于何处，即使它们在当前帧中不可见。关键思想是（1）卷积对象识别模型的中间表示在其帧中抽象场景信息，并且（2）我们可以基于当前帧的帧对应于未来帧来预测（即，回归）这样的表示。 。我们通过扩展最先进的卷积对象检测网络，为视频设计了一种新的双流卷积神经网络（CNN）架构，并提出了一种新的完全卷积回归网络，用于预测未来的场景表示。我们的实验证实，将回归的未来表示与我们的检测网络相结合，可以可靠地估计视频中未来的手和对象。与公共数据集上最先进的未来对象存在预测方法相比，我们获得了更高的准确性。

##### URL
[http://arxiv.org/abs/1705.07328](http://arxiv.org/abs/1705.07328)

##### PDF
[http://arxiv.org/pdf/1705.07328](http://arxiv.org/pdf/1705.07328)

