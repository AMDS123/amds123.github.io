---
layout: post
title: "Bidirectional Attentional Encoder-Decoder Model and Bidirectional Beam Search for Abstractive Summarization"
date: 2018-09-18 12:18:22
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Summarization Inference RNN Prediction
author: Kamal Al-Sabahi, Zhang Zuping, Yang Kang
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence generative models with RNN variants, such as LSTM, GRU, show promising performance on abstractive document summarization. However, they still have some issues that limit their performance, especially while deal-ing with long sequences. One of the issues is that, to the best of our knowledge, all current models employ a unidirectional decoder, which reasons only about the past and still limited to retain future context while giving a prediction. This makes these models suffer on their own by generating unbalanced outputs. Moreover, unidirec-tional attention-based document summarization can only capture partial aspects of attentional regularities due to the inherited challenges in document summarization. To this end, we propose an end-to-end trainable bidirectional RNN model to tackle the aforementioned issues. The model has a bidirectional encoder-decoder architecture; in which the encoder and the decoder are bidirectional LSTMs. The forward decoder is initialized with the last hidden state of the backward encoder while the backward decoder is initialized with the last hidden state of the for-ward encoder. In addition, a bidirectional beam search mechanism is proposed as an approximate inference algo-rithm for generating the output summaries from the bidi-rectional model. This enables the model to reason about the past and future and to generate balanced outputs as a result. Experimental results on CNN / Daily Mail dataset show that the proposed model outperforms the current abstractive state-of-the-art models by a considerable mar-gin.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.06662](https://arxiv.org/abs/1809.06662)

##### PDF
[https://arxiv.org/pdf/1809.06662](https://arxiv.org/pdf/1809.06662)

