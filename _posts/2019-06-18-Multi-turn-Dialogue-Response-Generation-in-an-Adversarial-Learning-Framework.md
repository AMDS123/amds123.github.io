---
layout: post
title: "Multi-turn Dialogue Response Generation in an Adversarial Learning Framework"
date: 2019-06-18 13:26:28
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Embedding Inference RNN
author: Oluwatobi Olabiyi, Alan Salimov, Anish Khazane, Erik T. Mueller
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an adversarial learning approach for generating multi-turn dialogue responses. Our proposed framework, hredGAN, is based on conditional generative adversarial networks (GANs). The GAN's generator is a modified hierarchical recurrent encoder-decoder network (HRED) and the discriminator is a word-level bidirectional RNN that shares context and word embeddings with the generator. During inference, noise samples conditioned on the dialogue history are used to perturb the generator's latent space to generate several possible responses. The final response is the one ranked best by the discriminator. The hredGAN shows improved performance over existing methods: (1) it generalizes better than networks trained using only the log-likelihood criterion, and (2) it generates longer, more informative and more diverse responses with high utterance and topic relevance even with limited training data. This improvement is demonstrated on the Movie triples and Ubuntu dialogue datasets using both automatic and human evaluations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.11752](http://arxiv.org/abs/1805.11752)

##### PDF
[http://arxiv.org/pdf/1805.11752](http://arxiv.org/pdf/1805.11752)

