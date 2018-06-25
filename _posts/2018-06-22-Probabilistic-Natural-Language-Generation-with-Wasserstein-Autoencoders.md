---
layout: post
title: "Probabilistic Natural Language Generation with Wasserstein Autoencoders"
date: 2018-06-22 01:11:40
categories: arXiv_CL
tags: arXiv_CL
author: Hareesh Bahuleyan, Lili Mou, Kartik Vamaraju, Hao Zhou, Olga Vechtomova
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic generation of natural language sentences is an important task in NLP. Existing models such as variational autoencoders (VAE) for sequence generation are extremely difficult to train due to the issues associated with the Kullback-Leibler (KL) loss collapsing to zero. One has to implement various heuristics such as KL weight annealing and word dropout in a carefully engineered manner to successfully train a text VAE. In this paper, we propose the use of Wasserstein autoencoders (WAE) for probabilistic natural language sentence generation. We show that sequence-to-sequence WAEs are more robust towards hyperparameters and can be trained in a straightforward manner without the need for any weight annealing. Empirical evidence shows that the latent space learned by WAEs exhibits properties of continuity and smoothness as in VAEs, while simultaneously achieving much higher BLEU scores for sentence reconstruction.

##### Abstract (translated by Google)
自然语言句子的概率生成是NLP中的一项重要任务。由于与Kullback-Leibler（KL）损失坍缩为零有关的问题，用于序列生成的现有模型（如变分自编码器（VAE））非常难以训练。必须以精心设计的方式实施各种启发式措施，如KL重量退火和单词退出，以成功培训文本VAE。在本文中，我们提出使用Wasserstein自动编码器（WAE）进行概率自然语言句子生成。我们证明序列到序列WAEs对于超参数更加稳健，并且可以以直接的方式进行训练而不需要任何权重退火。经验证据表明，WAEs学到的潜在空间表现出与VAE一样的连续性和平滑性，同时在句子重建中获得更高的BLEU分数。

##### URL
[http://arxiv.org/abs/1806.08462](http://arxiv.org/abs/1806.08462)

##### PDF
[http://arxiv.org/pdf/1806.08462](http://arxiv.org/pdf/1806.08462)

