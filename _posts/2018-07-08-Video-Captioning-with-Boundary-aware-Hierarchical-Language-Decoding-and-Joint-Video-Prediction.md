---
layout: post
title: "Video Captioning with Boundary-aware Hierarchical Language Decoding and Joint Video Prediction"
date: 2018-07-08 08:49:34
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption RNN Language_Model Prediction
author: Xiangxi Shi, Jianfei Cai, Jiuxiang Gu, Shafiq Joty
mathjax: true
---

* content
{:toc}

##### Abstract
The explosion of video data on the internet requires effective and efficient technology to generate captions automatically for people who are not able to watch the videos. Despite the great progress of video captioning research, particularly on video feature encoding, the language decoder is still largely based on the prevailing RNN decoder such as LSTM, which tends to prefer the frequent word that aligns with the video. In this paper, we propose a boundary-aware hierarchical language decoder for video captioning, which consists of a high-level GRU based language decoder, working as a global (caption-level) language model, and a low-level GRU based language decoder, working as a local (phrase-level) language model. Most importantly, we introduce a binary gate into the low-level GRU language decoder to detect the language boundaries. Together with other advanced components including joint video prediction, shared soft attention, and boundary-aware video encoding, our integrated video captioning framework can discover hierarchical language information and distinguish the subject and the object in a sentence, which are usually confusing during the language generation. Extensive experiments on two widely-used video captioning datasets, MSR-Video-to-Text (MSR-VTT) \cite{xu2016msr} and YouTube-to-Text (MSVD) \cite{chen2011collecting} show that our method is highly competitive, compared with the state-of-the-art methods.

##### Abstract (translated by Google)
互联网上视频数据的激增需要有效且高效的技术，以便为无法观看视频的人自动生成字幕。尽管视频字幕研究取得了很大进展，特别是在视频特征编码方面，语言解码器仍然主要基于流行的RNN解码器，例如LSTM，它倾向于选择与视频对齐的频繁字。在本文中，我们提出了一种用于视频字幕的边界感知分层语言解码器，它包括一个基于GRU的高级语言解码器，作为全局（字幕级）语言模型和一个基于GRU的低级语言解码器。 ，作为本地（短语级）语言模型。最重要的是，我们将二进制门引入低级GRU语言解码器以检测语言边界。与其他高级组件（包括联合视频预测，共享软注意和边界感知视频编码）一起，我们的集成视频字幕框架可以发现分层语言信息并区分句子中的主题和对象，这在语言生成过程中通常会令人困惑。两个广泛使用的视频字幕数据集的广泛实验，MSR-Video-to-Text（MSR-VTT）\ cite {xu2016msr}和YouTube-to-Text（MSVD）\ cite {chen2011collecting}表明我们的方法具有很强的竞争力，与最先进的方法相比。

##### URL
[http://arxiv.org/abs/1807.03658](http://arxiv.org/abs/1807.03658)

##### PDF
[http://arxiv.org/pdf/1807.03658](http://arxiv.org/pdf/1807.03658)

