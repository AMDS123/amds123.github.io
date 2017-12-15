---
layout: post
title: "Neural Language Correction with Character-Based Attention"
date: 2016-03-31 19:16:54
categories: arXiv_SD
tags: arXiv_SD Attention Language_Model
author: Ziang Xie, Anand Avati, Naveen Arivazhagan, Dan Jurafsky, Andrew Y. Ng
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language correction has the potential to help language learners improve their writing skills. While approaches with separate classifiers for different error types have high precision, they do not flexibly handle errors such as redundancy or non-idiomatic phrasing. On the other hand, word and phrase-based machine translation methods are not designed to cope with orthographic errors, and have recently been outpaced by neural models. Motivated by these issues, we present a neural network-based approach to language correction. The core component of our method is an encoder-decoder recurrent neural network with an attention mechanism. By operating at the character level, the network avoids the problem of out-of-vocabulary words. We illustrate the flexibility of our approach on dataset of noisy, user-generated text collected from an English learner forum. When combined with a language model, our method achieves a state-of-the-art $F_{0.5}$-score on the CoNLL 2014 Shared Task. We further demonstrate that training the network on additional data with synthesized errors can improve performance.

##### Abstract (translated by Google)
自然语言矫正可以帮助语言学习者提高写作技巧。虽然针对不同错误类型使用不同分类器的方法具有较高的精度，但它们不能灵活地处理诸如冗余或非惯用措辞的错误。另一方面，基于单词和短语的机器翻译方法并不是为了处理拼字错误而设计的，最近已经被神经模型所超越。受到这些问题的启发，我们提出了一种基于神经网络的语言矫正方法。我们方法的核心部分是具有注意机制的编码器 - 解码器递归神经网络。通过在人物层面进行操作，网络避免了词汇之外的问题。我们说明了我们的方法在从英语学习者论坛收集的嘈杂的，用户生成的文本的数据集上的灵活性。当与语言模型相结合时，我们的方法在CoNLL 2014共享任务上实现了最新的$ F_ {0.5} $  - 分值。我们进一步证明，通过合成错误对附加数据进行网络训练可以提高性能。

##### URL
[https://arxiv.org/abs/1603.09727](https://arxiv.org/abs/1603.09727)

##### PDF
[https://arxiv.org/pdf/1603.09727](https://arxiv.org/pdf/1603.09727)

