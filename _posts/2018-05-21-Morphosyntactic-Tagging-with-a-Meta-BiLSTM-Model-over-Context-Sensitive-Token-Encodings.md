---
layout: post
title: "Morphosyntactic Tagging with a Meta-BiLSTM Model over Context Sensitive Token Encodings"
date: 2018-05-21 18:09:23
categories: arXiv_CL
tags: arXiv_CL Embedding RNN
author: Bernd Bohnet, Ryan McDonald, Goncalo Simoes, Daniel Andor, Emily Pitler, Joshua Maynez
mathjax: true
---

* content
{:toc}

##### Abstract
The rise of neural networks, and particularly recurrent neural networks, has produced significant advances in part-of-speech tagging accuracy. One characteristic common among these models is the presence of rich initial word encodings. These encodings typically are composed of a recurrent character-based representation with learned and pre-trained word embeddings. However, these encodings do not consider a context wider than a single word and it is only through subsequent recurrent layers that word or sub-word information interacts. In this paper, we investigate models that use recurrent neural networks with sentence-level context for initial character and word-based representations. In particular we show that optimal results are obtained by integrating these context sensitive representations through synchronized training with a meta-model that learns to combine their states. We present results on part-of-speech and morphological tagging with state-of-the-art performance on a number of languages.

##### Abstract (translated by Google)
神经网络，特别是递归神经网络的兴起，在词性标注精度方面取得了显着的进步。这些模型的一个共同特点是存在丰富的初始字编码。这些编码通常由带有学习和预先训练的字嵌入的基于字符的循环表示组成。但是，这些编码不考虑比单个单词更宽泛的上下文，并且仅通过随后的循环层来使单词或子词信息相互作用。在本文中，我们调查使用循环神经网络与句子级上下文初始字符和基于词表示的模型。具体而言，我们展示了通过将这些上下文敏感表示通过与学习结合其状态的元模型的同步训练相结合来获得最佳结果。我们用多种语言呈现了词性和形态标记以及最新性能的结果。

##### URL
[https://arxiv.org/abs/1805.08237](https://arxiv.org/abs/1805.08237)

##### PDF
[https://arxiv.org/pdf/1805.08237](https://arxiv.org/pdf/1805.08237)

