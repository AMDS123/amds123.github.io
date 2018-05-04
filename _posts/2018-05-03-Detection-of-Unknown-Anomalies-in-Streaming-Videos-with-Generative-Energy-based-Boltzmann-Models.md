---
layout: post
title: "Detection of Unknown Anomalies in Streaming Videos with Generative Energy-based Boltzmann Models"
date: 2018-05-03 02:47:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Represenation_Learning Detection
author: Hung Vu, Tu Dinh Nguyen, Dinh Phung
mathjax: true
---

* content
{:toc}

##### Abstract
Abnormal event detection is one of the important objectives in research and practical applications of video surveillance. However, there are still three challenging problems for most anomaly detection systems in practical setting: limited labeled data, ambiguous definition of "abnormal" and expensive feature engineering steps. This paper introduces a unified detection framework to handle these challenges using energy-based models, which are powerful tools for unsupervised representation learning. Our proposed models are firstly trained on unlabeled raw pixels of image frames from an input video rather than hand-crafted visual features; and then identify the locations of abnormal objects based on the errors between the input video and its reconstruction produced by the models. To handle video stream, we develop an online version of our framework, wherein the model parameters are updated incrementally with the image frames arriving on the fly. Our experiments show that our detectors, using Restricted Boltzmann Machines (RBMs) and Deep Boltzmann Machines (DBMs) as core modules, achieve superior anomaly detection performance to unsupervised baselines and obtain accuracy comparable with the state-of-the-art approaches when evaluating at the pixel-level. More importantly, we discover that our system trained with DBMs is able to simultaneously perform scene clustering and scene reconstruction. This capacity not only distinguishes our method from other existing detectors but also offers a unique tool to investigate and understand how the model works.

##### Abstract (translated by Google)
异常事件检测是视频监控研究和实际应用的重要目标之一。然而，在实际环境中，大多数异常检测系统仍然存在三个具有挑战性的问题：有限的标记数据，“异常”的模糊定义和昂贵的特征工程步骤。本文介绍了一个统一的检测框架，以处理这些挑战使用能源模型，这是非监督表示学习的强大工具。我们提出的模型首先在输入视频的图像帧的未标记原始像素上进行训练，而不是手工制作的视觉特征;然后基于模型产生的输入视频与其重建之间的误差来识别异常对象的位置。为了处理视频流，我们开发了我们的框架的在线版本，其中模型参数随着图像帧实时到达而递增地更新。我们的实验表明，我们的探测器使用受限玻尔兹曼机器（RBMs）和深玻尔兹曼机器（DBMs）作为核心模块，可在无监督基线上实现卓越的异常检测性能，并获得与当前评估方法像素级。更重要的是，我们发现使用DBM训练的系统能够同时执行场景聚类和场景重建。这种能力不仅将我们的方法与其他现有的探测器区分开来，而且还提供了一种独特的工具来调查和理解模型如何工作。

##### URL
[http://arxiv.org/abs/1805.01090](http://arxiv.org/abs/1805.01090)

##### PDF
[http://arxiv.org/pdf/1805.01090](http://arxiv.org/pdf/1805.01090)

