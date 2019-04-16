---
layout: post
title: "Labeled Memory Networks for Online Model Adaptation"
date: 2017-12-02 07:31:20
categories: arXiv_CV
tags: arXiv_CV GAN RNN Classification Memory_Networks
author: Shiv Shankar, Sunita Sarawagi
mathjax: true
---

* content
{:toc}

##### Abstract
Augmenting a neural network with memory that can grow without growing the number of trained parameters is a recent powerful concept with many exciting applications. We propose a design of memory augmented neural networks (MANNs) called Labeled Memory Networks (LMNs) suited for tasks requiring online adaptation in classification models. LMNs organize the memory with classes as the primary key.The memory acts as a second boosted stage following a regular neural network thereby allowing the memory and the primary network to play complementary roles. Unlike existing MANNs that write to memory for every instance and use LRU based memory replacement, LMNs write only for instances with non-zero loss and use label-based memory replacement. We demonstrate significant accuracy gains on various tasks including word-modelling and few-shot learning. In this paper, we establish their potential in online adapting a batch trained neural network to domain-relevant labeled data at deployment time. We show that LMNs are better than other MANNs designed for meta-learning. We also found them to be more accurate and faster than state-of-the-art methods of retuning model parameters for adapting to domain-specific labeled data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.01461](https://arxiv.org/abs/1707.01461)

##### PDF
[https://arxiv.org/pdf/1707.01461](https://arxiv.org/pdf/1707.01461)

