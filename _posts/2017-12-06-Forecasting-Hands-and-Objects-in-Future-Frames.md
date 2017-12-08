---
layout: post
title: "Forecasting Hands and Objects in Future Frames"
date: 2017-12-06 23:37:51
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
本文提出了一种预测未来人类手和物体的存在和位置的方法。给定图像帧，目标是预测将来帧（例如，5秒后）将出现哪些对象以及它们将在何处出现，即使在当前帧中不可见时。关键的思想是：（1）卷积对象识别模型的中间表示抽象其帧中的场景信息，并且（2）可以基于当前帧的表示来预测（即回归）与未来帧对应的表示。我们通过扩展最先进的卷积物体检测网络，设计了一种新的视频流二维卷积神经网络（CNN）体系结构，并提出了一种新的全卷积回归网络来预测未来的场景表示。我们的实验证实，将回归的未来表示与我们的检测网络相结合，可以可靠地估计未来的视频中的手和物体。与公共数据集上最先进的未来对象存在预测方法相比，我们获得了更高的准确性。

##### URL
[http://arxiv.org/abs/1705.07328](http://arxiv.org/abs/1705.07328)

##### PDF
[http://arxiv.org/pdf/1705.07328](http://arxiv.org/pdf/1705.07328)

