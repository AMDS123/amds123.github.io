---
layout: post
title: "Deep convolutional neural networks for predominant instrument recognition in polyphonic music"
date: 2016-12-26 12:29:26
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Yoonchang Han, Jaehun Kim, Kyogu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying musical instruments in polyphonic music recordings is a challenging but important problem in the field of music information retrieval. It enables music search by instrument, helps recognize musical genres, or can make music transcription easier and more accurate. In this paper, we present a convolutional neural network framework for predominant instrument recognition in real-world polyphonic music. We train our network from fixed-length music excerpts with a single-labeled predominant instrument and estimate an arbitrary number of predominant instruments from an audio signal with a variable length. To obtain the audio-excerpt-wise result, we aggregate multiple outputs from sliding windows over the test audio. In doing so, we investigated two different aggregation methods: one takes the average for each instrument and the other takes the instrument-wise sum followed by normalization. In addition, we conducted extensive experiments on several important factors that affect the performance, including analysis window size, identification threshold, and activation functions for neural networks to find the optimal set of parameters. Using a dataset of 10k audio excerpts from 11 instruments for evaluation, we found that convolutional neural networks are more robust than conventional methods that exploit spectral features and source separation with support vector machines. Experimental results showed that the proposed convolutional network architecture obtained an F1 measure of 0.602 for micro and 0.503 for macro, respectively, achieving 19.6% and 16.4% in performance improvement compared with other state-of-the-art algorithms.

##### Abstract (translated by Google)
在复调音乐录音中识别乐器是音乐信息检索领域中具有挑战性但又重要的问题。它能够通过乐器进行音乐搜索，帮助识别音乐流派，或者使音乐转录更容易和更准确。在本文中，我们提出了一个用于现实世界中复调音乐的主要仪器识别的卷积神经网络框架。我们使用单一标签的主要乐器从固定长度的音乐节选中训练我们的网络，并从具有可变长度的音频信号中估计任意数量的主要乐器。为了获得音频摘录的结果，我们在测试音频上聚合滑动窗口的多个输出。在这样做的过程中，我们调查了两种不同的聚合方法：一种取各台仪器的平均值，另一台取仪器的总和，然后进行归一化。此外，我们还对影响性能的几个重要因素进行了广泛的实验，包括分析窗口大小，识别阈值和神经网络的激活函数，以找到最优参数集。使用来自11个仪器的10k音频摘录的数据集进行评估，我们发现卷积神经网络比利用支持向量机利用频谱特征和源分离的传统方法更强健。实验结果表明，所提出的卷积网络架构分别获得了0.602和0.503的F1值，与其他最先进的算法相比，性能提高了19.6％和16.4％。

##### URL
[https://arxiv.org/abs/1605.09507](https://arxiv.org/abs/1605.09507)

##### PDF
[https://arxiv.org/pdf/1605.09507](https://arxiv.org/pdf/1605.09507)

