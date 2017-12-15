---
layout: post
title: "Audio Visual Speech Recognition using Deep Recurrent Neural Networks"
date: 2016-11-09 10:24:52
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Classification Recognition
author: Abhinav Thanda, Shankar M Venkatesan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a training algorithm for an audio-visual automatic speech recognition (AV-ASR) system using deep recurrent neural network (RNN).First, we train a deep RNN acoustic model with a Connectionist Temporal Classification (CTC) objective function. The frame labels obtained from the acoustic model are then used to perform a non-linear dimensionality reduction of the visual features using a deep bottleneck network. Audio and visual features are fused and used to train a fusion RNN. The use of bottleneck features for visual modality helps the model to converge properly during training. Our system is evaluated on GRID corpus. Our results show that presence of visual modality gives significant improvement in character error rate (CER) at various levels of noise even when the model is trained without noisy data. We also provide a comparison of two fusion methods: feature fusion and decision fusion.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个使用深回归神经网络（RNN）的视听自动语音识别（AV-ASR）系统的训练算法。首先，我们训练一个深入RNN声学模型与连接主义时间分类（CTC）目标功能。然后使用从声学模型获得的帧标签使用深度瓶颈网络来执行视觉特征的非线性维度降低。音频和视觉特征被融合并用于训练融合RNN。视觉形态瓶颈功能的使用有助于模型在训练过程中正确地衔接。我们的系统在GRID语料库上进行评估。我们的研究结果表明，即使模型训练时没有噪声数据，视觉模态的存在也可以显着改善不同噪声水平下的字符错误率（CER）。我们还提供了两种融合方法的比较：特征融合和决策融合。

##### URL
[https://arxiv.org/abs/1611.02879](https://arxiv.org/abs/1611.02879)

##### PDF
[https://arxiv.org/pdf/1611.02879](https://arxiv.org/pdf/1611.02879)

