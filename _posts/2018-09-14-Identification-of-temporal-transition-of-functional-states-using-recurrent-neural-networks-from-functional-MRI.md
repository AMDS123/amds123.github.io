---
layout: post
title: "Identification of temporal transition of functional states using recurrent neural networks from functional MRI"
date: 2018-09-14 18:59:32
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning Prediction Detection
author: Hongming Li, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic functional connectivity analysis provides valuable information for understanding brain functional activity underlying different cognitive processes. Besides sliding window based approaches, a variety of methods have been developed to automatically split the entire functional MRI scan into segments by detecting change points of functional signals to facilitate better characterization of temporally dynamic functional connectivity patterns. However, these methods are based on certain assumptions for the functional signals, such as Gaussian distribution, which are not necessarily suitable for the fMRI data. In this study, we develop a deep learning based framework for adaptively detecting temporally dynamic functional state transitions in a data-driven way without any explicit modeling assumptions, by leveraging recent advances in recurrent neural networks (RNNs) for sequence modeling. Particularly, we solve this problem in an anomaly detection framework with an assumption that the functional profile of one single time point could be reliably predicted based on its preceding profiles within stable functional state, while large prediction errors would occur around change points of functional states. We evaluate the proposed method using both task and resting-state fMRI data obtained from the human connectome project and experimental results have demonstrated that the proposed change point detection method could effectively identify change points between different task events and split the resting-state fMRI into segments with distinct functional connectivity patterns.

##### Abstract (translated by Google)
动态功能连接分析为理解不同认知过程中的大脑功能活动提供了有价值的信息除了基于滑动窗口的方法之外，已经开发了多种方法来通过检测功能信号的变化点来自动地将整个功能性MRI扫描分成段，以便于更好地表征时间上动态的功能连接模式。然而，这些方法基于功能信号的某些假设，例如高斯分布，其不一定适合于fMRI数据。在本研究中，我们开发了一种基于深度学习的框架，通过利用递归神经网络（RNN）的最新进展进行序列建模，以数据驱动的方式自适应地检测时间动态功能状态转换，而无需任何明确的建模假设。特别地，我们在异常检测框架中解决该问题，假设可以基于其在稳定功能状态内的先前分布来可靠地预测单个时间点的功能分布，而在功能状态的变化点周围将发生大的预测误差。我们使用从人类连接组项目获得的任务和静止状态fMRI数据来评估所提出的方法，并且实验结果已经证明所提出的变化点检测方法可以有效地识别不同任务事件之间的变化点并且将静止状态fMRI分成段。具有独特的功能连接模式。

##### URL
[http://arxiv.org/abs/1809.05560](http://arxiv.org/abs/1809.05560)

##### PDF
[http://arxiv.org/pdf/1809.05560](http://arxiv.org/pdf/1809.05560)

