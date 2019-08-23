---
layout: post
title: "'Mask and Infill' : Applying Masked Language Model to Sentiment Transfer"
date: 2019-08-21 23:12:36
categories: arXiv_CL
tags: arXiv_CL Sentiment Review RNN Language_Model Quantitative
author: Xing Wu, Tao Zhang, Liangjun Zang, Jizhong Han, Songlin Hu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on the task of sentiment transfer on non-parallel text, which modifies sentiment attributes (e.g., positive or negative) of sentences while preserving their attribute-independent content. Due to the limited capability of RNNbased encoder-decoder structure to capture deep and long-range dependencies among words, previous works can hardly generate satisfactory sentences from scratch. When humans convert the sentiment attribute of a sentence, a simple but effective approach is to only replace the original sentimental tokens in the sentence with target sentimental expressions, instead of building a new sentence from scratch. Such a process is very similar to the task of Text Infilling or Cloze, which could be handled by a deep bidirectional Masked Language Model (e.g. BERT). So we propose a two step approach "Mask and Infill". In the mask step, we separate style from content by masking the positions of sentimental tokens. In the infill step, we retrofit MLM to Attribute Conditional MLM, to infill the masked positions by predicting words or phrases conditioned on the context1 and target sentiment. We evaluate our model on two review datasets with quantitative, qualitative, and human evaluations. Experimental results demonstrate that our models improve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08039](https://arxiv.org/abs/1908.08039)

##### PDF
[https://arxiv.org/pdf/1908.08039](https://arxiv.org/pdf/1908.08039)

