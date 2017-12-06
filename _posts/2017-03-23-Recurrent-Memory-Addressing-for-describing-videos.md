---
layout: post
title: 'Recurrent Memory Addressing for describing videos'
date: 2017-03-23 14:01:20
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Memory_Networks
author: Arnav Kumar Jain, Abhinav Agarwalla, Kumar Krishna Agrawal, Pabitra Mitra
---

* content
{:toc}

##### Abstract
In this paper, we introduce Key-Value Memory Networks to a multimodal setting and a novel key-addressing mechanism to deal with sequence-to-sequence models. The proposed model naturally decomposes the problem of video captioning into vision and language segments, dealing with them as key-value pairs. More specifically, we learn a semantic embedding (v) corresponding to each frame (k) in the video, thereby creating (k, v) memory slots. We propose to find the next step attention weights conditioned on the previous attention distributions for the key-value memory slots in the memory addressing schema. Exploiting this flexibility of the framework, we additionally capture spatial dependencies while mapping from the visual to semantic embedding. Experiments done on the Youtube2Text dataset demonstrate usefulness of recurrent key-addressing, while achieving competitive scores on BLEU@4, METEOR metrics against state-of-the-art models.

##### Abstract (translated by Google)
在本文中，我们将键值存储器网络引入到多模式设置和一种处理序列到序列模型的新型关键寻址机制中。所提出的模型自然将视频字幕的问题分解成视觉和语言片段，将它们作为键值对处理。更具体地说，我们学习了对应于视频中的每个帧（k）的语义嵌入（v），从而创建（k，v）个存储器槽。我们建议在内存寻址模式中找出下一步注意权重，这些权重以先前的关注分布为关键值内存槽位。利用框架的这种灵活性，我们另外捕获了从视觉到语义嵌入的空间依赖关系。在Youtube2Text数据集上进行的实验证明了经常性键盘寻址的有效性，同时在BLEU @ 4，METEOR指标上获得了与最先进的模型相媲美的分数。

##### URL
[https://arxiv.org/abs/1611.06492](https://arxiv.org/abs/1611.06492)

