---
layout: post
title: "Refining Source Representations with Relation Networks for Neural Machine Translation"
date: 2017-11-08 08:20:13
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Wen Zhang, Jiawei Hu, Yang Feng, Qun Liu
---

* content
{:toc}

##### Abstract
Although neural machine translation (NMT) with the encoder-decoder framework has achieved great success in recent times, it still suffers from some drawbacks: RNNs tend to forget old information which is often useful and the encoder only operates through words without considering word relationship. To solve these problems, we introduce a relation networks (RN) into NMT to refine the encoding representations of the source. In our method, the RN first augments the representation of each source word with its neighbors and reasons all the possible pairwise relations between them. Then the source representations and all the relations are fed to the attention module and the decoder together, keeping the main encoder-decoder architecture unchanged. Experiments on two Chinese-to-English data sets in different scales both show that our method can outperform the competitive baselines significantly.

##### Abstract (translated by Google)
尽管神经机器翻译（NMT）与编码器 - 解码器框架在近代取得了巨大的成功，但它仍然存在一些缺点：RNN倾向于遗忘通常有用的旧信息，并且编码器仅通过单词操作，而不考虑单词关系。为了解决这些问题，我们将一个关系网络（RN）引入到NMT中以改进源的编码表示。在我们的方法中，RN首先用邻居来增强每个源词的表示，并且推导它们之间所有可能的成对关系。然后源表示和所有的关系一起被馈送到关注模块和解码器，保持主编码器 - 解码器结构不变。对两个不同尺度的汉英数据集进行的实验都表明，我们的方法可以显着地超越竞争的基线。

##### URL
[https://arxiv.org/abs/1709.03980](https://arxiv.org/abs/1709.03980)

