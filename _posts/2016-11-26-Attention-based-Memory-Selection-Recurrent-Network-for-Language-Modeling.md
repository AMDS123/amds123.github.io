---
layout: post
title: "Attention-based Memory Selection Recurrent Network for Language Modeling"
date: 2016-11-26 04:25:00
categories: arXiv_CV
tags: arXiv_CV Review Attention RNN Language_Model
author: Da-Rong Liu, Shun-Po Chuang, Hung-yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have achieved great success in language modeling. However, since the RNNs have fixed size of memory, their memory cannot store all the information about the words it have seen before in the sentence, and thus the useful long-term information may be ignored when predicting the next words. In this paper, we propose Attention-based Memory Selection Recurrent Network (AMSRN), in which the model can review the information stored in the memory at each previous time step and select the relevant information to help generate the outputs. In AMSRN, the attention mechanism finds the time steps storing the relevant information in the memory, and memory selection determines which dimensions of the memory are involved in computing the attention weights and from which the information is extracted.In the experiments, AMSRN outperformed long short-term memory (LSTM) based language models on both English and Chinese corpora. Moreover, we investigate using entropy as a regularizer for attention weights and visualize how the attention mechanism helps language modeling.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.08656](https://arxiv.org/abs/1611.08656)

##### PDF
[https://arxiv.org/pdf/1611.08656](https://arxiv.org/pdf/1611.08656)

