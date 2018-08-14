---
layout: post
title: "EV-FlowNet: Self-Supervised Optical Flow Estimation for Event-based Cameras"
date: 2018-08-13 15:32:01
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
基于事件的相机在基于帧的相机遭受诸如高速运动和高动态范围场景的各种情况下表现出很大的希望。但是，开发用于事件测量的算法需要一类新的手工制作算法。深度学习在为视觉社区中的许多问题提供无模型解决方案方面取得了巨大成功，但现有网络已经开发时考虑了基于帧的图像，并且不存在大量用于事件的标记数据，因为监督培训。对于这些要点，我们提出了EV-FlowNet，一种用于基于事件的摄像机的光流估计的新型自监督深度学习管道。特别地，我们引入了给定事件流的基于图像的表示，其被馈送到作为唯一输入的自监督神经网络。然后，在给定来自网络的估计流量的情况下，将与事件同时从相同相机捕获的相应灰度图像用作监控信号，以在训练时提供损失函数。我们表明，由此产生的网络能够准确地预测仅在各种不同场景中的事件的光流，其性能与基于图像的网络相竞争。该方法不仅允许精确估计密集光流，而且还提供了将其他自监督方法转移到基于事件的域的框架。

##### URL
[http://arxiv.org/abs/1802.06898](http://arxiv.org/abs/1802.06898)

##### PDF
[http://arxiv.org/pdf/1802.06898](http://arxiv.org/pdf/1802.06898)

