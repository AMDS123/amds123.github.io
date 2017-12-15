---
layout: post
title: "End-to-End ASR-free Keyword Search from Speech"
date: 2017-01-13 15:05:39
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Embedding CNN RNN Language_Model Recognition
author: Kartik Audhkhasi, Andrew Rosenberg, Abhinav Sethy, Bhuvana Ramabhadran, Brian Kingsbury
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end (E2E) systems have achieved competitive results compared to conventional hybrid hidden Markov model (HMM)-deep neural network based automatic speech recognition (ASR) systems. Such E2E systems are attractive due to the lack of dependence on alignments between input acoustic and output grapheme or HMM state sequence during training. This paper explores the design of an ASR-free end-to-end system for text query-based keyword search (KWS) from speech trained with minimal supervision. Our E2E KWS system consists of three sub-systems. The first sub-system is a recurrent neural network (RNN)-based acoustic auto-encoder trained to reconstruct the audio through a finite-dimensional representation. The second sub-system is a character-level RNN language model using embeddings learned from a convolutional neural network. Since the acoustic and text query embeddings occupy different representation spaces, they are input to a third feed-forward neural network that predicts whether the query occurs in the acoustic utterance or not. This E2E ASR-free KWS system performs respectably despite lacking a conventional ASR system and trains much faster.

##### Abstract (translated by Google)
与传统的基于混合隐马尔可夫模型（HMM） - 深度神经网络的自动语音识别（ASR）系统相比，端到端（E2E）系统已经取得了有竞争力的结果。这样的E2E系统是有吸引力的，因为在训练期间缺少对输入声学和输出字形或HMM状态序列之间的对齐的依赖。本文从最小监督下的语音训练探讨了基于文本查询的关键字搜索（KWS）的无ASR端到端系统的设计。我们的E2E KWS系统由三个子系统组成。第一个子系统是基于循环神经网络（RNN）的声学自动编码器，通过有限维表示来重建音频。第二个子系统是使用从卷积神经网络学习的嵌入的角色级RNN语言模型。由于声音和文本查询嵌入占据不同的表示空间，所以它们被输入到第三前馈神经网络，该网络预测查询是否发生在声音话语中。这个E2E无ASR的KWS系统虽然缺乏传统的ASR系统，但训练速度快，

##### URL
[https://arxiv.org/abs/1701.04313](https://arxiv.org/abs/1701.04313)

##### PDF
[https://arxiv.org/pdf/1701.04313](https://arxiv.org/pdf/1701.04313)

