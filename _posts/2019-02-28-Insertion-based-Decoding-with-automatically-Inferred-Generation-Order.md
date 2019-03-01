---
layout: post
title: "Insertion-based Decoding with automatically Inferred Generation Order"
date: 2019-02-28 18:56:48
categories: arXiv_CL
tags: arXiv_CL Image_Caption Caption
author: Jiatao Gu, Qi Liu, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional neural autoregressive decoding commonly assumes a fixed left-to-right generation order, which may be sub-optimal. In this work, we propose a novel decoding algorithm -- InDIGO -- which supports flexible sequence generation in arbitrary orders through insertion operations. We extend Transformer, a state-of-the-art sequence generation model, to efficiently implement the proposed approach, enabling it to be trained with either a pre-defined generation order or adaptive orders obtained from beam-search. Experiments on four real-world tasks, including word order recovery, machine translation, image caption and code generation, demonstrate that our algorithm can generate sequences following arbitrary orders, while achieving competitive or even better performance compared to the conventional left-to-right generation. The generated sequences show that InDIGO adopts adaptive generation orders based on input information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01370](http://arxiv.org/abs/1902.01370)

##### PDF
[http://arxiv.org/pdf/1902.01370](http://arxiv.org/pdf/1902.01370)

