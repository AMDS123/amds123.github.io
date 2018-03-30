---
layout: post
title: "Towards Unsupervised Automatic Speech Recognition Trained by Unaligned Speech and Text only"
date: 2018-03-29 08:03:45
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding Recognition
author: Yi-Chen Chen, Chia-Hao Shen, Sung-Feng Huang, Hung-yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic speech recognition (ASR) has been widely researched with supervised approaches, while many low-resourced languages lack audio-text aligned data, and supervised methods cannot be applied on them. 
 In this work, we propose a framework to achieve unsupervised ASR on a read English speech dataset, where audio and text are unaligned. In the first stage, each word-level audio segment in the utterances is represented by a vector representation extracted by a sequence-of-sequence autoencoder, in which phonetic information and speaker information are disentangled. 
 Secondly, semantic embeddings of audio segments are trained from the vector representations using a skip-gram model. Last but not the least, an unsupervised method is utilized to transform semantic embeddings of audio segments to text embedding space, and finally the transformed embeddings are mapped to words. 
 With the above framework, we are towards unsupervised ASR trained by unaligned text and speech only.

##### Abstract (translated by Google)
自动语音识别（ASR）已经通过监督方法得到了广泛研究，而许多低资源语言缺乏音频文本对齐的数据，并且监督方法不能应用于它们。
 在这项工作中，我们提出了一个框架，在阅读英语语音数据集时实现无监督ASR，其中音频和文本不对齐。在第一阶段中，话语中的每个单词级音频片段由通过序列自动编码器提取的向量表示来表示，其中语音信息和说话者信息被解开。
 其次，使用跳跃模型从矢量表示中训练音频片段的语义嵌入。最后但并非最不重要的是，利用无监督方法将音频片段的语义嵌入转换为文本嵌入空间，最后将转换后的嵌入映射到单词。
 有了上述的框架，我们只能通过未对齐的文本和语音训练无人监督的ASR。

##### URL
[http://arxiv.org/abs/1803.10952](http://arxiv.org/abs/1803.10952)

##### PDF
[http://arxiv.org/pdf/1803.10952](http://arxiv.org/pdf/1803.10952)

