---
layout: post
title: "Hierarchical LSTM with Adjusted Temporal Attention for Video Captioning"
date: 2017-06-05 08:09:20
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption RNN Language_Model
author: Jingkuan Song, Zhao Guo, Lianli Gao, Wu Liu, Dongxiang Zhang, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progress has been made in using attention based encoder-decoder framework for video captioning. However, most existing decoders apply the attention mechanism to every generated word including both visual words (e.g., "gun" and "shooting") and non-visual words (e.g. "the", "a"). However, these non-visual words can be easily predicted using natural language model without considering visual signals or attention. Imposing attention mechanism on non-visual words could mislead and decrease the overall performance of video captioning. To address this issue, we propose a hierarchical LSTM with adjusted temporal attention (hLSTMat) approach for video captioning. Specifically, the proposed framework utilizes the temporal attention for selecting specific frames to predict the related words, while the adjusted temporal attention is for deciding whether to depend on the visual information or the language context information. Also, a hierarchical LSTMs is designed to simultaneously consider both low-level visual information and high-level language context information to support the video caption generation. To demonstrate the effectiveness of our proposed framework, we test our method on two prevalent datasets: MSVD and MSR-VTT, and experimental results show that our approach outperforms the state-of-the-art methods on both two datasets.

##### Abstract (translated by Google)
视频字幕使用基于注意力的编码器 - 解码器框架已经取得了最新进展。然而，大多数现有解码器将注意机制应用于包括视觉单词（例如，“枪”和“拍摄”）和非视觉单词（例如“the”，“a”）的每个生成的单词。然而，这些非视觉单词可以很容易地使用自然语言模型预测，而不用考虑视觉信号或注意力。对非视觉词汇采取注意机制可能会误导和降低视频字幕的整体表现。为了解决这个问题，我们提出了一种具有调整时间关注的分级LSTM（hLSTMat）方法来处理视频字幕。具体而言，所提出的框架利用时间上的关注来选择特定的帧来预测相关词语，而调整后的时间上的关注则用于决定是否依赖于视觉信息或语言上下文信息。而且，分级LSTM被设计成同时考虑低级视觉信息和高级语言上下文信息以支持视频字幕生成。为了证明我们提出的框架的有效性，我们在两个普遍的数据集上测试了我们的方法：MSVD和MSR-VTT，实验结果表明我们的方法在两个数据集上的表现都优于最先进的方法。

##### URL
[https://arxiv.org/abs/1706.01231](https://arxiv.org/abs/1706.01231)

##### PDF
[https://arxiv.org/pdf/1706.01231](https://arxiv.org/pdf/1706.01231)

