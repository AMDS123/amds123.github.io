---
layout: post
title: "Multi-turn Dialogue Response Generation in an Adversarial Learning Framework"
date: 2018-09-19 13:35:08
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Embedding Inference RNN
author: Oluwatobi Olabiyi, Alan Salimov, Anish Khazane, Erik T. Mueller
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an adversarial learning approach to the generation of multi-turn dialogue responses. Our proposed framework, hredGAN, is based on conditional generative adversarial networks (GANs). The GAN's generator is a modified hierarchical recurrent encoder-decoder network (HRED) and the discriminator is a word-level bidirectional RNN that shares context and word embedding with the generator. During inference, noise samples conditioned on the dialogue history are used to perturb the generator's latent space to generate several possible responses. The final response is the one ranked best by the discriminator. The hredGAN shows major advantages over existing methods: (1) it generalizes better than networks trained using only the log-likelihood criterion, and (2) it generates longer, more informative and more diverse responses with high utterance and topic relevance even with limited training data. This superiority is demonstrated on the Movie triples and Ubuntu dialogue datasets in terms of perplexity, BLEU, ROUGE and Distinct n-gram scores.

##### Abstract (translated by Google)
我们提出了一种对抗性学习方法来产生多转对话。我们提出的框架hredGAN基于条件生成对抗网络（GAN）。 GAN的生成器是修改的分层递归编码器 - 解码器网络（HRED），并且鉴别器是与发生器共享上下文和字嵌入的字级双向RNN。在推理期间，以对话历史为条件的噪声样本用于扰乱发生器的潜在空间以产生若干可能的响应。最终的答案是鉴别者排名最高的答案。 hredGAN显示出优于现有方法的主要优势：（1）它比仅使用对数似然准则训练的网络更好地推广;（2）它产生更长，更丰富和更多样化的响应，即使在训练有限的情况下也具有高话语和主题相关性数据。电影三元组和Ubuntu对话数据集在困惑，BLEU，ROUGE和不同的n-gram分数方面证明了这种优势。

##### URL
[http://arxiv.org/abs/1805.11752](http://arxiv.org/abs/1805.11752)

##### PDF
[http://arxiv.org/pdf/1805.11752](http://arxiv.org/pdf/1805.11752)

