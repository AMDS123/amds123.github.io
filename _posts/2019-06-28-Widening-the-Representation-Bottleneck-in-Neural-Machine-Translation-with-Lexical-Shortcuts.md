---
layout: post
title: "Widening the Representation Bottleneck in Neural Machine Translation with Lexical Shortcuts"
date: 2019-06-28 16:14:06
categories: arXiv_CL
tags: arXiv_CL Attention Embedding
author: Denis Emelin, Ivan Titov, Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
The transformer is a state-of-the-art neural translation model that uses attention to iteratively refine lexical representations with information drawn from the surrounding context. Lexical features are fed into the first layer and propagated through a deep network of hidden layers. We argue that the need to represent and propagate lexical features in each layer limits the model's capacity for learning and representing other information relevant to the task. To alleviate this bottleneck, we introduce gated shortcut connections between the embedding layer and each subsequent layer within the encoder and decoder. This enables the model to access relevant lexical content dynamically, without expending limited resources on storing it within intermediate states. We show that the proposed modification yields consistent improvements over a baseline transformer on standard WMT translation tasks in 5 translation directions (0.9 BLEU on average) and reduces the amount of lexical information passed along the hidden layers. We furthermore evaluate different ways to integrate lexical connections into the transformer architecture and present ablation experiments exploring the effect of proposed shortcuts on model behavior.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12284](http://arxiv.org/abs/1906.12284)

##### PDF
[http://arxiv.org/pdf/1906.12284](http://arxiv.org/pdf/1906.12284)

