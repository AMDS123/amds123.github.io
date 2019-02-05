---
layout: post
title: "Insertion-based Decoding with Automatically Inferred Generation Order"
date: 2019-02-04 18:35:59
categories: arXiv_CL
tags: arXiv_CL
author: Jiatao Gu, Qi Liu, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional neural autoregressive decoding commonly assumes a left-to-right generation order. In this work, we propose a novel decoding algorithm -- INDIGO -- which supports flexible generation in an arbitrary order with the help of insertion operations. We use Transformer, a state-of-the-art sequence generation model, to efficiently implement the proposed approach, enabling it to be trained with either a pre-defined generation order or an adaptive order searched based on the model's own preference. Experiments on three real-world tasks, including machine translation, word order recovery and code generation, demonstrate that our algorithm can generate sequences in an arbitrary order, while achieving competitive or even better performance compared to the conventional left-to-right generation. Case studies show that INDIGO adopts adaptive generation orders based on input information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01370](http://arxiv.org/abs/1902.01370)

##### PDF
[http://arxiv.org/pdf/1902.01370](http://arxiv.org/pdf/1902.01370)

