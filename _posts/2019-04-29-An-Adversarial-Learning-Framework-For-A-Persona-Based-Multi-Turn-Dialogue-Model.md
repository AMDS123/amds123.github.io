---
layout: post
title: "An Adversarial Learning Framework For A Persona-Based Multi-Turn Dialogue Model"
date: 2019-04-29 15:21:13
categories: arXiv_CL
tags: arXiv_CL Sentiment Adversarial GAN Quantitative
author: Oluwatobi Olabiyi, Anish Khazane, Alan Salimov, Erik T. Mueller
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we extend the persona-based sequence-to-sequence (Seq2Seq) neural network conversation model to a multi-turn dialogue scenario by modifying the state-of-the-art hredGAN architecture to simultaneously capture utterance attributes such as speaker identity, dialogue topic, speaker sentiments and so on. The proposed system, phredGAN has a persona-based HRED generator (PHRED) and a conditional discriminator. We also explore two approaches to accomplish the conditional discriminator: (1) phredGAN_a, a system that passes the attribute representation as an additional input into a traditional adversarial discriminator, and (2) phredGAN_d, a dual discriminator system which in addition to the adversarial discriminator, collaboratively predicts the attribute(s) that generated the input utterance. To demonstrate the superior performance of phredGAN over the persona Seq2Seq model, we experiment with two conversational datasets, the Ubuntu Dialogue Corpus (UDC) and TV series transcripts from the Big Bang Theory and Friends. Performance comparison is made with respect to a variety of quantitative measures as well as crowd-sourced human evaluation. We also explore the trade-offs from using either variant of phredGAN on datasets with many but weak attribute modalities (such as with Big Bang Theory and Friends) and ones with few but strong attribute modalities (customer-agent interactions in Ubuntu dataset).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01992](http://arxiv.org/abs/1905.01992)

##### PDF
[http://arxiv.org/pdf/1905.01992](http://arxiv.org/pdf/1905.01992)

