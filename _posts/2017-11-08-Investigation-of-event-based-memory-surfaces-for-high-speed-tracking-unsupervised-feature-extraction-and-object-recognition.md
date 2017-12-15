---
layout: post
title: "Investigation of event-based memory surfaces for high-speed tracking, unsupervised feature extraction and object recognition"
date: 2017-11-08 10:39:46
categories: arXiv_CV
tags: arXiv_CV Face Tracking Classification Recognition
author: Saeed Afshar, Gregory Cohen, Tara Julia Hamilton, Jonathan Tapson, Andre van Schaik
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we compare event-based decaying and time based-decaying memory surfaces for high-speed eventbased tracking, feature extraction, and object classification using an event-based camera. The high-speed recognition task involves detecting and classifying model airplanes that are dropped free-hand close to the camera lens so as to generate a challenging dataset exhibiting significant variance in target velocity. This variance motivated the investigation of event-based decaying memory surfaces in comparison to time-based decaying memory surfaces to capture the temporal aspect of the event-based data. These surfaces are then used to perform unsupervised feature extraction, tracking and recognition. In order to generate the memory surfaces, event binning, linearly decaying kernels, and exponentially decaying kernels were investigated with exponentially decaying kernels found to perform best. Event-based decaying memory surfaces were found to outperform time-based decaying memory surfaces in recognition especially when invariance to target velocity was made a requirement. A range of network and receptive field sizes were investigated. The system achieves 98.75% recognition accuracy within 156 milliseconds of an airplane entering the field of view, using only twenty-five event-based feature extracting neurons in series with a linear classifier. By comparing the linear classifier results to an ELM classifier, we find that a small number of event-based feature extractors can effectively project the complex spatio-temporal event patterns of the dataset to an almost linearly separable representation in feature space.

##### Abstract (translated by Google)
在本文中，我们比较基于事件的衰减和基于时间的衰减内存表面，用于基于事件的高速事件跟踪，特征提取和对象分类。高速识别任务涉及检测和分类在相机镜头附近自由落下的模型飞机，以便生成具有显着的目标速度变化的具有挑战性的数据集。与基于时间的衰减记忆表面相比，这种变化激发了基于事件的衰减记忆表面的研究，以捕捉基于事件的数据的时间方面。这些表面然后用于执行无监督的特征提取，跟踪和识别。为了产生记忆表面，事件分箱，线性衰减的内核和指数衰减的内核被用指数衰减的内核发现性能最好。发现基于事件的衰减记忆表面在识别时优于基于时间的衰减记忆表面，特别是当要求不变的目标速度时。调查了一系列网络和感受野的大小。该系统在进入视野的飞机156毫秒内实现了98.75％的识别精度，仅使用25个基于事件的特征提取神经元与线性分类器串联。通过将线性分类器结果与ELM分类器进行比较，我们发现少数基于事件的特征提取器可以有效地将数据集的复杂时空事件模式投影到特征空间中的几乎线性可分的表示。

##### URL
[https://arxiv.org/abs/1603.04223](https://arxiv.org/abs/1603.04223)

##### PDF
[https://arxiv.org/pdf/1603.04223](https://arxiv.org/pdf/1603.04223)

