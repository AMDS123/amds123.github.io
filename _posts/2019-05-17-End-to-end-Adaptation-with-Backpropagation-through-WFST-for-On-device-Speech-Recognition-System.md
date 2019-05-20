---
layout: post
title: "End-to-end Adaptation with Backpropagation through WFST for On-device Speech Recognition System"
date: 2019-05-17 07:49:33
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Emiru Tsunoo, Yosuke Kashiwagi, Satoshi Asakawa, Toshiyuki Kumakura
mathjax: true
---

* content
{:toc}

##### Abstract
An on-device DNN-HMM speech recognition system efficiently works with a limited vocabulary in the presence of a variety of predictable noise. In such a case, vocabulary and environment adaptation is highly effective. In this paper, we propose a novel method of end-to-end (E2E) adaptation, which adjusts not only an acoustic model (AM) but also a weighted finite-state transducer (WFST). We convert a pretrained WFST to a trainable neural network and adapt the system to target environments/vocabulary by E2E joint training with an AM. We replicate Viterbi decoding with forward--backward neural network computation, which is similar to recurrent neural networks (RNNs). By pooling output score sequences, a vocabulary posterior for each utterance is obtained and used for discriminative loss computation. Experiments using 2--10 hours of English/Japanese adaptation datasets indicate that the fine-tuning of only WFSTs and that of only AMs are both comparable to a state-of-the-art adaptation method, and E2E joint training of the two components achieves the best recognition performance. We also adapt each language system to the other language using the adaptation data, and the results show that the proposed method also works well for language adaptations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07149](http://arxiv.org/abs/1905.07149)

##### PDF
[http://arxiv.org/pdf/1905.07149](http://arxiv.org/pdf/1905.07149)

