---
layout: post
title: "Language Transfer of Audio Word2Vec: Learning Audio Segment Representations without Target Language Data"
date: 2017-07-19 10:54:00
categories: arXiv_CL
tags: arXiv_CL Language_Model Detection
author: Chia-Hao Shen, Janet Y. Sung, Hung-Yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Audio Word2Vec offers vector representations of fixed dimensionality for variable-length audio segments using Sequence-to-sequence Autoencoder (SA). These vector representations are shown to describe the sequential phonetic structures of the audio segments to a good degree, with real world applications such as query-by-example Spoken Term Detection (STD). This paper examines the capability of language transfer of Audio Word2Vec. We train SA from one language (source language) and use it to extract the vector representation of the audio segments of another language (target language). We found that SA can still catch phonetic structure from the audio segments of the target language if the source and target languages are similar. In query-by-example STD, we obtain the vector representations from the SA learned from a large amount of source language data, and found them surpass the representations from naive encoder and SA directly learned from a small amount of target language data. The result shows that it is possible to learn Audio Word2Vec model from high-resource languages and use it on low-resource languages. This further expands the usability of Audio Word2Vec.

##### Abstract (translated by Google)
音频Word2Vec使用序列到序列自动编码器（SA）为可变长度的音频片段提供固定维度的矢量表示。这些矢量表示被示出以很好的程度描述音频段的顺序语音结构，并且通过例如查询语音检测（STD）等现实世界的应用。本文考察了Audio Word2Vec的语言转换能力。我们从一种语言（源语言）训练SA，并使用它来提取另一种语言（目标语言）的音频段的矢量表示。我们发现，如果源语言和目标语言相似，SA仍然可以从目标语言的音频段抓住语音结构。在实例查询STD中，我们从大量的源语言数据中获得了来自SA的向量表示，发现它们超过了从少量目标语言数据直接学习到的朴素编码器和SA的表示。结果表明，可以从高资源语言中学习Audio Word2Vec模型，并将其用于低资源语言。这进一步扩大了音频Word2Vec的可用性。

##### URL
[https://arxiv.org/abs/1707.06519](https://arxiv.org/abs/1707.06519)

##### PDF
[https://arxiv.org/pdf/1707.06519](https://arxiv.org/pdf/1707.06519)

