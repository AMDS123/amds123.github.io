---
layout: post
title: 'From Deterministic to Generative: Multi-Modal Stochastic RNNs for Video Captioning'
date: 2017-10-20 09:27:14
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption RNN
author: Jingkuan Song, Yuyu Guo, Lianli Gao, Xuelong Li, Alan Hanjalic, Heng Tao Shen
---

* content
{:toc}

##### Abstract
Video captioning in essential is a complex natural process, which is affected by various uncertainties stemming from video content, subjective judgment, etc. In this paper we build on the recent progress in using encoder-decoder framework for video captioning and address what we find to be a critical deficiency of the existing methods, that most of the decoders propagate deterministic hidden states. Such complex uncertainty cannot be modeled efficiently by the deterministic models. In this paper, we propose a generative approach, referred to as multi-modal stochastic RNNs networks (MS-RNN), which models the uncertainty observed in the data using latent stochastic variables. Therefore, MS-RNN can improve the performance of video captioning, and generate multiple sentences to describe a video considering different random factors. Specifically, a multi-modal LSTM (M-LSTM) is first proposed to interact with both visual and textual features to capture a high-level representation. Then, a backward stochastic LSTM (S-LSTM) is proposed to support uncertainty propagation by introducing latent variables. Experimental results on the challenging datasets MSVD and MSR-VTT show that our proposed MS-RNN approach outperforms the state-of-the-art video captioning benchmarks.

##### Abstract (translated by Google)
本质上的视频字幕是一个复杂的自然过程，受到来自视频内容，主观判断等各种不确定因素的影响。在本文中，我们建立在使用视频字幕编码器 - 解码器框架的最新进展，并解决我们发现是现有方法的关键缺陷，大多数解码器传播确定性隐藏状态。这种复杂的不确定性不能通过确定性模型有效地建模。在本文中，我们提出了一种生成方法，称为多模态随机RNN网络（MS-RNN），它使用潜在随机变量对数据中观测到的不确定性进行建模。因此，MS-RNN可以提高视频字幕的性能，并且考虑到不同的随机因素，生成多个句子来描述视频。具体而言，多模式LSTM（M-LSTM）首先被提议与视觉和文本特征交互以捕捉高级表示。然后，引入一个后向随机LSTM（S-LSTM），通过引入潜变量来支持不确定性传播。在具有挑战性的数据集MSVD和MSR-VTT上的实验结果表明，我们提出的MS-RNN方法胜过了最新的视频字幕基准。

##### URL
[https://arxiv.org/abs/1708.02478](https://arxiv.org/abs/1708.02478)

