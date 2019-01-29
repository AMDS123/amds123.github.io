---
layout: post
title: "Intrinsically Sparse Long Short-Term Memory Networks"
date: 2019-01-26 13:17:27
categories: arXiv_CV
tags: arXiv_CV Sentiment Sparse Embedding Optimization Inference RNN Classification Memory_Networks
author: Shiwei Liu, Decebal Constantin Mocanu, Mykola Pechenizkiy
mathjax: true
---

* content
{:toc}

##### Abstract
Long Short-Term Memory (LSTM) has achieved state-of-the-art performances on a wide range of tasks. Its outstanding performance is guaranteed by the long-term memory ability which matches the sequential data perfectly and the gating structure controlling the information flow. However, LSTMs are prone to be memory-bandwidth limited in realistic applications and need an unbearable period of training and inference time as the model size is ever-increasing. To tackle this problem, various efficient model compression methods have been proposed. Most of them need a big and expensive pre-trained model which is a nightmare for resource-limited devices where the memory budget is strictly limited. To remedy this situation, in this paper, we incorporate the Sparse Evolutionary Training (SET) procedure into LSTM, proposing a novel model dubbed SET-LSTM. Rather than starting with a fully-connected architecture, SET-LSTM has a sparse topology and dramatically fewer parameters in both phases, training and inference. Considering the specific architecture of LSTMs, we replace the LSTM cells and embedding layers with sparse structures and further on, use an evolutionary strategy to adapt the sparse connectivity to the data. Additionally, we find that SET-LSTM can provide many different good combinations of sparse connectivity to substitute the overparameterized optimization problem of dense neural networks. Evaluated on four sentiment analysis classification datasets, the results demonstrate that our proposed model is able to achieve usually better performance than its fully connected counterpart while having less than 4\% of its parameters.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.09208](https://arxiv.org/abs/1901.09208)

##### PDF
[https://arxiv.org/pdf/1901.09208](https://arxiv.org/pdf/1901.09208)

