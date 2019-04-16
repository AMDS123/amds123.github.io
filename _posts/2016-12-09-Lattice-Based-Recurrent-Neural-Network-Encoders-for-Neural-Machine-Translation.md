---
layout: post
title: "Lattice-Based Recurrent Neural Network Encoders for Neural Machine Translation"
date: 2016-12-09 13:03:42
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Jinsong Su, Zhixing Tan, Deyi Xiong, Rongrong Ji, Xiaodong Shi, Yang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) heavily relies on word-level modelling to learn semantic representations of input sentences. However, for languages without natural word delimiters (e.g., Chinese) where input sentences have to be tokenized first, conventional NMT is confronted with two issues: 1) it is difficult to find an optimal tokenization granularity for source sentence modelling, and 2) errors in 1-best tokenizations may propagate to the encoder of NMT. To handle these issues, we propose word-lattice based Recurrent Neural Network (RNN) encoders for NMT, which generalize the standard RNN to word lattice topology. The proposed encoders take as input a word lattice that compactly encodes multiple tokenizations, and learn to generate new hidden states from arbitrarily many inputs and hidden states in preceding time steps. As such, the word-lattice based encoders not only alleviate the negative impact of tokenization errors but also are more expressive and flexible to embed input sentences. Experiment results on Chinese-English translation demonstrate the superiorities of the proposed encoders over the conventional encoder.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1609.07730](https://arxiv.org/abs/1609.07730)

##### PDF
[https://arxiv.org/pdf/1609.07730](https://arxiv.org/pdf/1609.07730)

