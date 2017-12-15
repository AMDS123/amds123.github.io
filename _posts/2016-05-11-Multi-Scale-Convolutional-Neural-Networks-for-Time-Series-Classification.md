---
layout: post
title: "Multi-Scale Convolutional Neural Networks for Time Series Classification"
date: 2016-05-11 04:48:21
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction
author: Zhicheng Cui, Wenlin Chen, Yixin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Time series classification (TSC), the problem of predicting class labels of time series, has been around for decades within the community of data mining and machine learning, and found many important applications such as biomedical engineering and clinical prediction. However, it still remains challenging and falls short of classification accuracy and efficiency. Traditional approaches typically involve extracting discriminative features from the original time series using dynamic time warping (DTW) or shapelet transformation, based on which an off-the-shelf classifier can be applied. These methods are ad-hoc and separate the feature extraction part with the classification part, which limits their accuracy performance. Plus, most existing methods fail to take into account the fact that time series often have features at different time scales. To address these problems, we propose a novel end-to-end neural network model, Multi-Scale Convolutional Neural Networks (MCNN), which incorporates feature extraction and classification in a single framework. Leveraging a novel multi-branch layer and learnable convolutional layers, MCNN automatically extracts features at different scales and frequencies, leading to superior feature representation. MCNN is also computationally efficient, as it naturally leverages GPU computing. We conduct comprehensive empirical evaluation with various existing methods on a large number of benchmark datasets, and show that MCNN advances the state-of-the-art by achieving superior accuracy performance than other leading methods.

##### Abstract (translated by Google)
时间序列分类（TSC）是预测时间序列类别标签的问题，在数据挖掘和机器学习领域已有数十年的历史，并发现了许多重要的应用，如生物医学工程和临床预测。但是，它仍然具有挑战性，缺乏分类准确性和效率。传统方法通常包括使用动态时间规整（DTW）或shapelet转换从原始时间序列中提取区分特征，基于此可以应用现成的分类器。这些方法是特设的，将特征提取部分与分类部分分开，限制了其准确性。此外，大多数现有的方法都没有考虑到时间序列在不同时间尺度上通常具有特征的事实。为了解决这些问题，我们提出了一种新颖的端到端神经网络模型，多尺度卷积神经网络（MCNN），它将特征提取和分类结合在一个框架中。利用新颖的多分支层和可学习卷积层，MCNN可以自动提取不同尺度和频率的特征，从而实现卓越的特征表示。 MCNN在计算上也是高效的，因为它自然地利用了GPU计算。我们用大量基准数据集上的各种现有方法进行了全面的实证评估，并表明MCNN通过实现比其他领先方法更高的精度性能来推进最新技术。

##### URL
[https://arxiv.org/abs/1603.06995](https://arxiv.org/abs/1603.06995)

##### PDF
[https://arxiv.org/pdf/1603.06995](https://arxiv.org/pdf/1603.06995)

