---
layout: post
title: "Mask-Predict: Parallel Decoding of Conditional Masked Language Models"
date: 2019-09-04 16:31:39
categories: arXiv_AI
tags: arXiv_AI Language_Model
author: Marjan Ghazvininejad, Omer Levy, Yinhan Liu, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
Most machine translation systems generate text autoregressively from left to right. We, instead, use a masked language modeling objective to train a model to predict any subset of the target words, conditioned on both the input text and a partially masked target translation. This approach allows for efficient iterative decoding, where we first predict all of the target words non-autoregressively, and then repeatedly mask out and regenerate the subset of words that the model is least confident about. By applying this strategy for a constant number of iterations, our model improves state-of-the-art performance levels for non-autoregressive and parallel decoding translation models by over 4 BLEU on average. It is also able to reach within about 1 BLEU point of a typical left-to-right transformer model, while decoding significantly faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09324](http://arxiv.org/abs/1904.09324)

##### PDF
[http://arxiv.org/pdf/1904.09324](http://arxiv.org/pdf/1904.09324)

