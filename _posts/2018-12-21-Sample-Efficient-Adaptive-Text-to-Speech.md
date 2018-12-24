---
layout: post
title: "Sample Efficient Adaptive Text-to-Speech"
date: 2018-12-21 15:23:54
categories: arXiv_SD
tags: arXiv_SD Embedding Gradient_Descent
author: Yutian Chen, Yannis Assael, Brendan Shillingford, David Budden, Scott Reed, Heiga Zen, Quan Wang, Luis C. Cobo, Andrew Trask, Ben Laurie, Caglar Gulcehre, A&#xe4;ron van den Oord, Oriol Vinyals, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
We present a meta-learning approach for adaptive text-to-speech (TTS) with few data. During training, we learn a multi-speaker model using a shared conditional WaveNet core and independent learned embeddings for each speaker. The aim of training is not to produce a neural network with fixed weights, which is then deployed as a TTS system. Instead, the aim is to produce a network that requires few data at deployment time to rapidly adapt to new speakers. We introduce and benchmark three strategies: (i) learning the speaker embedding while keeping the WaveNet core fixed, (ii) fine-tuning the entire architecture with stochastic gradient descent, and (iii) predicting the speaker embedding with a trained neural network encoder. The experiments show that these approaches are successful at adapting the multi-speaker neural network to new speakers, obtaining state-of-the-art results in both sample naturalness and voice similarity with merely a few minutes of audio data from new speakers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.10460](http://arxiv.org/abs/1809.10460)

##### PDF
[http://arxiv.org/pdf/1809.10460](http://arxiv.org/pdf/1809.10460)

