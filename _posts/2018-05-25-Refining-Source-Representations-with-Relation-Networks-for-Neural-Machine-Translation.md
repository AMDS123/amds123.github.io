---
layout: post
title: "Refining Source Representations with Relation Networks for Neural Machine Translation"
date: 2018-05-25 13:36:08
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN Relation
author: Wen Zhang, Jiawei Hu, Yang Feng, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Although neural machine translation (NMT) with the encoder-decoder framework has achieved great success in recent times, it still suffers from some drawbacks: RNNs tend to forget old information which is often useful and the encoder only operates through words without considering word relationship. To solve these problems, we introduce a relation networks (RN) into NMT to refine the encoding representations of the source. In our method, the RN first augments the representation of each source word with its neighbors and reasons all the possible pairwise relations between them. Then the source representations and all the relations are fed to the attention module and the decoder together, keeping the main encoder-decoder architecture unchanged. Experiments on two Chinese-to-English data sets in different scales both show that our method can outperform the competitive baselines significantly.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.03980](https://arxiv.org/abs/1709.03980)

##### PDF
[https://arxiv.org/e-print/1709.03980](https://arxiv.org/e-print/1709.03980)

