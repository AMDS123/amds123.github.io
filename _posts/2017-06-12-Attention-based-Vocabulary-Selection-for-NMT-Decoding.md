---
layout: post
title: "Attention-based Vocabulary Selection for NMT Decoding"
date: 2017-06-12 19:51:00
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Baskaran Sankaran, Markus Freitag, Yaser Al-Onaizan
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) models usually use large target vocabulary sizes to capture most of the words in the target language. The vocabulary size is a big factor when decoding new sentences as the final softmax layer normalizes over all possible target words. To address this problem, it is widely common to restrict the target vocabulary with candidate lists based on the source sentence. Usually, the candidate lists are a combination of external word-to-word aligner, phrase table entries or most frequent words. In this work, we propose a simple and yet novel approach to learn candidate lists directly from the attention layer during NMT training. The candidate lists are highly optimized for the current NMT model and do not need any external computation of the candidate pool. We show significant decoding speedup compared with using the entire vocabulary, without losing any translation quality for two language pairs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.03824](https://arxiv.org/abs/1706.03824)

##### PDF
[https://arxiv.org/pdf/1706.03824](https://arxiv.org/pdf/1706.03824)

