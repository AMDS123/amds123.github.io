---
layout: post
title: "LocNet: Improving Localization Accuracy for Object Detection"
date: 2016-04-07 15:09:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference Detection
author: Spyros Gidaris, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel object localization methodology with the purpose of boosting the localization accuracy of state-of-the-art object detection systems. Our model, given a search region, aims at returning the bounding box of an object of interest inside this region. To accomplish its goal, it relies on assigning conditional probabilities to each row and column of this region, where these probabilities provide useful information regarding the location of the boundaries of the object inside the search region and allow the accurate inference of the object bounding box under a simple probabilistic framework. For implementing our localization model, we make use of a convolutional neural network architecture that is properly adapted for this task, called LocNet. We show experimentally that LocNet achieves a very significant improvement on the mAP for high IoU thresholds on PASCAL VOC2007 test set and that it can be very easily coupled with recent state-of-the-art object detection systems, helping them to boost their performance. Finally, we demonstrate that our detection approach can achieve high detection accuracy even when it is given as input a set of sliding windows, thus proving that it is independent of box proposal methods.

##### Abstract (translated by Google)
我们提出了一种新的物体定位方法，其目的是提高最先进的物体检测系统的定位精度。给定搜索区域的我们的模型旨在返回该区域内感兴趣对象的边界框。为了实现其目标，它依赖于为该区域的每一行和列分配条件概率，其中这些概率提供关于搜索区域内的对象的边界的位置的有用信息，并允许对象边界框的准确推断一个简单的概率框架。为了实现我们的本地化模型，我们利用适合于这个任务的卷积神经网络架构，称为LocNet。我们通过实验证明，LocNet在PASCAL VOC2007测试装置的高IoU阈值上可以实现非常显着的改进，并且可以很容易地与最新的最先进的物体检测系统耦合，帮助他们提高性能。最后，我们证明我们的检测方法即使在输入一组滑动窗口的情况下也能获得较高的检测精度，从而证明它独立于方框提议方法。

##### URL
[https://arxiv.org/abs/1511.07763](https://arxiv.org/abs/1511.07763)

##### PDF
[https://arxiv.org/pdf/1511.07763](https://arxiv.org/pdf/1511.07763)

