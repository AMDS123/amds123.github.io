---
layout: post
title: "Lightweight Convolutional Approaches to Reading Comprehension on SQuAD"
date: 2018-10-19 20:32:36
categories: arXiv_AI
tags: arXiv_AI Regularization Attention CNN RNN
author: Tobin Bell, Benjamin Penchas
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art reading comprehension models rely heavily on recurrent neural networks. We explored an entirely different approach to question answering: a convolutional model. By their nature, these convolutional models are fast to train and capture local dependencies well, though they can struggle with longer-range dependencies and thus require augmentation to achieve comparable performance to RNN-based models. We conducted over two dozen controlled experiments with convolutional models and various kernel/attention/regularization schemes to determine the precise performance gains of each strategy, while maintaining a focus on speed. We ultimately ensembled three models: crossconv (0.5398 dev F1), attnconv (0.5665), and maybeconv (0.5285). The ensembled model was able to achieve a 0.6238 F1 score using the official SQuAD evaluation script. Our individual convolutional model crossconv was able to exceed the performance of the RNN-plus-attention baseline by 25% while training 6 times faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08680](http://arxiv.org/abs/1810.08680)

##### PDF
[http://arxiv.org/pdf/1810.08680](http://arxiv.org/pdf/1810.08680)

