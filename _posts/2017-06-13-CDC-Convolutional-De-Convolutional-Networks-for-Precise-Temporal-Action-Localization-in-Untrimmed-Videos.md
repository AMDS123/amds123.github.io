---
layout: post
title: "CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos"
date: 2017-06-13 04:14:57
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Zheng Shou, Jonathan Chan, Alireza Zareian, Kazuyuki Miyazawa, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action localization is an important yet challenging problem. Given a long, untrimmed video consisting of multiple action instances and complex background contents, we need not only to recognize their action categories, but also to localize the start time and end time of each instance. Many state-of-the-art systems use segment-level classifiers to select and rank proposal segments of pre-determined boundaries. However, a desirable model should move beyond segment-level and make dense predictions at a fine granularity in time to determine precise temporal boundaries. To this end, we design a novel Convolutional-De-Convolutional (CDC) network that places CDC filters on top of 3D ConvNets, which have been shown to be effective for abstracting action semantics but reduce the temporal length of the input data. The proposed CDC filter performs the required temporal upsampling and spatial downsampling operations simultaneously to predict actions at the frame-level granularity. It is unique in jointly modeling action semantics in space-time and fine-grained temporal dynamics. We train the CDC network in an end-to-end manner efficiently. Our model not only achieves superior performance in detecting actions in every frame, but also significantly boosts the precision of localizing temporal boundaries. Finally, the CDC network demonstrates a very high efficiency with the ability to process 500 frames per second on a single GPU server. We will update the camera-ready version and publish the source codes online soon.

##### Abstract (translated by Google)
时间动作本地化是一个重要但具有挑战性的问题。给定一个由多个动作实例和复杂背景内容组成的长时间未修剪的视频，我们不仅需要识别他们的动作类别，还要定位每个实例的开始时间和结束时间。许多最先进的系统使用段级分类器来选择和排列预定边界的提议段。然而，一个理想的模型应该超越片段级别，并且以精细的时间间隔进行密集的预测，以确定精确的时间边界。为此，我们设计了一种新颖的卷积 - 去卷积（CDC）网络，将CDC滤波器放置在3D通信网络的顶部，已被证明对提取动作语义是有效的，但是减少了输入数据的时间长度。所提出的CDC滤波器同时执行所需的时间上采样和空间下采样操作以在帧级粒度处预测动作。联合建模时空动作语义和细粒度时态动力学是独一无二的。我们有效地以端对端的方式培训CDC网络。我们的模型不仅在每帧中检测动作方面都有很好的性能，而且显着提高了时间边界定位的精度。最后，CDC网络显示出非常高的效率，能够在单个GPU服务器上处理每秒500帧的能力。我们将更新相机就绪版本，并尽快在线发布源代码。

##### URL
[https://arxiv.org/abs/1703.01515](https://arxiv.org/abs/1703.01515)

##### PDF
[https://arxiv.org/pdf/1703.01515](https://arxiv.org/pdf/1703.01515)

