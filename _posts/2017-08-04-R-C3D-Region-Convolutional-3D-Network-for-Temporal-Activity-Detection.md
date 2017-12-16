---
layout: post
title: "R-C3D: Region Convolutional 3D Network for Temporal Activity Detection"
date: 2017-08-04 22:37:54
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Huijuan Xu, Abir Das, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of activity detection in continuous, untrimmed video streams. This is a difficult task that requires extracting meaningful spatio-temporal features to capture activities, accurately localizing the start and end times of each activity. We introduce a new model, Region Convolutional 3D Network (R-C3D), which encodes the video streams using a three-dimensional fully convolutional network, then generates candidate temporal regions containing activities, and finally classifies selected regions into specific activities. Computation is saved due to the sharing of convolutional features between the proposal and the classification pipelines. The entire model is trained end-to-end with jointly optimized localization and classification losses. R-C3D is faster than existing methods (569 frames per second on a single Titan X Maxwell GPU) and achieves state-of-the-art results on THUMOS'14. We further demonstrate that our model is a general activity detection framework that does not rely on assumptions about particular dataset properties by evaluating our approach on ActivityNet and Charades. Our code is available at this http URL

##### Abstract (translated by Google)
我们解决连续的，未修剪的视频流中的活动检测问题。这是一项艰巨的任务，需要提取有意义的时空特征来捕捉活动，准确定位每个活动的开始和结束时间。我们引入了一个新的模型，即区域卷积三维网络（R-C3D），它使用三维完全卷积网络对视频流进行编码，然后生成包含活动的候选时间区域，最后将选定区域分类为特定活动。由于提案和分类流水线之间的卷积特性的共享，节省了计算。整个模型是端对端训练，共同优化了定位和分类损失。 R-C3D比现有方法（单个Titan X Maxwell GPU上的每秒569帧）更快，并在THUMOS'14上实现了最新的结果。我们进一步证明，我们的模型是一个通用的活动检测框架，通过评估我们在ActivityNet和Charades上的方法，不依赖于关于特定数据集属性的假设。我们的代码在这个http URL中可用

##### URL
[https://arxiv.org/abs/1703.07814](https://arxiv.org/abs/1703.07814)

##### PDF
[https://arxiv.org/pdf/1703.07814](https://arxiv.org/pdf/1703.07814)

