---
layout: post
title: "Speech Denoising with Deep Feature Losses"
date: 2018-06-27 15:08:23
categories: arXiv_SD
tags: arXiv_SD CNN Deep_Learning Detection
author: Francois G. Germain, Qifeng Chen, Vladlen Koltun
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end deep learning approach to denoising speech signals by processing the raw waveform directly. Given input audio containing speech corrupted by an additive background signal, the system aims to produce a processed signal that contains only the speech content. Recent approaches have shown promising results using various deep network architectures. In this paper, we propose to train a fully-convolutional context aggregation network using a deep feature loss. That loss is based on comparing the internal feature activations in a different network, trained for acoustic environment detection and domestic audio tagging. Our approach outperforms the state-of-the-art in objective speech quality metrics and in large-scale perceptual experiments with human listeners. It also outperforms an identical network trained using traditional regression losses. The advantage of the new approach is particularly pronounced for the hardest data with the most intrusive background noise, for which denoising is most needed and most challenging.

##### Abstract (translated by Google)
我们提出了一种通过直接处理原始波形去除语音信号的端到端深度学习方法。给定包含由加性背景信号损坏的语音的输入音频，系统旨在产生仅包含语音内容的经处理的信号。最近的方法已经使用各种深度网络架构显示出有希望的结果在本文中，我们建议使用深度特征丢失来训练全卷积上下文聚合网络。这种损失是基于比较不同网络中的内部特征激活，经过声学环境检测和国内音频标签培训。我们的方法胜过了客观语音质量指标的最新技术以及与人类听众进行的大规模感知实验。它还优于使用传统回归损失训练的相同网络。新方法的优势对于背景噪声最大的难度最大的数据尤其明显，因为去噪是最需要和最具挑战性的。

##### URL
[http://arxiv.org/abs/1806.10522](http://arxiv.org/abs/1806.10522)

##### PDF
[http://arxiv.org/pdf/1806.10522](http://arxiv.org/pdf/1806.10522)

