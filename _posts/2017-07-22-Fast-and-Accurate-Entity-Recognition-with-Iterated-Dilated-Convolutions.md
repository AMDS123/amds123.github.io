---
layout: post
title: "Fast and Accurate Entity Recognition with Iterated Dilated Convolutions"
date: 2017-07-22 04:04:30
categories: arXiv_SD
tags: arXiv_SD Face CNN RNN Prediction Recognition
author: Emma Strubell, Patrick Verga, David Belanger, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Today when many practitioners run basic NLP on the entire web and large-volume traffic, faster methods are paramount to saving time and energy costs. Recent advances in GPU hardware have led to the emergence of bi-directional LSTMs as a standard method for obtaining per-token vector representations serving as input to labeling tasks such as NER (often followed by prediction in a linear-chain CRF). Though expressive and accurate, these models fail to fully exploit GPU parallelism, limiting their computational efficiency. This paper proposes a faster alternative to Bi-LSTMs for NER: Iterated Dilated Convolutional Neural Networks (ID-CNNs), which have better capacity than traditional CNNs for large context and structured prediction. Unlike LSTMs whose sequential processing on sentences of length N requires O(N) time even in the face of parallelism, ID-CNNs permit fixed-depth convolutions to run in parallel across entire documents. We describe a distinct combination of network structure, parameter sharing and training procedures that enable dramatic 14-20x test-time speedups while retaining accuracy comparable to the Bi-LSTM-CRF. Moreover, ID-CNNs trained to aggregate context from the entire document are even more accurate while maintaining 8x faster test time speeds.

##### Abstract (translated by Google)
今天当许多从业人员在整个网络上运行基本的自然语言处理和大量的流量时，更快速的方法对节省时间和能源成本至关重要。 GPU硬件的最新进展已经导致双向LSTM的出现，作为用于获得每个令牌向量表示的标准方法，用作标记诸如NER（通常在线性链CRF中预测之后）的任务的输入。尽管表达和准确，这些模型未能充分利用GPU并行性，限制了其计算效率。本文提出了一种更快的NER迭代扩展卷积神经网络（ID-CNNs）的替代方案，在大环境和结构预测方面比传统的CNN具有更好的容量。与LSTMs不同的是，即使面对并行性，对长度为N的句子进行连续处理也需要O（N）个时间，ID-CNN允许固定深度卷积在整个文档中并行运行。我们描述了网络结构，参数共享和培训程序的独特组合，可实现戏剧性14-20倍的测试时间加速，同时保持与Bi-LSTM-CRF相当的精度。而且，训练来自整个文档聚合上下文的ID-CNN甚至更准确，同时保持8倍的测试时间速度。

##### URL
[https://arxiv.org/abs/1702.02098](https://arxiv.org/abs/1702.02098)

##### PDF
[https://arxiv.org/pdf/1702.02098](https://arxiv.org/pdf/1702.02098)

