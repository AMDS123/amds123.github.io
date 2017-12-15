---
layout: post
title: "Leaving Some Stones Unturned: Dynamic Feature Prioritization for Activity Detection in Streaming Video"
date: 2016-04-01 22:37:28
categories: arXiv_CV
tags: arXiv_CV Prediction Detection Recognition
author: Yu-Chuan Su, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Current approaches for activity recognition often ignore constraints on computational resources: 1) they rely on extensive feature computation to obtain rich descriptors on all frames, and 2) they assume batch-mode access to the entire test video at once. We propose a new active approach to activity recognition that prioritizes "what to compute when" in order to make timely predictions. The main idea is to learn a policy that dynamically schedules the sequence of features to compute on selected frames of a given test video. In contrast to traditional static feature selection, our approach continually re-prioritizes computation based on the accumulated history of observations and accounts for the transience of those observations in ongoing video. We develop variants to handle both the batch and streaming settings. On two challenging datasets, our method provides significantly better accuracy than alternative techniques for a wide range of computational budgets.

##### Abstract (translated by Google)
目前的活动识别方法通常会忽略对计算资源的限制：1）依靠广泛的特征计算来获取所有帧上的丰富的描述符; 2）他们假设批量模式访问整个测试视频。我们提出了一种新的主​​动方法来活动识别，优先考虑“什么时候计算”，以便及时进行预测。主要思想是学习动态调度特征序列的策略，以在给定测试视频的选定帧上进行计算。与传统的静态特征选择相比，我们的方法不断地根据观察的累积历史来重新计算计算的优先次序，并且考虑到正在进行的视频中那些观察的短暂性。我们开发变体来处理批处理和流设置。在两个具有挑战性的数据集上，我们的方法比广泛的计算预算的替代技术提供了更好的准确性。

##### URL
[https://arxiv.org/abs/1604.00427](https://arxiv.org/abs/1604.00427)

##### PDF
[https://arxiv.org/pdf/1604.00427](https://arxiv.org/pdf/1604.00427)

