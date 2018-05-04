---
layout: post
title: "Real-Time Human Detection as an Edge Service Enabled by a Lightweight CNN"
date: 2018-04-24 22:02:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Prediction Detection Recognition
author: Seyed Yahya Nikouei, Yu Chen, Sejun Song, Ronghua Xu, Baek-Young Choi, Timothy R. Faughnan
mathjax: true
---

* content
{:toc}

##### Abstract
Edge computing allows more computing tasks to take place on the decentralized nodes at the edge of networks. Today many delay sensitive, mission-critical applications can leverage these edge devices to reduce the time delay or even to enable real time, online decision making thanks to their onsite presence. Human objects detection, behavior recognition and prediction in smart surveillance fall into that category, where a transition of a huge volume of video streaming data can take valuable time and place heavy pressure on communication networks. It is widely recognized that video processing and object detection are computing intensive and too expensive to be handled by resource limited edge devices. Inspired by the depthwise separable convolution and Single Shot Multi-Box Detector (SSD), a lightweight Convolutional Neural Network (LCNN) is introduced in this paper. By narrowing down the classifier's searching space to focus on human objects in surveillance video frames, the proposed LCNN algorithm is able to detect pedestrians with an affordable computation workload to an edge device. A prototype has been implemented on an edge node (Raspberry PI 3) using openCV libraries, and satisfactory performance is achieved using real world surveillance video streams. The experimental study has validated the design of LCNN and shown it is a promising approach to computing intensive applications at the edge.

##### Abstract (translated by Google)
边缘计算允许更多计算任务在网络边缘的分布式节点上发生。今天，许多对延迟敏感的任务关键型应用程序可以利用这些边缘设备来缩短时间延迟，甚至可以通过现场存在实现实时的在线决策。智能监控中的人体检测，行为识别和预测属于这一类别，在这种情况下，大量视频流数据的转换会花费宝贵的时间，并给通信网络带来沉重的压力。人们普遍认为，视频处理和对象检测是计算密集型且太昂贵而无法由资源有限的边缘设备来处理。受深度可分卷积和单发多盒检测器（SSD）的启发，本文介绍了一种轻量级卷积神经网络（LCNN）。通过缩小分类器的搜索空间以专注于监控视频帧中的人体对象，所提出的LCNN算法能够以对于边缘设备的负担得起的计算工作量来检测行人。原型已经在使用openCV库的边缘节点（Raspberry PI 3）上实现，使用真实世界的监控视频流可以获得令人满意的性能。实验研究验证了LCNN的设计，并表明它是在边缘计算密集型应用的有前景的方法。

##### URL
[https://arxiv.org/abs/1805.00330](https://arxiv.org/abs/1805.00330)

##### PDF
[https://arxiv.org/pdf/1805.00330](https://arxiv.org/pdf/1805.00330)

