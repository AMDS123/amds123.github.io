---
layout: post
title: "R-CRNN: Region-based Convolutional Recurrent Neural Network for Audio Event Detection"
date: 2018-08-20 18:01:52
categories: arXiv_SD
tags: arXiv_SD Object_Detection Knowledge CNN RNN Classification Prediction Detection
author: Chieh-Chi Kao, Weiran Wang, Ming Sun, Chao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a Region-based Convolutional Recurrent Neural Network (R-CRNN) for audio event detection (AED). The proposed network is inspired by Faster-RCNN, a well known region-based convolutional network framework for visual object detection. Different from the original Faster-RCNN, a recurrent layer is added on top of the convolutional network to capture the long-term temporal context from the extracted high level features. While most of the previous works on AED generate predictions at frame level first, and then use post-processing to predict the onset/offset timestamps of events from a probability sequence; the proposed method generates predictions at event level directly and can be trained end-to-end with a multitask loss, which optimizes the classification and localization of audio events simultaneously. The proposed method is tested on DCASE 2017 Challenge dataset. To the best of our knowledge, R-CRNN is the best performing single-model method among all methods without using ensembles both on development and evaluation sets. Compared to the other region-based network for AED (R-FCN) with an event-based error rate (ER) of 0.18 on the development set, our method reduced the ER to half.

##### Abstract (translated by Google)
本文提出了一种基于区域的卷积递归神经网络（R-CRNN），用于音频事件检测（AED）。拟议的网络受到Faster-RCNN的启发，这是一个众所周知的基于区域的卷积网络框架，用于视觉对象检测。与原始的Faster-RCNN不同，在卷积网络的顶部添加循环层以从提取的高级特征捕获长期时间上下文。虽然之前关于AED的大部分工作首先在帧级生成预测，然后使用后处理来预测概率序列中事件的起始/偏移时间戳;所提出的方法直接在事件级别生成预测，并且可以通过多任务丢失进行端到端训练，从而同时优化音频事件的分类和定位。提出的方法在DCASE 2017 Challenge数据集上进行测试。据我们所知，R-CRNN是所有方法中性能最佳的单模型方法，无需在开发和评估集上使用集合。与用于AED（R-FCN）的其他基于区域的网络相比，在开发集合上基于事件的错误率（ER）为0.18，我们的方法将ER减少到一半。

##### URL
[http://arxiv.org/abs/1808.06627](http://arxiv.org/abs/1808.06627)

##### PDF
[http://arxiv.org/pdf/1808.06627](http://arxiv.org/pdf/1808.06627)

