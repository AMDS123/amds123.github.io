---
layout: post
title: "CBinfer: Change-Based Inference for Convolutional Neural Networks on Video Data"
date: 2017-06-21 09:27:14
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Lukas Cavigelli, Philippe Degen, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting per-frame features using convolutional neural networks for real-time processing of video data is currently mainly performed on powerful GPU-accelerated workstations and compute clusters. However, there are many applications such as smart surveillance cameras that require or would benefit from on-site processing. To this end, we propose and evaluate a novel algorithm for change-based evaluation of CNNs for video data recorded with a static camera setting, exploiting the spatio-temporal sparsity of pixel changes. We achieve an average speed-up of 8.6x over a cuDNN baseline on a realistic benchmark with a negligible accuracy loss of less than 0.1% and no retraining of the network. The resulting energy efficiency is 10x higher than that of per-frame evaluation and reaches an equivalent of 328 GOp/s/W on the Tegra X1 platform.

##### Abstract (translated by Google)
使用卷积神经网络来提取视频数据的实时处理的每帧特征目前主要在强大的GPU加速工作站和计算集群上执行。但是，智能监控摄像机等许多应用都需要现场处理，或者会受益于现场处理。为此，我们提出并评估了一种用静态相机设置记录的用于视频数据的CNN的基于变化的评估的新算法，利用像素变化的时空稀疏性。在一个现实的基准上，我们实现了平均加速8.6倍的cuDNN基线，精度损失可以忽略不计，小于0.1％，而且不需要再训练网络。由此产生的能源效率比每帧评估高10倍，在Tegra X1平台上达到328 GOp / s / W。

##### URL
[https://arxiv.org/abs/1704.04313](https://arxiv.org/abs/1704.04313)

##### PDF
[https://arxiv.org/pdf/1704.04313](https://arxiv.org/pdf/1704.04313)

