---
layout: post
title: "Neural Machine Translation with Characters and Hierarchical Encoding"
date: 2016-10-20 19:33:02
categories: arXiv_CL
tags: arXiv_CL Attention Embedding
author: Alexander Rosenberg Johansen, Jonas Meinertz Hansen, Elias Khazen Obeid, Casper Kaae Sønderby, Ole Winther
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing Neural Machine Translation models use groups of characters or whole words as their unit of input and output. We propose a model with a hierarchical char2word encoder, that takes individual characters both as input and output. We first argue that this hierarchical representation of the character encoder reduces computational complexity, and show that it improves translation performance. Secondly, by qualitatively studying attention plots from the decoder we find that the model learns to compress common words into a single embedding whereas rare words, such as names and places, are represented character by character.

##### Abstract (translated by Google)
大多数现有的神经机器翻译模型使用字符组或全字作为其输入和输出的单位。我们提出了一个带有分层char2word编码器的模型，它将单个字符作为输入和输出。我们首先认为，这种字符编码器的分层表示降低了计算复杂度，并表明它提高了翻译性能。其次，通过定性研究解码器的注意力图，我们发现模型学习将常见单词压缩成一个单一的嵌入，而罕见的单词，如名字和地方，是逐字符表示的。

##### URL
[https://arxiv.org/abs/1610.06550](https://arxiv.org/abs/1610.06550)

##### PDF
[https://arxiv.org/pdf/1610.06550](https://arxiv.org/pdf/1610.06550)

