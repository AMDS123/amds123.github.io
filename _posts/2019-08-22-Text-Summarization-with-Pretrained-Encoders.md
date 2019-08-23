---
layout: post
title: "Text Summarization with Pretrained Encoders"
date: 2019-08-22 12:59:40
categories: arXiv_CL
tags: arXiv_CL Summarization Language_Model
author: Yang Liu, Mirella Lapata
mathjax: true
---

* content
{:toc}

##### Abstract
Bidirectional Encoder Representations from Transformers (BERT) represents the latest incarnation of pretrained language models which have recently advanced a wide range of natural language processing tasks. In this paper, we showcase how BERT can be usefully applied in text summarization and propose a general framework for both extractive and abstractive models. We introduce a novel document-level encoder based on BERT which is able to express the semantics of a document and obtain representations for its sentences. Our extractive model is built on top of this encoder by stacking several inter-sentence Transformer layers. For abstractive summarization, we propose a new fine-tuning schedule which adopts different optimizers for the encoder and the decoder as a means of alleviating the mismatch between the two (the former is pretrained while the latter is not). We also demonstrate that a two-staged fine-tuning approach can further boost the quality of the generated summaries. Experiments on three datasets show that our model achieves state-of-the-art results across the board in both extractive and abstractive settings. Our code is available at this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08345](https://arxiv.org/abs/1908.08345)

##### PDF
[https://arxiv.org/pdf/1908.08345](https://arxiv.org/pdf/1908.08345)

