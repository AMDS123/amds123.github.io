---
layout: post
title: "Chunk-Based Bi-Scale Decoder for Neural Machine Translation"
date: 2017-05-03 14:39:56
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Hao Zhou, Zhaopeng Tu, Shujian Huang, Xiaohua Liu, Hang Li, Jiajun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In typical neural machine translation~(NMT), the decoder generates a sentence word by word, packing all linguistic granularities in the same time-scale of RNN. In this paper, we propose a new type of decoder for NMT, which splits the decode state into two parts and updates them in two different time-scales. Specifically, we first predict a chunk time-scale state for phrasal modeling, on top of which multiple word time-scale states are generated. In this way, the target sentence is translated hierarchically from chunks to words, with information in different granularities being leveraged. Experiments show that our proposed model significantly improves the translation performance over the state-of-the-art NMT model.

##### Abstract (translated by Google)
在典型的神经机器翻译〜（NMT）中，解码器逐字地生成一个句子，将相同时间尺度的所有语言粒度进行打包。在本文中，我们提出了一种新型的NMT解码器，它将解码状态分为两部分，并在两个不同的时间尺度上进行更新。具体而言，我们首先预测短语建模的块时间尺度状态，在其上面生成多个时间尺度状态。通过这种方式，目标句子从块到词被分层次地转换，并利用不同粒度的信息。实验表明，我们提出的模型显着提高了最先进的NMT模型的翻译性能。

##### URL
[https://arxiv.org/abs/1705.01452](https://arxiv.org/abs/1705.01452)

