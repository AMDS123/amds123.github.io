---
layout: post
title: "Bidirectional Attentional Encoder-Decoder Model and Bidirectional Beam Search for Abstractive Summarization"
date: 2018-09-18 12:18:22
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Summarization Inference RNN Prediction
author: Kamal Al-Sabahi, Zhang Zuping, Yang Kang
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence generative models with RNN variants, such as LSTM, GRU, show promising performance on abstractive document summarization. However, they still have some issues that limit their performance, especially while deal-ing with long sequences. One of the issues is that, to the best of our knowledge, all current models employ a unidirectional decoder, which reasons only about the past and still limited to retain future context while giving a prediction. This makes these models suffer on their own by generating unbalanced outputs. Moreover, unidirec-tional attention-based document summarization can only capture partial aspects of attentional regularities due to the inherited challenges in document summarization. To this end, we propose an end-to-end trainable bidirectional RNN model to tackle the aforementioned issues. The model has a bidirectional encoder-decoder architecture; in which the encoder and the decoder are bidirectional LSTMs. The forward decoder is initialized with the last hidden state of the backward encoder while the backward decoder is initialized with the last hidden state of the for-ward encoder. In addition, a bidirectional beam search mechanism is proposed as an approximate inference algo-rithm for generating the output summaries from the bidi-rectional model. This enables the model to reason about the past and future and to generate balanced outputs as a result. Experimental results on CNN / Daily Mail dataset show that the proposed model outperforms the current abstractive state-of-the-art models by a considerable mar-gin.

##### Abstract (translated by Google)
具有RNN变体的序列生成模型，例如LSTM，GRU，在抽象文档概述上显示出有希望的性能。但是，它们仍然存在一些限制其性能的问题，尤其是在处理长序列时。其中一个问题是，据我们所知，所有当前模型都采用单向解码器，这只能解释过去，并且仍然限制在给出预测的同时保留未来的上下文。这使得这些模型通过产生不平衡输出而自行受损。此外，由于文档摘要中的继承挑战，基于注意力的单向文档摘要只能捕获注意力规则的部分方面。为此，我们提出了一种端到端的可训练双向RNN模型来解决上述问题。该模型具有双向编码器 - 解码器架构;其中编码器和解码器是双向LSTM。正向解码器用反向编码器的最后隐藏状态初始化，而反向解码器用向前编码器的最后隐藏状态初始化。此外，提出了一种双向波束搜索机制作为近似推断算法，用于生成来自双向模型的输出摘要。这使模型能够推断过去和未来，并因此产生平衡的输出。在CNN /每日邮报数据集上的实验结果表明，所提出的模型通过相当大的差距优于当前抽象的最先进模型。

##### URL
[http://arxiv.org/abs/1809.06662](http://arxiv.org/abs/1809.06662)

##### PDF
[http://arxiv.org/pdf/1809.06662](http://arxiv.org/pdf/1809.06662)

