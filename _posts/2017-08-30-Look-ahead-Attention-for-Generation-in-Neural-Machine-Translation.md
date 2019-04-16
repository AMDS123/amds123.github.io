---
layout: post
title: "Look-ahead Attention for Generation in Neural Machine Translation"
date: 2017-08-30 11:27:02
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN Relation
author: Long Zhou, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
The attention model has become a standard component in neural machine translation (NMT) and it guides translation process by selectively focusing on parts of the source sentence when predicting each target word. However, we find that the generation of a target word does not only depend on the source sentence, but also rely heavily on the previous generated target words, especially the distant words which are difficult to model by using recurrent neural networks. To solve this problem, we propose in this paper a novel look-ahead attention mechanism for generation in NMT, which aims at directly capturing the dependency relationship between target words. We further design three patterns to integrate our look-ahead attention into the conventional attention model. Experiments on NIST Chinese-to-English and WMT English-to-German translation tasks show that our proposed look-ahead attention mechanism achieves substantial improvements over state-of-the-art baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.09217](https://arxiv.org/abs/1708.09217)

##### PDF
[https://arxiv.org/pdf/1708.09217](https://arxiv.org/pdf/1708.09217)

