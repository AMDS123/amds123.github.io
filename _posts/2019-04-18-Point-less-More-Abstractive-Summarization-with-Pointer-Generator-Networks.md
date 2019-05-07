---
layout: post
title: "Point-less: More Abstractive Summarization with Pointer-Generator Networks"
date: 2019-04-18 22:17:21
categories: arXiv_CL
tags: arXiv_CL Attention Summarization
author: Freek Boutkan, Jorn Ranzijn, David Rau, Eelco van der Wel
mathjax: true
---

* content
{:toc}

##### Abstract
The Pointer-Generator architecture has shown to be a big improvement for abstractive summarization seq2seq models. However, the summaries produced by this model are largely extractive as over 30% of the generated sentences are copied from the source text. This work proposes a multihead attention mechanism, pointer dropout, and two new loss functions to promote more abstractive summaries while maintaining similar ROUGE scores. Both the multihead attention and dropout do not improve N-gram novelty, however, the dropout acts as a regularizer which improves the ROUGE score. The new loss function achieves significantly higher novel N-grams and sentences, at the cost of a slightly lower ROUGE score.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01975](http://arxiv.org/abs/1905.01975)

##### PDF
[http://arxiv.org/pdf/1905.01975](http://arxiv.org/pdf/1905.01975)

