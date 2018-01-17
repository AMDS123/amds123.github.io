---
layout: post
title: "Detecting abnormal events in video using Narrowed Motion Clusters"
date: 2018-01-12 10:57:08
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Radu Tudor Ionescu, Sorina Smeureanu, Marius Popescu, Bogdan Alexe
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate the abnormal event detection problem as an outlier detection task and we propose a two-stage algorithm based on k-means clustering and one-class Support Vector Machines (SVM) to eliminate outliers. After extracting motion features from the training video containing only normal events, we apply k-means clustering to find clusters representing different types of motion. In the first stage, we consider that clusters with fewer samples (with respect to a given threshold) contain only outliers and we eliminate these clusters altogether. In the second stage, we shrink the borders of the remaining clusters by training a one-class SVM model on each cluster. To detected abnormal events in the test video, we analyze each test sample and consider its maximum normality score provided by the trained one-class SVM models, based on the intuition that a test sample can belong to only one cluster of normal motion. If the test sample does not fit well in any narrowed cluster, than it is labeled as abnormal. We also combine our approach based on motion features with a recent approach based on deep appearance features extracted with pre-trained convolutional neural networks (CNN). We combine our two-stage algorithm with the deep framework using a late fusion strategy, keeping the pipelines of the two approaches independent. We compare our method with several state-of-the-art supervised and unsupervised methods on four benchmark data sets. The empirical results indicate that our abnormal event detection framework can achieve better results in most cases, while processing the test video in real-time at 30 frames per second on CPU.

##### Abstract (translated by Google)
我们将异常事件检测问题作为异常检测任务来制定，提出了一种基于k均值聚类和一类支持向量机（SVM）的两阶段算法来消除异常值。在从仅包含正常事件的训练视频中提取运动特征之后，我们应用k均值聚类来查找表示不同类型运动的聚类。在第一阶段，我们认为具有较少样本（相对于给定阈值）的聚类只包含异常值，我们完全消除这些聚类。在第二阶段，我们通过在每个集群上训练一个类别的SVM模型来缩小剩余集群的边界。为了检测测试视频中的异常事件，我们基于直觉认为一个测试样本只能属于一个正常运动的聚类，我们分析每个测试样本并考虑由训练的一类SVM模型提供的最大正态分数。如果测试样本不适合任何缩小的群集，则会被标记为异常。我们还将基于运动特征的方法与基于用预先训练的卷积神经网络（CNN）提取的深度外观特征的最近方法相结合。我们使用后期融合策略将两阶段算法与深度框架相结合，使两种方法的流水线保持独立。我们将我们的方法与四种基准数据集上的几种最新的有监督和无监督方法进行比较。实验结果表明，在大多数情况下，我们的异常事件检测框架可以在CPU上以30帧/秒的速度实时处理测试视频。

##### URL
[http://arxiv.org/abs/1801.05030](http://arxiv.org/abs/1801.05030)

##### PDF
[http://arxiv.org/pdf/1801.05030](http://arxiv.org/pdf/1801.05030)

