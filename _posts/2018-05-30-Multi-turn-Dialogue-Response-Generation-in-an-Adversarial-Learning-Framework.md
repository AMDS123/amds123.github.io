---
layout: post
title: "Multi-turn Dialogue Response Generation in an Adversarial Learning Framework"
date: 2018-05-30 00:05:53
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Embedding Inference RNN
author: Oluwatobi Olabiyi, Alan Salimov, Anish Khazane, Erik Mueller
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an adversarial learning approach to the generation of multi-turn dialogue responses. Our proposed framework, hredGAN, is based on conditional generative adversarial networks (GANs). The GAN's generator is a modified hierarchical recurrent encoder-decoder network (HRED) and the discriminator is a word-level bidirectional RNN that shares context and word embedding with the generator. During inference, noise samples conditioned on the dialogue history are used to perturb the generator's latent space to generate several possible responses. The final response is the one ranked best by the discriminator. The hredGAN shows major advantages over existing methods: (1) it generalizes better than networks trained using only the log-likelihood criterion, and (2) it generates longer, more informative and more diverse responses with high utterance and topic relevance even with limited training data. This superiority is demonstrated on the Movie triples and Ubuntu dialogue datasets in terms of perplexity, BLEU, ROUGE and Distinct n-gram scores.

##### Abstract (translated by Google)
我们提出了一种针对多回合对话反应的对抗学习方法。我们提出的框架hredGAN基于条件生成对抗网络（GAN）。 GAN的生成器是修改后的分层循环编码器 - 解码器网络（HRED），鉴别器是一个字级双向RNN，与发生器共享上下文和字嵌入。在推理过程中，以对话历史为条件的噪声样本被用来扰动发生器的潜在空间以产生几种可能的响应。最终的回应是鉴别者排名最好的那个。与现有方法相比，hredGAN具有以下主要优点：（1）它优于仅使用对数似然标准训练的网络;（2）即使训练有限，也可产生更长，更丰富和更多样化的反应，并具有高度的话语和主题相关性数据。这种优越性在Movie triples和Ubuntu对话数据集中以困惑，BLEU，ROUGE和独特的n-gram分数表现出来。

##### URL
[http://arxiv.org/abs/1805.11752](http://arxiv.org/abs/1805.11752)

##### PDF
[http://arxiv.org/pdf/1805.11752](http://arxiv.org/pdf/1805.11752)

