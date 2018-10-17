---
layout: post
title: "Trellis Networks for Sequence Modeling"
date: 2018-10-15 20:50:05
categories: arXiv_AI
tags: arXiv_AI CNN Language_Model
author: Shaojie Bai, J. Zico Kolter, Vladlen Koltun
mathjax: true
---

* content
{:toc}

##### Abstract
We present trellis networks, a new architecture for sequence modeling. On the one hand, a trellis network is a temporal convolutional network with special structure, characterized by weight tying across depth and direct injection of the input into deep layers. On the other hand, we show that truncated recurrent networks are equivalent to trellis networks with special sparsity structure in their weight matrices. Thus trellis networks with general weight matrices generalize truncated recurrent networks. We leverage these connections to design high-performing trellis networks that absorb structural and algorithmic elements from both recurrent and convolutional models. Experiments demonstrate that trellis networks outperform the current state of the art on a variety of challenging benchmarks, including word-level language modeling on Penn Treebank and WikiText-103, character-level language modeling on Penn Treebank, and stress tests designed to evaluate long-term memory retention. The code is available at https://github.com/locuslab/trellisnet .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06682](http://arxiv.org/abs/1810.06682)

##### PDF
[http://arxiv.org/pdf/1810.06682](http://arxiv.org/pdf/1810.06682)

