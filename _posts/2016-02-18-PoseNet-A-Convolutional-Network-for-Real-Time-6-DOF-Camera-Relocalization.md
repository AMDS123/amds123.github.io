---
layout: post
title: "PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization"
date: 2016-02-18 13:52:18
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification
author: Alex Kendall, Matthew Grimes, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a robust and real-time monocular six degree of freedom relocalization system. Our system trains a convolutional neural network to regress the 6-DOF camera pose from a single RGB image in an end-to-end manner with no need of additional engineering or graph optimisation. The algorithm can operate indoors and outdoors in real time, taking 5ms per frame to compute. It obtains approximately 2m and 6 degree accuracy for large scale outdoor scenes and 0.5m and 10 degree accuracy indoors. This is achieved using an efficient 23 layer deep convnet, demonstrating that convnets can be used to solve complicated out of image plane regression problems. This was made possible by leveraging transfer learning from large scale classification data. We show the convnet localizes from high level features and is robust to difficult lighting, motion blur and different camera intrinsics where point based SIFT registration fails. Furthermore we show how the pose feature that is produced generalizes to other scenes allowing us to regress pose with only a few dozen training examples. PoseNet code, dataset and an online demonstration is available on our project webpage, at this http URL

##### Abstract (translated by Google)
我们提出了一个强大的实时单目六自由度重定位系统。我们的系统训练卷积神经网络，从一个单一的RGB图像以一种端到端的方式来回归六自由度摄像机姿态，而不需要额外的工程或图形优化。该算法可以实时室内外运行，每帧5ms计算。对于大型户外场景，室内可获得约2米和6度精度，0.5米和10度精度。这是通过使用高效的23层深度的小圆点来实现的，表明可以使用小圆点来解决复杂的图像平面回归问题。这是通过利用大规模分类数据的转移学习来实现的。我们展示的convnet从高层次的特点本地化，是强大的困难的照明，运动模糊和不同的摄像机内部基于点的SIFT注册失败。此外，我们展示了如何产生的姿态特征推广到其他场景，使我们只有几十个训练例子退步姿势。 PoseNet代码，数据集和在线演示可以在我们的项目网页上的这个http URL中找到

##### URL
[https://arxiv.org/abs/1505.07427](https://arxiv.org/abs/1505.07427)

##### PDF
[https://arxiv.org/pdf/1505.07427](https://arxiv.org/pdf/1505.07427)

