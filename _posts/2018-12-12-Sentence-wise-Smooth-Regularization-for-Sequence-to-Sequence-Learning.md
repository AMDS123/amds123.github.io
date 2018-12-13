---
layout: post
title: "Sentence-wise Smooth Regularization for Sequence to Sequence Learning"
date: 2018-12-12 02:47:11
categories: arXiv_CL
tags: arXiv_CL Regularization Summarization Classification Prediction
author: Chengyue Gong, Xu Tan, Di He, Tao Qin
mathjax: true
---

* content
{:toc}

##### Abstract
Maximum-likelihood estimation (MLE) is widely used in sequence to sequence tasks for model training. It uniformly treats the generation/prediction of each target token as multi-class classification, and yields non-smooth prediction probabilities: in a target sequence, some tokens are predicted with small probabilities while other tokens are with large probabilities. According to our empirical study, we find that the non-smoothness of the probabilities results in low quality of generated sequences. In this paper, we propose a sentence-wise regularization method which aims to output smooth prediction probabilities for all the tokens in the target sequence. Our proposed method can automatically adjust the weights and gradients of each token in one sentence to ensure the predictions in a sequence uniformly well. Experiments on three neural machine translation tasks and one text summarization task show that our method outperforms conventional MLE loss on all these tasks and achieves promising BLEU scores on WMT14 English-German and WMT17 Chinese-English translation task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04784](http://arxiv.org/abs/1812.04784)

##### PDF
[http://arxiv.org/pdf/1812.04784](http://arxiv.org/pdf/1812.04784)

