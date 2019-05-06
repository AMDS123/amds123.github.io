---
layout: post
title: "Exploring Neural Transducers for End-to-End Speech Recognition"
date: 2017-07-24 06:05:21
categories: arXiv_CV
tags: arXiv_CV Attention Speech_Recognition RNN Language_Model Recognition
author: Eric Battenberg, Jitong Chen, Rewon Child, Adam Coates, Yashesh Gaur, Yi Li, Hairong Liu, Sanjeev Satheesh, David Seetapun, Anuroop Sriram, Zhenyao Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we perform an empirical comparison among the CTC, RNN-Transducer, and attention-based Seq2Seq models for end-to-end speech recognition. We show that, without any language model, Seq2Seq and RNN-Transducer models both outperform the best reported CTC models with a language model, on the popular Hub5'00 benchmark. On our internal diverse dataset, these trends continue - RNNTransducer models rescored with a language model after beam search outperform our best CTC models. These results simplify the speech recognition pipeline so that decoding can now be expressed purely as neural network operations. We also study how the choice of encoder architecture affects the performance of the three models - when all encoder layers are forward only, and when encoders downsample the input representation aggressively.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.07413](https://arxiv.org/abs/1707.07413)

##### PDF
[https://arxiv.org/pdf/1707.07413](https://arxiv.org/pdf/1707.07413)

