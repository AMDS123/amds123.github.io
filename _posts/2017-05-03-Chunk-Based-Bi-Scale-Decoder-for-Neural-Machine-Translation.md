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


##### URL
[https://arxiv.org/abs/1705.01452](https://arxiv.org/abs/1705.01452)

##### PDF
[https://arxiv.org/pdf/1705.01452](https://arxiv.org/pdf/1705.01452)

