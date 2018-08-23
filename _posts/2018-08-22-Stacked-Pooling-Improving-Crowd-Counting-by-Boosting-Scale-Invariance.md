---
layout: post
title: "Stacked Pooling: Improving Crowd Counting by Boosting Scale Invariance"
date: 2018-08-22 17:46:06
categories: arXiv_CV
tags: arXiv_CV CNN
author: Siyu Huang, Xi Li, Zhi-Qi Cheng, Zhongfei Zhang, Alexander Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we explore the cross-scale similarity in crowd counting scenario, in which the regions of different scales often exhibit high visual similarity. This feature is universal both within an image and across different images, indicating the importance of scale invariance of a crowd counting model. Motivated by this, in this paper we propose simple but effective variants of pooling module, i.e., multi-kernel pooling and stacked pooling, to boost the scale invariance of convolutional neural networks (CNNs), benefiting much the crowd density estimation and counting. Specifically, the multi-kernel pooling comprises of pooling kernels with multiple receptive fields to capture the responses at multi-scale local ranges. The stacked pooling is an equivalent form of multi-kernel pooling, while, it reduces considerable computing cost. Our proposed pooling modules do not introduce extra parameters into model and can easily take place of the vanilla pooling layer in implementation. In empirical study on two benchmark crowd counting datasets, the stacked pooling beats the vanilla pooling layer in most cases.

##### Abstract (translated by Google)
在这项工作中，我们探讨了人群计数场景中的跨尺度相似性，其中不同尺度的区域通常表现出高视觉相似性。该特征在图像内和不同图像上是通用的，表明人群计数模型的尺度不变性的重要性。由此推动，在本文中，我们提出简单但有效的汇集模块变体，即多核池和堆叠池，以增强卷积神经网络（CNN）的规模不变性，从而有利于人群密度估计和计数。具体地，多内核池包括具有多个感受域的内核池以捕获多尺度本地范围的响应。堆叠池是多内核池的等效形式，同时降低了可观的计算成本。我们提出的池模块不会在模型中引入额外的参数，并且可以在实现中轻松取代vanilla池层。在对两个基准人群计数数据集的实证研究中，堆叠池在大多数情况下击败了香草汇集层。

##### URL
[http://arxiv.org/abs/1808.07456](http://arxiv.org/abs/1808.07456)

##### PDF
[http://arxiv.org/pdf/1808.07456](http://arxiv.org/pdf/1808.07456)

