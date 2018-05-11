---
layout: post
title: "End-to-End Polyphonic Sound Event Detection Using Convolutional Recurrent Neural Networks with Learned Time-Frequency Representation Input"
date: 2018-05-09 15:10:57
categories: arXiv_SD
tags: arXiv_SD CNN RNN Detection Recognition
author: Emre &#xc7;ak&#x131;r, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
Sound event detection systems typically consist of two stages: extracting hand-crafted features from the raw audio waveform, and learning a mapping between these features and the target sound events using a classifier. Recently, the focus of sound event detection research has been mostly shifted to the latter stage using standard features such as mel spectrogram as the input for classifiers such as deep neural networks. In this work, we utilize end-to-end approach and propose to combine these two stages in a single deep neural network classifier. The feature extraction over the raw waveform is conducted by a feedforward layer block, whose parameters are initialized to extract the time-frequency representations. The feature extraction parameters are updated during training, resulting with a representation that is optimized for the specific task. This feature extraction block is followed by (and jointly trained with) a convolutional recurrent network, which has recently given state-of-the-art results in many sound recognition tasks. The proposed system does not outperform a convolutional recurrent network with fixed hand-crafted features. The final magnitude spectrum characteristics of the feature extraction block parameters indicate that the most relevant information for the given task is contained in 0 - 3 kHz frequency range, and this is also supported by the empirical results on the SED performance.

##### Abstract (translated by Google)
声音事件检测系统通常由两个阶段组成：从原始音频波形中提取手工制作的特征，并使用分类器学习这些特征与目标声音事件之间的映射。最近，声音事件检测研究的重点已经大部分转移到后期阶段，使用标准特征，如mel谱图作为分类器（如深度神经网络）的输入。在这项工作中，我们利用端到端的方法，并提出将这两个阶段结合在一个深度神经网络分类器中。原始波形上的特征提取由前馈层块进行，其前端参数被初始化以提取时频表示。特征提取参数在训练期间被更新，从而得到针对特定任务而优化的表示。该特征提取块之后是卷积循环网络（并且与其共同训练），卷积循环网络最近在许多声音识别任务中给出了最新的结果。所提出的系统不能超越具有固定手工特征的卷积循环网络。特征提取块参数的最终幅度谱特征指示给定任务的最相关信息包含在0-3kHz频率范围内，并且SED性能的实证结果也支持这一点。

##### URL
[http://arxiv.org/abs/1805.03647](http://arxiv.org/abs/1805.03647)

##### PDF
[http://arxiv.org/pdf/1805.03647](http://arxiv.org/pdf/1805.03647)

