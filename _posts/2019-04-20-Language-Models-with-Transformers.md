---
layout: post
title: "Language Models with Transformers"
date: 2019-04-20 06:43:14
categories: arXiv_AI
tags: arXiv_AI Attention RNN Language_Model
author: Chenguang Wang, Mu Li, Alexander J. Smola
mathjax: true
---

* content
{:toc}

##### Abstract
The Transformer architecture is superior to RNN-based models in computational efficiency. Recently, GPT and BERT demonstrate the efficacy of Transformer models on various NLP tasks using pre-trained language models on large-scale corpora. Surprisingly, these Transformer architectures are suboptimal for language model itself. Neither self-attention nor the positional encoding in the Transformer is able to efficiently incorporate the word-level sequential context crucial to language modeling. 
 In this paper, we explore effective Transformer architectures for language model, including adding additional LSTM layers to better capture the sequential context while still keeping the computation efficient. We propose Coordinate Architecture Search (CAS) to find an effective architecture through iterative refinement of the model. Experimental results on the PTB, WikiText-2, and WikiText-103 show that CAS achieves perplexities between 20.42 and 34.11 on all problems, i.e. on average an improvement of 12.0 perplexity units compared to state-of-the-art LSTMs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09408](http://arxiv.org/abs/1904.09408)

##### PDF
[http://arxiv.org/pdf/1904.09408](http://arxiv.org/pdf/1904.09408)

