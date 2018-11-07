---
layout: post
title: "Language model integration based on memory control for sequence to sequence speech recognition"
date: 2018-11-06 04:56:44
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Transfer_Learning Inference RNN Language_Model Recognition
author: Jaejin Cho, Shinji Watanabe, Takaaki Hori, Murali Karthick Baskar, Hirofumi Inaguma, Jesus Villalba, Najim Dehak
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore several new schemes to train a seq2seq model to integrate a pre-trained LM. Our proposed fusion methods focus on the memory cell state and the hidden state in the seq2seq decoder long short-term memory (LSTM), and the memory cell state is updated by the LM unlike the prior studies. This means the memory retained by the main seq2seq would be adjusted by the external LM. These fusion methods have several variants depending on the architecture of this memory cell update and the use of memory cell and hidden states which directly affects the final label inference. We performed the experiments to show the effectiveness of the proposed methods in a mono-lingual ASR setup on the Librispeech corpus and in a transfer learning setup from a multilingual ASR (MLASR) base model to a low-resourced language. In Librispeech, our best model improved WER by 3.7%, 2.4% for test clean, test other relatively to the shallow fusion baseline, with multi-level decoding. In transfer learning from an MLASR base model to the IARPA Babel Swahili model, the best scheme improved the transferred model on eval set by 9.9%, 9.8% in CER, WER relatively to the 2-stage transfer baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02162](http://arxiv.org/abs/1811.02162)

##### PDF
[http://arxiv.org/pdf/1811.02162](http://arxiv.org/pdf/1811.02162)

