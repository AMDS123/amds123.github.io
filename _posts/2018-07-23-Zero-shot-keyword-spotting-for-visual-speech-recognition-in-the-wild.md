---
layout: post
title: "Zero-shot keyword spotting for visual speech recognition in-the-wild"
date: 2018-07-23 08:06:08
categories: arXiv_CV
tags: arXiv_CV Attention Speech_Recognition RNN Recognition
author: Themos Stafylakis, Georgios Tzimiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Visual keyword spotting (KWS) is the problem of estimating whether a text query occurs in a given recording using only video information. This paper focuses on visual KWS for words unseen during training, a real-world, practical setting which so far has received no attention by the community. To this end, we devise an end-to-end architecture comprising (a) a state-of-the-art visual feature extractor based on spatiotemporal Residual Networks, (b) a grapheme-to-phoneme model based on sequence-to-sequence neural networks, and (c) a stack of recurrent neural networks which learn how to correlate visual features with the keyword representation. Different to prior works on KWS, which try to learn word representations merely from sequences of graphemes (i.e. letters), we propose the use of a grapheme-to-phoneme encoder-decoder model which learns how to map words to their pronunciation. We demonstrate that our system obtains very promising visual-only KWS results on the challenging LRS2 database, for keywords unseen during training. We also show that our system outperforms a baseline which addresses KWS via automatic speech recognition (ASR), while it drastically improves over other recently proposed ASR-free KWS methods.

##### Abstract (translated by Google)
可视关键字定位（KWS）是仅使用视频信息来估计文本查询是否在给定记录中发生的问题。本文重点关注视觉KWS，用于培训期间看不到的文字，这是一个真实世界的实用环境，到目前为止还没有得到社区的关注。为此，我们设计了一种端到端架构，包括（a）基于时空残留网络的最先进的视觉特征提取器，（b）基于序列到 - 的 - 字母 - 音素模型序列神经网络，以及（c）一系列递归神经网络，它们学习如何将视觉特征与关键字表示相关联。与KWS的先前工作不同，KWS试图仅仅从字形序列（即字母）学习单词表示，我们建议使用字形到音素编码器 - 解码器模型，该模型学习如何将单词映射到他们的发音。我们证明了我们的系统在具有挑战性的LRS2数据库中获得了非常有前途的仅视觉KWS结果，用于培训期间看不到的关键字。我们还表明，我们的系统优于通过自动语音识别（ASR）解决KWS的基线，同时它比其他最近提出的无ASR KWS方法有了显着的改进。

##### URL
[http://arxiv.org/abs/1807.08469](http://arxiv.org/abs/1807.08469)

##### PDF
[http://arxiv.org/pdf/1807.08469](http://arxiv.org/pdf/1807.08469)

