---
layout: post
title: "SEQ^3: Differentiable Sequence-to-Sequence-to-Sequence Autoencoder for Unsupervised Abstractive Sentence Compression"
date: 2019-04-07 13:47:28
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Optimization Language_Model
author: Christos Baziotis, Ion Androutsopoulos, Ioannis Konstas, Alexandros Potamianos
mathjax: true
---

* content
{:toc}

##### Abstract
Neural sequence-to-sequence models are currently the dominant approach in several natural language processing tasks, but require large parallel corpora. We present a sequence-to-sequence-to-sequence autoencoder (SEQ^3), consisting of two chained encoder-decoder pairs, with words used as a sequence of discrete latent variables. We apply the proposed model to unsupervised abstractive sentence compression, where the first and last sequences are the input and reconstructed sentences, respectively, while the middle sequence is the compressed sentence. Constraining the length of the latent word sequences forces the model to distill important information from the input. A pretrained language model, acting as a prior over the latent sequences, encourages the compressed sentences to be human-readable. Continuous relaxations enable us to sample from categorical distributions, allowing gradient-based optimization, unlike alternatives that rely on reinforcement learning. The proposed model does not require parallel text-summary pairs, achieving promising results in unsupervised sentence compression on benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03651](http://arxiv.org/abs/1904.03651)

##### PDF
[http://arxiv.org/pdf/1904.03651](http://arxiv.org/pdf/1904.03651)

