---
layout: post
title: "Multi-turn Dialogue Response Generation with Autoregressive Transformer Models"
date: 2019-07-26 21:53:09
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Oluwatobi Olabiyi, Erik T. Mueller
mathjax: true
---

* content
{:toc}

##### Abstract
Neural dialogue models, despite their successes, still suffer from lack of relevance, diversity, and in many cases coherence in their generated responses. These issues have been attributed to reasons including (1) short-range model architectures that capture limited temporal dependencies, (2) limitations of the maximum likelihood training objective, (3) the concave entropy profile of dialogue datasets resulting into short and generic responses, and (4) out-of-vocabulary problem leading to generation of a large number of $<$UNK$>$ tokens. Autoregressive transformer models such as GPT-2, although trained with the maximum likelihood objective, do not suffer from the out-of-vocabulary problem and have demonstrated an excellent ability to capture long-range structures in language modeling tasks. In this paper, we examine the use of autoregressive transformer models for multi-turn dialogue response generation. In our experiments, we employ small and medium GPT-2 models (with publicly available pretrained language model parameters) on the open-domain Movie Triples dataset and the closed-domain Ubuntu Dialogue dataset. The models (with and without pretraining) achieve significant improvements over the baselines for multi-turn dialogue response generation. They also produce state-of-the-art performance on the two datasets based on several metrics, including BLEU, ROGUE, and distinct n-gram.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.01841](https://arxiv.org/abs/1908.01841)

##### PDF
[https://arxiv.org/pdf/1908.01841](https://arxiv.org/pdf/1908.01841)

