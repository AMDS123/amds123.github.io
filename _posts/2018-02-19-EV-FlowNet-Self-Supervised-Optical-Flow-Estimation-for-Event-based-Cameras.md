---
layout: post
title: "EV-FlowNet: Self-Supervised Optical Flow Estimation for Event-based Cameras"
date: 2018-02-19 22:47:52
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Alex Zihao Zhu, Liangzhe Yuan, Kenneth Chaney, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
Event-based cameras have shown great promise in a variety of situations where frame based cameras suffer, such as high speed motions and high dynamic range scenes. However, developing algorithms for event measurements requires a new class of hand crafted algorithms. Deep learning has shown great success in providing model free solutions to many problems in the vision community, but existing networks have been developed with frame based images in mind, and there does not exist the wealth of labeled data for events as there does for images for supervised training. To these points, we present EV-FlowNet, a novel self-supervised deep learning pipeline for optical flow estimation for event based cameras. In particular, we introduce an image based representation of a given event stream, which is fed into a self-supervised neural network as the sole input. The corresponding grayscale images captured from the same camera at the same time as the events are then used as a supervisory signal to provide a loss function at training time, given the estimated flow from the network. We show that the resulting network is able to accurately predict optical flow from events only in a variety of different scenes, with performance competitive to image based networks. This method not only allows for accurate estimation of dense optical flow, but also provides a framework for the transfer of other self-supervised methods to the event-based domain.

##### Abstract (translated by Google)
基于事件的摄像机已经在基于帧的摄像机受到影响的各种情况下显示出巨大的前景，例如高速运动和高动态范围场景。但是，为事件测量开发算法需要一类新的手工算法。深度学习在为视觉社区中的许多问题提供无模型解决方案方面取得了巨大成功，但现有网络已开发出基于帧的图像，并且不存在事件的标记数据的丰富性，监督培训。为此，我们推出EV-FlowNet，一种新型自监督深度学习管道，用于基于事件的相机的光流估计。特别是，我们引入了一个给定事件流的基于图像的表示，它被馈送到自我监督的神经网络中作为唯一的输入。考虑到来自网络的估计流量，在事件同时从同一摄像机捕获的对应灰度图像随后用作监督信号以在训练时间提供丢失功能。我们表明，由此产生的网络能够准确地预测来自仅在各种不同场景中的事件的光流，并且具有与基于图像的网络相竞争的性能。这种方法不仅可以准确估计密集的光流，而且还可以为其他自我监督方法向基于事件的领域转移提供一个框架。

##### URL
[http://arxiv.org/abs/1802.06898](http://arxiv.org/abs/1802.06898)

##### PDF
[http://arxiv.org/pdf/1802.06898](http://arxiv.org/pdf/1802.06898)

