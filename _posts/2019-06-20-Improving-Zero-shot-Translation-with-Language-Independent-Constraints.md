---
layout: post
title: "Improving Zero-shot Translation with Language-Independent Constraints"
date: 2019-06-20 12:49:17
categories: arXiv_CL
tags: arXiv_CL Regularization NMT
author: Ngoc-Quan Pham, Jan Niehues, Thanh-Le Ha, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
An important concern in training multilingual neural machine translation (NMT) is to translate between language pairs unseen during training, i.e zero-shot translation. Improving this ability kills two birds with one stone by providing an alternative to pivot translation which also allows us to better understand how the model captures information between languages. 
 In this work, we carried out an investigation on this capability of the multilingual NMT models. First, we intentionally create an encoder architecture which is independent with respect to the source language. Such experiments shed light on the ability of NMT encoders to learn multilingual representations, in general. Based on such proof of concept, we were able to design regularization methods into the standard Transformer model, so that the whole architecture becomes more robust in zero-shot conditions. We investigated the behaviour of such models on the standard IWSLT 2017 multilingual dataset. We achieved an average improvement of 2.23 BLEU points across 12 language pairs compared to the zero-shot performance of a state-of-the-art multilingual system. Additionally, we carry out further experiments in which the effect is confirmed even for language pairs with multiple intermediate pivots.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08584](http://arxiv.org/abs/1906.08584)

##### PDF
[http://arxiv.org/pdf/1906.08584](http://arxiv.org/pdf/1906.08584)

