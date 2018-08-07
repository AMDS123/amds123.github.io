---
layout: post
title: "Recurrent Memory Addressing for describing videos"
date: 2017-03-23 14:01:20
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption Embedding Memory_Networks
author: Arnav Kumar Jain, Abhinav Agarwalla, Kumar Krishna Agrawal, Pabitra Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce Key-Value Memory Networks to a multimodal setting and a novel key-addressing mechanism to deal with sequence-to-sequence models. The proposed model naturally decomposes the problem of video captioning into vision and language segments, dealing with them as key-value pairs. More specifically, we learn a semantic embedding (v) corresponding to each frame (k) in the video, thereby creating (k, v) memory slots. We propose to find the next step attention weights conditioned on the previous attention distributions for the key-value memory slots in the memory addressing schema. Exploiting this flexibility of the framework, we additionally capture spatial dependencies while mapping from the visual to semantic embedding. Experiments done on the Youtube2Text dataset demonstrate usefulness of recurrent key-addressing, while achieving competitive scores on BLEU@4, METEOR metrics against state-of-the-art models.

##### Abstract (translated by Google)
在本文中，我们将密钥值存储器网络引入多模式设置和一种新的密钥寻址机制来处理序列到序列模型。所提出的模型自然地将视频字幕的问题分解为视觉和语言片段，将它们作为键值对处理。更具体地，我们学习与视频中的每个帧（k）相对应的语义嵌入（v），从而创建（k，v）个存储器时隙。我们建议在存储器寻址模式中的键值存储器插槽的先前关注分布的条件下找到下一步注意权重。利用框架的这种灵活性，我们还可以在从视觉嵌入到语义嵌入的映射中捕获空间依赖性。在Youtube2Text数据集上进行的实验证明了循环密钥寻址的有用性，同时在针对最先进模型的BLEU @ 4，METEOR指标上获得了竞争性分数。

##### URL
[https://arxiv.org/abs/1611.06492](https://arxiv.org/abs/1611.06492)

##### PDF
[https://arxiv.org/pdf/1611.06492](https://arxiv.org/pdf/1611.06492)

