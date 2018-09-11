---
layout: post
title: "ContextVP: Fully Context-Aware Video Prediction"
date: 2018-09-09 09:55:04
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN RNN Prediction
author: Wonmin Byeon, Qin Wang, Rupesh Kumar Srivastava, Petros Koumoutsakos
mathjax: true
---

* content
{:toc}

##### Abstract
Video prediction models based on convolutional networks, recurrent networks, and their combinations often result in blurry predictions. We identify an important contributing factor for imprecise predictions that has not been studied adequately in the literature: blind spots, i.e., lack of access to all relevant past information for accurately predicting the future. To address this issue, we introduce a fully context-aware architecture that captures the entire available past context for each pixel using Parallel Multi-Dimensional LSTM units and aggregates it using blending units. Our model outperforms a strong baseline network of 20 recurrent convolutional layers and yields state-of-the-art performance for next step prediction on three challenging real-world video datasets: Human 3.6M, Caltech Pedestrian, and UCF-101. Moreover, it does so with fewer parameters than several recently proposed models, and does not rely on deep convolutional networks, multi-scale architectures, separation of background and foreground modeling, motion flow learning, or adversarial training. These results highlight that full awareness of past context is of crucial importance for video prediction.

##### Abstract (translated by Google)
基于卷积网络，循环网络及其组合的视频预测模型经常导致模糊预测。我们确定了一个不精确预测的重要因素，这些因素尚未在文献中得到充分研究：盲点，即无法获得所有相关的过去信息以准确预测未来。为了解决这个问题，我们引入了一个完全上下文感知的体系结构，该体系结构使用并行多维LSTM单元捕获每个像素的整个可用过去上下文，并使用混合单元对其进行聚合。我们的模型优于20个递归卷积层的强大基线网络，并为三个具有挑战性的真实世界视频数据集的下一步预测提供最先进的性能：人类3.6M，加州理工学院行人和UCF-101。此外，它使用比最近提出的几个模型更少的参数，并且不依赖于深度卷积网络，多尺度架构，背景和前景建模的分离，运动流学习或对抗性训练。这些结果强调，对过去情境的充分了解对于视频预测至关重要。

##### URL
[http://arxiv.org/abs/1710.08518](http://arxiv.org/abs/1710.08518)

##### PDF
[http://arxiv.org/pdf/1710.08518](http://arxiv.org/pdf/1710.08518)

