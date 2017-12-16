---
layout: post
title: "Hierarchical Siamese Network for Thermal Infrared Object Tracking"
date: 2017-11-27 05:15:59
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Classification Prediction Detection
author: Qiao Liu, Zhenyu He, Hongzhi Wang, Xin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Most thermal infrared (TIR) tracking methods are discriminative, which treat the tracking problem as a classification task. However, the objective of the classifier (label prediction) is not coupled to the objective of the tracker (location estimation). The classification task focuses on the between-class difference of the arbitrary objects, while the tracking task mainly deals with the within-class difference of the same objects. In this paper, we cast the TIR tracking problem as a similarity verification task, which is well coupled to the objective of tracking task. We propose a TIR tracker via a hierarchical Siamese convolutional neural network (CNN), named HSNet. To obtain both spatial and semantic features of the TIR object, we design a Siamese CNN coalescing the multiple hierarchical convolutional layers. Then, we train this network end to end on a large visible video detection dataset to learn the similarity between paired objects before we transfer the network into the TIR domain. Next, this pre-trained Siamese network is used to evaluate the similarity between the target template and target candidates. Finally, we locate the most similar one as the tracked target. Extensive experimental results on the benchmarks: VOT-TIR 2015 and VOT-TIR 2016, show that our proposed method achieves favorable performance against the state-of-the-art methods.

##### Abstract (translated by Google)
大多数热红外（TIR）跟踪方法是有区别的，它把跟踪问题当作分类任务。然而，分类器（标签预测）的目标与追踪器（位置估计）的目标没有耦合。分类任务的重点在于任意对象间的类间差异，而跟踪任务则主要处理同一对象的类内差异。本文将TIR跟踪问题作为一个相似性验证任务，与跟踪任务的目标相结合。我们通过分层连体卷积神经网络（CNN）提出了一个TIR追踪器，命名为HSNet。为了获得TIR对象的空间和语义特征，我们设计了一个连体CNN聚合多层次卷积层。然后，我们在一个大的可见视频检测数据集上对这个网络进行端到端的训练，以在我们将网络传输到TIR域之前，学习配对对象之间的相似性。接下来，这个预先训练的连体网络被用来评估目标模板和目标候选人之间的相似性。最后，我们找到跟踪目标最相似的一个。基准测试的广泛实验结果：VOT-TIR 2015和VOT-TIR 2016表明，我们提出的方法与最先进的方法相比取得了良好的效果。

##### URL
[https://arxiv.org/abs/1711.09539](https://arxiv.org/abs/1711.09539)

##### PDF
[https://arxiv.org/pdf/1711.09539](https://arxiv.org/pdf/1711.09539)

