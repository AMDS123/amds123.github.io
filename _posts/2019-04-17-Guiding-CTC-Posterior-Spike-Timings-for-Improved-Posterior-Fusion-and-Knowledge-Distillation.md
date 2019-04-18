---
layout: post
title: "Guiding CTC Posterior Spike Timings for Improved Posterior Fusion and Knowledge Distillation"
date: 2019-04-17 15:18:23
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Speech_Recognition Classification Language_Model Recognition
author: Gakuto Kurata, Kartik Audhkhasi
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional automatic speech recognition (ASR) systems trained from frame-level alignments can easily leverage posterior fusion to improve ASR accuracy and build a better single model with knowledge distillation. End-to-end ASR systems trained using the Connectionist Temporal Classification (CTC) loss do not require frame-level alignment and hence simplify model training. However, sparse and arbitrary posterior spike timings from CTC models pose a new set of challenges in posterior fusion from multiple models and knowledge distillation between CTC models. We propose a method to train a CTC model so that its spike timings are guided to align with those of a pre-trained guiding CTC model. As a result, all models that share the same guiding model have aligned spike timings. We show the advantage of our method in various scenarios including posterior fusion of CTC models and knowledge distillation between CTC models with different architectures. With the 300-hour Switchboard training data, the single word CTC model distilled from multiple models improved the word error rates to 13.7%/23.1% from 14.9%/24.1% on the Hub5 2000 Switchboard/CallHome test sets without using any data augmentation, language model, or complex decoder.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08311](http://arxiv.org/abs/1904.08311)

##### PDF
[http://arxiv.org/pdf/1904.08311](http://arxiv.org/pdf/1904.08311)

