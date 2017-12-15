---
layout: post
title: "Fully-Convolutional Siamese Networks for Object Tracking"
date: 2016-09-14 11:48:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Object_Tracking Detection Gradient_Descent
author: Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of arbitrary object tracking has traditionally been tackled by learning a model of the object's appearance exclusively online, using as sole training data the video itself. Despite the success of these methods, their online-only approach inherently limits the richness of the model they can learn. Recently, several attempts have been made to exploit the expressive power of deep convolutional networks. However, when the object to track is not known beforehand, it is necessary to perform Stochastic Gradient Descent online to adapt the weights of the network, severely compromising the speed of the system. In this paper we equip a basic tracking algorithm with a novel fully-convolutional Siamese network trained end-to-end on the ILSVRC15 dataset for object detection in video. Our tracker operates at frame-rates beyond real-time and, despite its extreme simplicity, achieves state-of-the-art performance in multiple benchmarks.

##### Abstract (translated by Google)
传统上，任意对象跟踪的问题是通过仅仅在线地学习对象外观的模型来解决，使用视频本身作为唯一的训练数据。尽管这些方法取得了成功，但是他们的在线方法本质上限制了他们可以学习的模型的丰富性。最近，人们已经进行了一些尝试来利用深度卷积网络的表达能力。但是，如果事先不知道要跟踪的对象，则需要在线执行随机梯度下降来适应网络的权重，严重影响系统的速度。在本文中，我们配备了一个基本的跟踪算法，在ILSVRC15数据集上进行端到端的全卷积连体网络的训练，用于视频中的目标检测。我们的跟踪器以超过实时的帧率运行，尽管其极其简单，却能够在多个基准测试中实现最高水平的性能。

##### URL
[https://arxiv.org/abs/1606.09549](https://arxiv.org/abs/1606.09549)

##### PDF
[https://arxiv.org/pdf/1606.09549](https://arxiv.org/pdf/1606.09549)

