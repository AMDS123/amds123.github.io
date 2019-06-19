---
layout: post
title: "Scheduled Sampling for Transformers"
date: 2019-06-18 15:46:08
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Prediction
author: Tsvetomila Mihaylova, Andr&#xe9; F. T. Martins
mathjax: true
---

* content
{:toc}

##### Abstract
Scheduled sampling is a technique for avoiding one of the known problems in sequence-to-sequence generation: exposure bias. It consists of feeding the model a mix of the teacher forced embeddings and the model predictions from the previous step in training time. The technique has been used for improving the model performance with recurrent neural networks (RNN). In the Transformer model, unlike the RNN, the generation of a new word attends to the full sentence generated so far, not only to the last word, and it is not straightforward to apply the scheduled sampling technique. We propose some structural changes to allow scheduled sampling to be applied to Transformer architecture, via a two-pass decoding strategy. Experiments on two language pairs achieve performance close to a teacher-forcing baseline and show that this technique is promising for further exploration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07651](http://arxiv.org/abs/1906.07651)

##### PDF
[http://arxiv.org/pdf/1906.07651](http://arxiv.org/pdf/1906.07651)

