---
layout: post
title: "Hybrid Data-Model Parallel Training for Sequence-to-Sequence Recurrent Neural Network Machine Translation"
date: 2019-09-02 06:41:34
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Junya Ono, Masao Utiyama, Eiichiro Sumita
mathjax: true
---

* content
{:toc}

##### Abstract
Reduction of training time is an important issue in many tasks like patent translation involving neural networks. Data parallelism and model parallelism are two common approaches for reducing training time using multiple graphics processing units (GPUs) on one machine. In this paper, we propose a hybrid data-model parallel approach for sequence-to-sequence (Seq2Seq) recurrent neural network (RNN) machine translation. We apply a model parallel approach to the RNN encoder-decoder part of the Seq2Seq model and a data parallel approach to the attention-softmax part of the model. We achieved a speed-up of 4.13 to 4.20 times when using 4 GPUs compared with the training speed when using 1 GPU without affecting machine translation accuracy as measured in terms of BLEU scores.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00562](http://arxiv.org/abs/1909.00562)

##### PDF
[http://arxiv.org/pdf/1909.00562](http://arxiv.org/pdf/1909.00562)

